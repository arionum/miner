# miner
Proof of Concept Arionum Miner

Requires php 7.2 , php-gmp and php-openssl

For solo mining:

Usage: ./miner solo [node] [public_key] [private_key]
The miner's IP must be added in the node's allowed hosts.


For pool mining:

Usage: ./miner pool http://aropool.com [address]



To install php from source in ubuntu/debian/mint:

`wget -O php-7.2.1.tar.gz http://php.net/get/php-7.2.1.tar.gz/from/this/mirror`

`tar -xvzf php-7.2.1.tar.gz`

`sudo apt-get install autoconf automake libtool re2c flex bison libssl-dev libgmp-dev libgmp10 libcurl4-openssl-dev openssl libzip4 libargon2-0 libargon2-0-dev libxml2-dev pkg-config libxml2 libzip-dev libreadline7 libreadline-dev`

`cd php-7.2.1/`

`./configure --disable-cgi     --with-gmp     --enable-mysqlnd     --with-pdo-mysql     --with-pdo-mysql=mysqlnd     --enable-bcmath     --enable-fpm     --with-fpm-user=www-data     --with-fpm-group=www-data     --enable-mbstring     --enable-phpdbg     --enable-shmop     --enable-sockets     --enable-sysvmsg     --enable-sysvsem     --enable-sysvshm     --enable-zip     --with-libzip     --with-zlib     --with-curl     --with-pear     --with-mhash     --with-openssl     --enable-pcntl     --with-readline  --with-password-argon2`

If you want php installed to /usr/bin then use:

`./configure --disable-cgi     --with-gmp     --enable-mysqlnd     --with-pdo-mysql     --with-pdo-mysql=mysqlnd     --enable-bcmath     --enable-fpm     --with-fpm-user=www-data     --with-fpm-group=www-data     --enable-mbstring     --enable-phpdbg     --enable-shmop     --enable-sockets     --enable-sysvmsg     --enable-sysvsem     --enable-sysvshm     --enable-zip     --with-libzip     --with-zlib     --with-curl     --with-pear     --with-mhash     --with-openssl     --enable-pcntl     --with-readline  --with-password-argon2 --prefix=/usr  --sysconfdir=/etc  --localstatedir=/var  --datadir=/usr/share/php    --mandir=/usr/share/man `

Otherwise it will install to /usr/local/bin

`make`

`sudo make install`




Development Fund:

ARO: 5WuRMXGM7Pf8NqEArVz1NxgSBptkimSpvuSaYC79g1yo3RDQc8TjVtGH5chQWQV7CHbJEuq9DmW5fbm CEW4AghQr

LTC: LWgqzbXGeucKaMmJEvwaAWPFrAgKiJ4Y4m

BTC: 1LdoMmYitb4C3pXoGNLL1VRj7xk3smGXoU

ETH: 0x4B904bDf071E9b98441d25316c824D7b7E447527

BCH: qrtkqrl3mxzdzl66nchkgdv73uu3rf7jdy7el2vduw

If you'd like to support the Arionum development, you can donate to the addresses listed above.