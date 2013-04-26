VAuth 8 
=======

DataLife Engine autorization through social networks

Russian description:
  Модуль авторизации и регистрации пользователей через социальные сети через протоколы OAuth.

Возможности модуля:

- Авторизация и регистрация пользователей на сайте через социальные сети
- Сопряжение аккантов DLE c каждой из доступных социальных сетей
- Последующая авторизация через любую из сетей будет вести в один и тот-же профиль
- Автоматическая установка аватарки пользователя при регистрации или подключении социальной сети
- Заполнение данных пользователя на основании информации, полученной из социальных сетей
- Вывод зарегистрированных друзей пользователя на сайте (друзей по социальным сетям, которые есть на этом-же сайте)
- Возможность задавать отдельную группу пользователя для каждой социальной сети.
- Сохранение возможности регистрации пользователей обычным способом
- Заполнение поля профиля DLE "О себе" (страна проживания, мобильный телефон, статус вконтакте, пол)
- Возможность смены e-mail пользователя без ошибок авторизации
- Возможность смены пароля пользователя без ошибок авторизации
- Возможность задавать размер аватарки пользователя, центрировать и обрезать её
- Переадресация пользователя после авторизации на ранее просматриваемую страницу
- Отправка ПС пользователю после регистрации с данными авторизации
- Возможность вывода формы ввода желаемого email/login/password при регистрации пользователя.

Организационные моменты:

- Весь текст вынесен в отдельный файл, для удобства перевода
- Статистика по пользователям в админ-панели
- Вывод всех зарегистрированных через vauth пользователей в админ-панели

Работа на UTF-8 движках:
- модуль работает, нужно конвертнуть /vauth/langfiles/russian.php в UTF-8 без BOM

Supported Networks:
- vk.com
- facebook.com
- google+
- mail.ru
- odnoklassniki.ru,

Authorization methods:
- OAuth 1.0
- OAuth 2.0

Info:
- vk.com/vauth
- dream-notes.ru
- vauth8.dream-notes.ru

Charset:
- win1251
