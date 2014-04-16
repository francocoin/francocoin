Francocoin
================================

http://www.francocoin.es

![Franco](http://mm.queaprendemoshoy.com/wp-content/uploads/2013/05/bandera-franquista.png)

Copyright (c) 2009-2013 Bitcoin Developers
Copyright (c) 2011-2013 Litecoin Developers
Copyright (c) 2014 Francocoin Developers

¿Qué es Francocoin?
-------------------

Francocoin es una versión de Bitcoin que usa scrypt como algoritmo para verificar el trabajo

 - 1 minuto por bloque
 - ~100.000.000.000 Francocoins aproximadamente

El resto es igual que Bitcoin
 - 50 monedas por bloque
 - 2016 bloques para cambiar la dificultad

Licencia
--------

Francocoin se encuentra bajo los términos de la licencia MIT. http://opensource.org/licenses/MIT.

Testing
-------

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./litecoin-qt_test

