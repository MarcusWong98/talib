# talib
How to install talib


Download ta-lib-0.4.0-src.tar.gz and put it to the directory where you are planning to install talib, lets' say "~/talib" open bash and skip to the directory that you just put the downloaded file cd ~/talib:
    tar -xzf ta-lib-0.4.0-src.tar.gz
    cd ta-lib/
    ./configure --prefix=/usr
    make
    sudo make install
    add necessary directories to the path. To do that;

Edit .bashrc in your home directory and add the following line: please remember to change PREFIX with your path to talib (~/talib/ta-lib/)

    export TA_LIBRARY_PATH=$PREFIX/lib

    export TA_INCLUDE_PATH=$PREFIX/include

    pip install TA-Lib

