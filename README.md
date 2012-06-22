heroku-cedar-php
================

Compiled a few library for Heroku's PHP extension - imagick.so, apc.so, gd.so

-----------------------------
Instruction for 'imagick.so':
----------------------------

1.  create folder "ext"

2.  put 'imagick.so' in "ext" folder

3.  create file "php.ini" in root folder of project

4.  Add these lines to "php.ini" 
<PRE>extension_dir = "/app/www/ext/"
  extension=imagick.so
</PRE>
5.  Run: git add php.ini ext/imagick.so

6.  Run: git commit -m "PHP's imagemagick library"

7.  Run: git push heroku master

