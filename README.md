# Накрутка фотографий в ВК

**Требования**
1. Глобально установленный composer
2. Глобально установленный PHP версии не ниже 7.1

**Установка**
1. Склонируйте проект
2. Запустите `composer install`
3. Откройте файл `demon.php` в текстовом редакторе
4. В переменную $token вставьте ваш токен с правами `photos`
5. В переменную $album_id вставьте ID альбома в который будут загружаться фотки.
6. Сохраните файл и запустите файл start.bat

**Допустимые форматы**
1. JPG
2. PNG
3. GIF

**Ограничения**
1. Сумма высоты и ширины не более 14000px
2. Файл объемом не более 50 МБ
3. Соотношение сторон не менее 1:20
