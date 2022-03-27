# sensei_postgresql_heroku

```
$ psql --host= --username= --password= --dbname=

```
||

create via Heroku CLI
```
$ heroku pg:psql postgresql-convex-name --app appname
```
execute script
```
heroku pg:psql --app appname<database.sql
``
omit heroku pg:psql if already in heroku cli
