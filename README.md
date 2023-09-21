# **Yandex Music Discord Rich Presence**
Discord RPC для приложения и веб версии Яндекс Музыки

![ff](https://img.shields.io/badge/price-FREE-green)
![src](https://img.shields.io/badge/source%20code-open-red)
![src2](https://img.shields.io/badge/language-python-blue)

Доработка, улучшение кода/функционала : @liztochekcode

Автор идеи : liztochekcode

------------
## Требования
1. Google Chrome
2. Python 3.10+

## Как использовать?
1. Скачиваем барузер Google Chrome, нужно обязательно т.к. через него будет осуществляться авторизация в аккаунте яндекс для получения токена.
2. Скачиваем все файлы с репозитория
3. Открываем файл start.bat и ждём пока появится откроется гугл хром, входим в аккаунт яндекса
4. Ждём загрузки окна с названием "Яндекс Музыка"
5. После можно закрыть консоль

### Спойлер
Использовать код из этой программы можно без обязательного указания автора.
Автор данной программы не несёт ответственность за данные выших аккаунтов, он их не получает и никому не передаёт.
Все что вы делаете, вы делаете на свой страх и риск.

![image](data:image/png;base64,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)
