# installation apache php
## apache
```bash
#telechargement du fichier source httpd-2.4.59.tar.gz
#en considérant que l'on part du repertoire par default pour toute les commandes
gunzip httpd-2.4.59.tar.gz
tar -xvf httpd-2.4.59.tar
cd httpd-2.4.59
./configure
#...erreur de dependance
nano README
nano INSTALL
./configure --help
#installation des librairies de apache
```
```bash
sudo apt install libpcre3-dev
sudo apt install lib-pcre-dev
sudo apt install lib-aprutil1-dev
sudo apt install libnghttp2
sudo apt install libxpat-dev
sudo apt install build-essential
sudo apt install g++ #compilateur c++

./configure --prefix=/usr/local/apache2
make
make install
apache -v
```

<img src="https://github.com/Heriandrisoa/devoir/blob/main/apache.png" alt="description">
<img src="https://github.com/Heriandrisoa/devoir/blob/main/apache.png" alt="description">
