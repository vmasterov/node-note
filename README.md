# **SkillNotes: Сервис личных заметок на Node. js**
## **Демо проекта:**
[https://icntdn.ru/](https://icntdn.ru/)
### **Пользователь с тестовыми заметками:**
* **логин** -- admin,
* **пароль** -- admin.

## **Загрузка и настройка проекта:**
1. Клонировать репозиторий по ssh: git clone git@github.com:vmasterov/node-note.git.
2. Установить необходимые зависимости: npm install.
3. Переименовать файл .env-sample в .env.
4. Собрать клиентскую часть приложения: npm run build.
5. Собрать серверную часть приложения: npm start.
6. Перейти по адресу http://localhost:3000/.

## **Npm скрипты:**
### **production:**
* **build** -- собирает клиентскую часть приложения,
* **start** -- собирает серверную часть приложения.

### **development:**
* **dev:front** -- собирает клиентскую часть приложения,
* **dev:back** -- собирает серверную часть приложения.

### **services:**
* **db:migrate** -- запускает миграцию, которая инициализирует БД,
* **db:rollback** -- откатывает последнюю миграцию,
* **prettify** -- приводит файл к единому стилю, принятому на проекте,
* **prettify:all** -- приводит все файлы приложения к единому стилю, принятому на проекте,
* **lint** -- проверяет файл на соответствие правилам, принятым на проекте,
* **lint:all** -- проверяет все файлы приложения на соответствие правилам, принятым на проекте.

## **В проекте реализован следующий функционал:**
* регистрация и аутентификация пользователя,
* создание и редактирование заметок,
* поиск заметок по датам,
* переход в архив,
* архивация, восстановление и удаление архивированных заметок,
* создание тестовой заметки для новых пользователей,
* аутентификация через github,
* скачивание заметки в формате PDF,
* поиск записей по тексту в заголовке,
* подсветка найденного фрагмента в заголовке.
