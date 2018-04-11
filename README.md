# codebarsess

`heroku create`

git remote add heroku

heroku addons:create heroku-postgresql:hobby-dev

heroku config:get DATABASE_URL

heroku pg:psql

DATABASE=> SELECT current_database();

DATABASE=> SELECT * FROM pg_stat_activity

 psql postgres:///codebarsess
