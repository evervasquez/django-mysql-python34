# django-mysql-python34
instalar mysql and django with django/python34

1. instalar [PyMySQL](https://github.com/PyMySQL/PyMySQL/)
```js
  pip install PyMySQL
```
2. ir a *{project}/settings.py* y colocar antes de las configuraciones `DATABASE`

```py
  import pymysql
  pymysql.install_as_MySQLdb()
```
