### **Описание**
В этом проекте вы можете создавать, обновлять, удалять и добавлять в сообщества ваши посты. Читать посты и подписываться на любимых авторов.

### **Как запустить проект**
##### Клонировать репозиторий и перейти в него в командной строке:

`git clone git@github.com:qtafy23/api_final_yatube.git`
`cd api_final_yatube`

##### Cоздать и активировать виртуальное окружение:

`python3 -m venv env`
`source env/bin/activate`

##### Установить зависимости из файла requirements.txt:

`python3 -m pip install --upgrade pip`
`pip install -r requirements.txt`

##### Выполнить миграции:

`python3 manage.py migrate`

##### Запустить проект:

`python3 manage.py runserver`

### Примеры
```
http://127.0.0.1:8000/api/v1/posts/
http://127.0.0.1:8000/api/v1/posts/{id}/
http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/
http://127.0.0.1:8000/api/v1/groups/
http://127.0.0.1:8000/api/v1/follow/
<<<<<<< HEAD
```
=======
```
>>>>>>> 1d77337 (Created Api_Yatube)
