heroku-cedar-php
================

Compiled a few library for Heroku's PHP extension - imagick.so, apc.so, gd.so

-----------------------------
Instruction for 'imagick.so':
----------------------------

1.  create folder "__ext__" in project folder

2.  put "__imagick.so__" in "ext" folder

3.  create file "__php.ini__" in main folder of project

4.  Add these lines to "__php.ini__" 
<PRE>extension_dir = "/app/www/ext/"
  extension=imagick.so
</PRE>
5.  Run: __git add php.ini ext/imagick.so__

6.  Run: __git commit -m "PHP's imagemagick library"__

7.  Run: __git push heroku master__

Google it for these extensions: zlib.so, mbstring.so, mongodb.so