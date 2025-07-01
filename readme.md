![version](https://img.shields.io/badge/version-1.0-red.svg?style=flat-square "Version Frontend-kit")
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/sinups/)

## Стартовый проект frontend-kit 🔥


👦   Автор : [ A K ](https://www.instagram.com/webtheory/ "Instagram page")

## Стартовий репозиторій .

Встановлення: `npm i`.

Запуск: `npm start`.

Збірка - `<b>`Gulp 4`</b>`

Запуск конкретної задачі: `npm start имя_задачи` (список задач  в `gulpfile.js`)

Зупинка: `<kbd>`Ctrl + C`</kbd>`

## Bивід svg sprite

`<svg class="custom-class" width="14px" height="14px"><use xlink:href="img/sprite-svg.svg#img_name"></use></svg>`

Або можете зробити include  зверху сайта  нижче тега `Body`

`@@include('img/sprite-svg.svg')`

Та виводити на сторінці таким чином:

`<svg  width="28"  height="28"  class="custom_class"><use  xlink:href="#image_name"></use></svg>`

## Bивід png sprite

Надані міксини призначені для використання зі змінними

` .icon-imagename {   @include sprite($image_name); }`

Приклад використання в HTML:

`display: block` sprite:

`<div class="icon-imagename"></div>`

Змініть `display` ( `display: inline-block;`), ми пропонуємо використовувати загальний css клас:

CSS

`.icon {   display: inline-block; }`

HTML

`<i class="icon icon-home"></i>`


## Оновити залежності

Видаляємо:
node_modules
package-lock.json
package.json

Встановлюємо:
npm install gulp gulp-sass sass gulp-rename gulp-sourcemaps gulp-postcss css-mqpacker gulp-replace gulp-svgmin gulp-notify gulp-plumber gulp-cleancss gulp-file-include gulp-html-beautify gulp.spritesmith merge-stream vinyl-buffernpm install gulp gulp-sass sass gulp-renas gulp-replace del@3.0.0 browser-sync gulp-gh-pages gulp-newer gulp-uglify gulp-concat gulp-cheerio gulp-svgstore gulp.spritesmith merge-stream vinyl-buffer
