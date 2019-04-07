# Тестовое задание и code-review для новичков (frontend, react)

## О себе  

Работаю фронтенд разработчиком 1.5 года,  
React изучал около двух недель => один сайт (<https://fyodor.pp.ua/>)  
+1.5 месяца на приложение на React Native => (<https://drive.google.com/file/d/14cWUiowDiszsuiSkYwdAZYm9AGpusH-6/view?usp=drive_open)>

### Про приложение  

-выполнен базовый функционал  
-использованы react-hooks  
-оформление - semantic-ui-react  
-demo (ссылка)

#### Задание

Ключевой игрок - React. Задание подходит новичкам, не подходит опытным разработчикам [1].
[1] - для тех, кто с легкостью пишет на JS и React, предлагаем выполнить данное ТЗ на TypeScript и Reach router. А также вы можете дополнить выполнение Docker-
образом. Получите новый опыт.
Участие бесплатное.
Что проверяем?
Начальные знания по React, Redux и роутингу.
Порядок проведения
Вы выполняете задание и присылаете письмо со ссылкой на гитхаб. На разборе обсуждаются как коллективные ошибки, так и индивидуальные. Так же 
обсуждаются хорошие решения и выбираются топ-3 работы.
Плюсы:
вам указывают на ошибку
вам подсказывают решение
вы смотрите как эту же проблему решали другие участники
Минусы:
публичное порицание за халтуру (не путать с “непреднамеренными ошибками”)
Рекомендации к выполнению
Заполните README .md по образцу
После того как сделали, посмотрите подобный разбор (видео), исправьте ошибки.
Для тех, кто пишет на TS - используйте строгие правила:
noImplicitAny
noImplicitThis
alwaysStrict
strictNullChecks
strictFunctionTypes
strictPropertyInitialization
Подробнее здесь (EN).
Предоставьте ссылку на demo и добавьте оформление проекту.
Дедлайн
Прием работ заканчивается ровно через месяц: 11 апреля 2019 года. Не тормозите, изучение без практики невозможно.
Если есть вопросы - задавайте в комментариях.

==================

TZ #1 v.2.0
Задача
Реализовать приложение, которое умеет показывать следующие страницы:
/ - главная
/login - страница ввода логина и пароля
/news - страница с новостями (любая однотипная информация)
/profile - страница с произвольным текстом, недоступная без авторизации
На сайте, в шапке или подвале реализовать ссылки:
На главную (/)
Новости (/news)
Профиль (/profile)
Если пользователь кликает на страницу “профиля” и он не “авторизован” - перекидывать на страницу /login
Форма входа (/login) принимает “фейковые” данные:
username: Admin
password: 12345
Если введены другие данные, то показывается сообщения:
Имя пользователя или пароль введены не верно
Если введены корректные данные, то перебрасывать на страницу /profile
Информацию об авторизации пользователя можно хранить в localStorage, простым параметром true/false. Базу данных реализовать не нужно.
Запрос за новостями, попытку залогиниться и все что посчитаете нужным - пробросить через Redux.
Оформление (дизайн) — не важно. Сделайте, чтобы можно было комфортно смотреть пример в браузере.
Условия
Код оформить на GitHub с толковым Readme .md (образец), ссылку прислать на почту maxpfrontend@gmail.com, в письме укажите ваш опыт работы с данными технологиями.
Дедлайн
Работы принимаются до 11 апреля 2019 года

==================