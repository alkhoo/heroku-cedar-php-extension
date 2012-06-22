heroku-php-imagemagick
======================

Heroku's PHP extension: imagick.so, apc.so, gd.so

Instruction for 'imagick.so':
+ create folder "ext"
+ put 'imagick.so' in "ext" folder
+ create file "php.ini" in root folder of project
+ Add these lines to "php.ini" 
+ + extension_dir = "/app/www/ext/"
+ + extension=imagick.so
+ git add php.ini ext/imagick.so
+ git commit -m "PHP's imagemagick library"
+ git push heroku master

