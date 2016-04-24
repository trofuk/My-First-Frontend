Фронтенд проект

Був встановлений та використаний Gulp з наступними плагінами:
gulp-autoprefixer - автоматично додає вендорні префікси до CSS властивостей
gulp-minify-css - сжимає CSS код
browser-sync - розгортає локальний dev сервер 
gulp-imagemin - сжимає картинки 
imagemin-pngquant - доповнення до gulp-imagemin для роботи з .png
gulp-uglify - сжимає JS
gulp-sass - для компиляції SCSS кода
gulp-sourcemaps - для генерації css sourscemaps
gulp-rigger - дозволяє імпортувати один файл в інший
gulp-watch - спостерігає за зміною файлів
rimraf - для видалення файлів з папки build

Також був встановлений Bower з наступними пакетами:
Bootstrap Sass
jQuery
Normalize.css

src - папка з вхідними файлами проекта

build - папка з файлами після обробки 


Команди Gulp
gulp html:build - сборка html
gulp js:build   - сборка скриптів
gulp style:build - сборка стилів
gulp image:build - обробка картинок
gulp fonts:build - перекидання шрифтів

gulp build - попередні 5 команд разом

gulp watch - відстежує змінені файли і запускає відповідну задачу
gulp webserver - запускає livereload сервер, відкриває проект в браузері, в консоль пише посилання на локальний сервер, тунель для демонстрації замовнику
gulp clean - очищає папку build

gulp - запускає всю сборку