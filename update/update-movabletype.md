### Обновление Movable Type

Существует 2 варианта обновления. Перед каждым обновлением не забывайте делать резервные копии: как базы данных, так и файлов Movable Type.

#### 1 вариант: перезапись существующих файлов

* Скачайте последнюю версию Movable Type: http://movable-type.ru/mt4 или http://movable-type.ru/mt5.
* Разархивируйте дистрибутив и загрузите все файлы на сервер, перезаписав старые файлы (кроме файла mt-config.cgi).
* Откройте Movable Type в браузере и пройдите процесс обновления.

#### 2 вариант: переименование каталога установки

* Скачайте последнюю версию Movable Type: http://movable-type.ru/mt4 или http://movable-type.ru/mt5.
* Переименуйте на сервере вашу папку Movable Type. Например, если ваша папка называлась «mt», то можно переименовать её в «mt-old».
* Создайте новую папку «mt» и загрузите в неё файлы дистрибутива, а затем из старой папки скопируйте в новую файл mt-config.cgi.
* Откройте Movable Type в браузере и пройдите процесс обновления.

Папку `mt-static` следует обновлять исключительно методом перезаписывания файлов, так как в ней содержатся мини-копии картинок, а также другие статические файлы, сгенерированные Movable Type.