# django-vue-minimal
minimal boilerplate with django and vue cli

# installation
```bash
 pip install django
 cd frontend
 yarn install
```

# running

```sh
 python manage.py runserver
```
and in another tab (`ctrl+shift+t`) run vue-cli-service watch using
  
```sh
 cd frontend
 yarn watch
```

this will watch and build as you write frontend code in `/frontend` . you have to reload the page to see changes coming.

# django files I edited
1. in django-vue/settings.py , STATICFILES_DIRS and TEMPLATES['DIRS']
2. django-vue/urls.py

so you have to edit only these files to make your django app compatible with vue cli app.

# vue files i edited

1. frontend/vue.config.js [added]
