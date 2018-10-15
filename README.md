# django-haystack、
sudo apt-get update
sudo apt-get install python-django
查看：
django-admin --version


Django的基本使用
第一步：
创建一个叫做myjob的新项目
django-admin startproject myjob
创建数据库：
python3 manage.py migrate
创建管理员用户：
python3 manage.py createsuperuser
启动Django服务：
python3 manage.py runserver 0.0.0.0:8000
