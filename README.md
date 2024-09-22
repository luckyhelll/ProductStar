Клонируйте репозиторий или создайте файлы согласно структуре проекта.
Активируйте виртуальное окружение и установите зависимости.
Запустите приложение:

python app.py

Примеры запросов:
Создание пользователя (POST):

URL: http://localhost:5000/api/v1/users
Тело запроса: {"username": "Lucky"}

Получение всех пользователей (GET):

URL: http://localhost:5000/api/v1/users

Создание поста (POST):

URL: http://localhost:5000/api/v1/posts
Тело запроса: {"username": "Lucky", "content": "Hello, world!"}

Получение всех постов (GET):

URL: http://localhost:5000/api/v1/posts
mkdir blog_api
cd blog_api
