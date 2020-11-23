# blagotvoritelnyifond
Благотворительный фонд
        Install Dependencies 
        Set Database (Make Sure you are in directory same as manage.py)
''''pip install -r requirements.txt
        Create DB in mysql 5.6 Command line Client(From Sanjar) 
''''show databases
''''create database sanjar character set utf8 collate utf8_unicode_ci;
        Создаем пользователя
''''CREATE USER 'user'@'localhost' IDENTIFIED BY 'password';
        Предоставляем полный доступ
''''GRANT ALL PRIVILEGES ON * . * TO 'user'@'localhost';

''''python manage.py createsuperuser

''''python manage.py makemigrations

''''python manage.py migrate
''''python manage.py runserver
        Установка телефоных номеров
''''pip install django-phonenumber-field[phonenumbers]
''''pip install django-phonenumber-field[phonenumberslite]


#### That's it! Happy Coding!
```
