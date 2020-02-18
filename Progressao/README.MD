Anotações:
Instalar python:
http://www.zottesso.com.br/professor/disciplinas/TESI/


### No linux:
#### Ambiente virtual Django
> source /opt/virtualenv/django/bin/activate

#### Iniciando projeto
> django-admin startproject Progressao
> python manage.py migrate
> python manage.py makemigrations

#### Criar superusário
> python manage.py createsuperuser

#### Iniciar servidor
```
python manage.py runserver
ou
python manage.py runserver 8080 (ou qualquer outra porta)
```



#### Criando páginas
> python manage.py startapp paginas


#### Ordem de criação: 
```
url
view
template
```
#### Importar os arquivos da pasta static

```
{% load static %}
<link rel="stylesheet" href="{% static 'css/bootstrap.min.css' %}">
```