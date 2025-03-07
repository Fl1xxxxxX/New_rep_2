# Запись в файл личных данных пользователя и списка названий его репозиториев из профиля Github
Программа получает данные(имя, электронная почта, описание профиля, список репозиториев) из профиля пользователя на платформе Github, запускает HTTP сервер и выводит все данные на страницу в браузере.

## Установка программы
1. `pip install -r requirements.txt`
2. Создать файл `.env` в формате:

```API_TOKEN = ваш токен github(```[можно получить в настройках](https://docs.github.com/ru/enterprise-cloud@latest/authentication/authenticating-with-saml-single-sign-on/authorizing-a-personal-access-token-for-use-with-saml-single-sign-on)```)```
```USER_NAME = <ваше имя пользователя github>```

## Запуск программы
`python app.py
