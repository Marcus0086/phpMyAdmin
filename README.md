# phpMyAdmin
# In order to install use following steps:
$ git clone git@github.com:Marcus0086/marcus0087-crunch.git
$ pkg up
$ apt install mariadb php php-apache apache2
$ unzip phpMyAdmin.zip
$ cp -f mysl $PREFIX/bin
$ chmod +x $PREFIX/bin/mysl

# for apache2 
$ cd $PREFIX/etc/apache2
$ rm -f httpd.conf
$ cd $HOME/phpMyAdmin
$ cp -f httpd.conf $PREFIX/etc/apache2
 # to start both servers
 $ mysl
 $
 $ apachectl
 
 # to stop
 $ pkill mysql
 $ apachectl stop

# Server will be on 0.0.0.0:8080 interface
