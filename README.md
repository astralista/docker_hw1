### Задание 1 

#### Собираем Docker-образ:
```
docker build -t my-custom-nginx
```

#### Запускаем контейнер:

```
docker run -d -p 80:80 my-custom-nginx
```
