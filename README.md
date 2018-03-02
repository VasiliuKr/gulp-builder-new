#Cборка для разработки frontend

Стек технологий:
 - Gulp 4.0
 - Bower
 - Pug
 - SCSS
 
Getting started:

1. клонируем данный репозиторий git clone https://github.com/VasiliuKr/gulp-builder-new.git
2. переходим в папку склонированного проекта cd gulp-builder-new
3. npm install gulpjs/gulp-cli -g  // Установим последнюю версию (4.0) Gulp глобально
4. если в системе не установлен bower, то устанавливаем глобально npm install -g bower  (возможно, выскочит предупреждение об устаревшей версии bower c предложением миграции на Yarn)
5. npm install  На этом шаге могут возникнуть различные ошибки. Например, связанные с устаревшими версиями gulp-плагинов. Корректируем package.json, где указываем актуальные версии плагинов. Плагины ищем на https://www.npmjs.com/ или https://gulpjs.com/plugins/
6. run "gulp" command to start
7. переходим в браузере на localhost:3000


