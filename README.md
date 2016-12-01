Учебная сборка Loftschool (выпускной проект №1)

Stack:

Gulp 4.0
Getting started:

1. clone this repo
2. cd path/to/
3. npm install gulpjs/gulp-cli -g // Install the latest Gulp CLI tools globally
4. npm install
5. run "gulp" command to start

__________________________________________________________________

Первый таск - генерация спрайтов из графических файлов (png, gif).

1. npm install gulp.spritesmith
2. create task gulp/tasks/sprite.png.js
3. in tasks.js create path to sprite.png.js
   
Второй таск - копирование файлов из папки с исходниками в папку для продакшена (картинки, шрифты).

1. creat task gulp/tasks/copy.fonts.js
2. in gulp/paths/tasks.js create path to copy.fonts.js
