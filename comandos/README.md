Iniciar o projeto Django

```
python -m venv venv
. venv\Scripts\activate
pip install django
django-admin startproject project .
python manage.py startapp contact
```

Configurar o git

```
git config --global user.name 'O seu nome'
git config --global user.email 'o_seu_email@gmail.com'
git config --global init.defaultBranch main
# Configurar o .gitignore
git init
git add .
git commit -m 'Mensagem'
git remote add origin URL_DO_GIT
```

Migrar a base de dados do Django

```
python manage.py makemigrations
python manage.py migrate
```

Criar e modificar a senha de um super usuário Django
```

python manage.py createsuperuser
python manage.py changepassword USERNAME
```