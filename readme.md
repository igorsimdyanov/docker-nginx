Сборка образа
```
docker build -t igorsimdyanov/nginx .
```
Запуск
```
docker run --name nginx_share -p 8080:80 -v "$(pwd)"/:/usr/share/nginx/html/ igorsimdyanov/nginx
```
