Flask

sqlite3

bootstrap

jQuery

blog

Простой пример блога.

Слева на главной - панель с тегами. Нажав на тег, мы получаем статьи, имеющие данный тег в своем списке тегов.
Справа - контент. Шапка, футер - есть.

Получить права админа: site-name:5000/admin

login: admin -//- password: admin


(Становятся доступны новые кнопки и изменяется шапка сайта под нужды админа.)

site:5000


        /<int> - пост #int

        /new_post - новый пост
        /edit/<int> - редактирвание поста #int
        /delete/<int> - удаление поста #int

нижние три доступны только авторизованному пользователю

