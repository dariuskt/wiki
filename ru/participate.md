# OpenIPC Wiki
[Оглавление](../index.md)

Хочу помочь! Что надо делать?
-----------------------------

Мы не откажемся от любой, даже самой малой помощи.
Проекту нужны как те, кто читает схемы, умеет отреверсить закрытый драйвер,
так и те, кто сможет увидеть и поправить опечатку, написать инструкцию,
нарисовать красивую картинку или может быть даже сложить красивую песню :)

### Я сделал поправки в код. Как его вам прислать?

Для работы с кодом мы используем систему управления версиями [Git][gitdoc]
и репозитории, расположенные на сервисе GitHub.

Если у вас есть аккаунт на GitHub, то все просто: сделайте копию нашего
кода в своем аккаунте (fork).

![GitHub Fork](/images/gh-fork.png)

Cделайте правки в своей копии, после чего отправьте запрос на включение 
ваших изменений в нашу ветку (pull request)

![GitHub Contribute](/images/gh-contribute.png)

Если вы по какой-то причине не пользуетесь GitHub, вы всё-равно можете
прислать нам свои изменения в код. Для этого сделайте локальную копию
репозитория соответствующего проекта.
```
git clone git@github.com:OpenIPC/firmware.git
```
Перенесите в него сделанные вами изменения. Запишите сделанные изменения в
вашу локальную копию репозитория. После чего создайте патч-файл и пришлите
его нам на адрес <dev@openipc.org>.
```
git format-patch master
```

[gitdoc]: https://git-scm.com/book/ru/v2