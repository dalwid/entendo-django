## Requisitos

* Python 3 ou superior - Conferir a versão: python --version
* Django 5 ou superior - Conferir a versão: django-admin --version
* Mysql 8 ou superior  - Conferir a versão mysql --version

## Como Rodar o projeto baixado
Alterar no arquivo "settings.py" as credencias do bande de dados
´´´
'ENGINE': 'django.db.backends.mysql',
    'NAME': 'nome-do-banco-de-dados',
    'USER': 'usuario-do-banco',
    'PASSWORD': 'senha-do-usuario-do-banco',
    'HOST': 'localhost',
    'PORT': '3306'
´´´ 

Executar as migrations para criar as tabelas.
´´´
python manage.py migrate
´´´

Rodar o projeto
´´´
python manage.py runserver
´´´

Acessar a página padrão criada com Django.
´´´
http://127.0.0.1:8000
´´´
Criar super usuário
´´´
python manage.py createsuperuser
´´´

´´´
Username (leave blank to use 'avrah'): admin
Email address: davidtfp@gmail.com
Password: 123456
Password (again): 123456
´´´

Acessar o sistema administrativo padrão do Django.
´´´
http://127.0.0.1:8000/admin

Usuário: admin<br>
Senha: 123456A#

## Sequencia para criar o projeto
Instalar o Django.
´´´
pip install Django
´´´

´´´
django-admin --version
´´´

Criar o projeto com Django.

Rodar o projeto
´´´
python manage.py runserver
´´´

Acessar a página padrão criada com Django.
´´´
http://127.0.0.1:8000
´´´

´´´
pip install mysqlclient 
´´´

Cria o banco de dados do projeto
´´´
CREATE DATABASE admin CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
´´´

Alterar no arquivo "settings.py" as credencias do bande de dados
´´´
'ENGINE': 'django.db.backends.mysql',
    'NAME': 'nome-do-banco-de-dados',
    'USER': 'usuario-do-banco',
    'PASSWORD': 'senha-do-usuario-do-banco',
    'HOST': 'localhost',
    'PORT': '3306'
´´´ 

Executar as migrations para criar as tabelas.
´´´
python manage.py migrate
´´´

Criar super usuário
´´´
python manage.py createsuperuser
´´´
´´´
Username (leave blank to use 'avrah'): admin
Email address: davidtfp@gmail.com
Password: 123456
Password (again): 123456
´´´

Acessar o sistema administrativo padrão do Django.
´´´
http://127.0.0.1:8000/admin
´´´

## Como usar  o GitHub

Inicializar um novo reposit´rorio GIT.
´´´
git init
´´´

´´´
´´´