# ansible_nginx_build

Вариант исполнения https://github.com/RaibeartRuadh/ansible_nginx
Но в текущем варианте я собираю nginx 1.19.3 из исходников
Чтобы проверить работу:
Выполните 
1. vagrant up
После запуска стенда авторизуйтесь и выполните команду
2. curl http://localhost:8080
чтобы увидеть страничку
Проверит версию nginx
3. nginx -v
