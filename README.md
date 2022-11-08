<img height="257" width="114" src="https://user-images.githubusercontent.com/25119216/200695956-17be5264-faef-424d-af7b-d4776bc86d41.png" style="display: block; margin: 0 auto;">
<p style="width: 100px; margin: 0 auto;" >My build Gulp</p>

Сборку буду дополнять или изменять по мере необходимости.

#### Применить сборку к проекту

Скопировать файлы себе на компьютер и ввести команду

	npm i

#### Чтобы запустить в режиме "разработчика"

	npm run dev // or gulp

+ не минифицируются файл css
+ не конвертируются изображения в WEBp
+ не сжимаются изображения
+ запускается сервер и остлеживает изменения

#### Чтобы собрать итоговую сборку

	npm run build

+ минифицируются файл css
+ конвертируются изображения в WEBp
+ сжимаются изображения
+ запускается сервер

В обоих сборках шрифты не отслеживаются, если в процессе работы установлены новые локальные шрифты, нужно перезапустить сборку.

	ctrl + C // остановить gulp