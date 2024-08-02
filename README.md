# Декрабизация Youtube в России

Браузерное расширение для обхода замедления Youtube в России.

## Инструкции

1. Необходимо запустить из командной строки вашей ОС Хром с выключенными [CORS](https://ru.wikipedia.org/wiki/Cross-origin_resource_sharing).  
   __ВНИМАНИЕ: Отключение CORS сделает ваш браузер уязвимым для некоторых атак__.  
   Здесь и далее `tmpDirForChrome` -- директория для временного хранения браузерных данных нового пользователя.
   - __Для Windows__:
     1) Нажать комбинацию клавиш `Win + R`, вписать команду `cmd`, нажать Enter.
     2) Откроется терминал. Введите в него (без `$`):

            $ chrome.exe --disable-web-security --user-data-dir=C:\tmpDirForChrome
     3) Если файл `chrome.exe` не будет найден, пропишите полный путь к нему.
        Полный путь можно подсмотреть на `chrome://extensions`, раздел "Executable Path".
   - __Для Linux/Unix__:

         $ google-chrome --disable-web-security --user-data-dir=/home/<username>/tmpDirForChrome/
3. Открыть в новой вкладке Хрома `chrome://extensions`.
4. Вкл. переключатель "Режим разработчика / Developer mode".
5. Перетащить на открытую в п.2 вкладку `.crx`-файл, скачанный из раздела [Releases](https://github.com/anticensority/decrab-youtube/releases) данного репозитория на GitHub.


### Attributions

- Youtube icon on black background from [www.vecteezy.com](https://www.vecteezy.com/free-vector/icons): https://www.vecteezy.com/vector-art/17796121-youtube-illustration-for-logo-or-icon.
- Crab icon from www.iconsdb.com: https://www.iconsdb.com/soylent-red-icons/crab-icon.html.
