### Создание контейнера

<pre> docker build -t python-app .</pre>

### Запуск контейнера

<pre>docker run -it --rm --name python/app -v "$PWD"/app:/app python-app</pre>

### Вход в sh

<pre>docker exec -it python/app sh</pre>