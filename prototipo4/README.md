[Demo](https://psdtoweb.herokuapp.com)


### Setup:
```
pipenv install
```

### Dump data:
```
python manage.py dumpdata auth.user exemplo.card exemplo.slide > db.json
```

### Load data:
```
python manage.py loaddata db.json
```