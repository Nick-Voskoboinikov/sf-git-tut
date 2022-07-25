[<< cодержание](../readme.md)

[< О системе Git](./about_git.md)

---

## Предварительная подготовка к работе с Git

1. Задать логин авторизации:
> ```bash=
> git config --global user.name "имя"
> ```

2. Задать адрес электронной почты:
> ```bash=
> git config --global user.email "адрес@лектроной.почты"
> ```
3. Задать тип завершения строк:
- В случае ОС Unix/Mac:
> ```bash=
> git config --global core.autocrlf input
> git config --global core.safecrlf warn
> ```
   - В случае ОС Windows:
> ```bash=
> git config --global core.autocrlf input
> git config --global core.safecrlf warn
> ```
4. Задать отображение в __Unicode__:
> ```bash=
> git config --global core.quotepath off
> ```

---

[Дальше к теме "Инициализация репозитория" >](./init.md)