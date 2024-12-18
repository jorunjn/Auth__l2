Описание
Проект состоит из трех основных HTML-страниц и одного CSS-файла:
1. **main.html** — Главная страница и регистрация.  
   Пользователь может зарегистрироваться, указав email, пароль (два раза для проверки), никнейм, выбрать пол. После успешной регистрации данные сохраняются в `localStorage`. Пользователь остаётся на этой же странице, получая сообщение об успешной регистрации, и может перейти к авторизации.

2. **backend.html** — Страница логина.  
   Пользователь вводит email и пароль, и при совпадении с сохранёнными данными попадает на страницу "о вас".

3. **develop.html** — Страница "о вас".  
   Здесь отображаются email, дата регистрации, никнейм и пол, взятые из `localStorage`. Есть кнопка "Log out", которая очищает данные и возвращает пользователя на главную страницу.

4. **frontend.css** — Файл со стилями для оформления внешнего вида проекта.

Как взаимодействовать с проектом
1. Откройте `main.html` в браузере.
2. Введите Email, Password, Confirm password, Nickname и выберите пол.
3. Нажмите "Sign up". При успешной регистрации увидите уведомление.
4. Вернитесь или перейдите по ссылке "Log in" в шапке, чтобы открыть `backend.html`.
5. Введите зарегистрированный email и пароль. При верных данных вы будете перенаправлены на `develop.html`.
6. На `develop.html` отображаются сохранённые данные. Нажмите "Log out" для выхода и очистки данных.

Структура проекта
- `main.html` — Регистрация (главная страница).
- `backend.html` — Авторизация.
- `develop.html` — Отображение информации о пользователе.
- `frontend.css` — Стили для всех страниц.
