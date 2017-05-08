---
layout: hary
title: new lines
---
to cut every space into new lines

for example, we have some text like this

```
cat cent6.txt
 software="nginx httpd mod_ssl mod_ruid2 mod_fcgid mod_extract_forwarded
    php php-common php-cli php-bcmath php-gd php-imap php-mbstring php-mcrypt
    php-mysql php-pdo php-soap php-tidy php-xml php-xmlrpc php-fpm php-pgsql
    awstats webalizer vsftpd proftpd bind bind-utils bind-libs exim dovecot
    clamd spamassassin roundcubemail mysql mysql-server phpMyAdmin postgresql
    postgresql-server postgresql-contrib phpPgAdmin e2fsprogs openssh-clients
    ImageMagick curl mc screen ftp zip unzip flex sqlite pcre sudo bc jwhois
    mailx lsof tar telnet rrdtool net-tools ntp GeoIP freetype fail2ban
    which vesta vesta-nginx vesta-php vim-common expect"
```

then want to make it vertical, which means, we want to change `space` into `new line`

     cat cent6.txt | tr " " "\n" | grep .

and you get the result :

```
software="nginx
httpd
mod_ssl
mod_ruid2
mod_fcgid
mod_extract_forwarded
php
php-common
php-cli
php-bcmath
php-gd
php-imap
php-mbstring
php-mcrypt
php-mysql
php-pdo
php-soap
php-tidy
php-xml
php-xmlrpc
php-fpm
php-pgsql
awstats
webalizer
vsftpd
proftpd
bind
bind-utils
bind-libs
exim
dovecot
clamd
spamassassin
roundcubemail
mysql
mysql-server
phpMyAdmin
postgresql
postgresql-server
postgresql-contrib
phpPgAdmin
e2fsprogs
openssh-clients
ImageMagick
curl
mc
screen
ftp
zip
unzip
flex
sqlite
pcre
sudo
bc
jwhois
mailx
lsof
tar
telnet
rrdtool
net-tools
ntp
GeoIP
freetype
fail2ban
which
vesta
vesta-nginx
vesta-php
vim-common
expect"
```

That's it for today.

Thank you.
