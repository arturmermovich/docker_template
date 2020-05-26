docker run -p 8888:8888 jupyter/scipy-notebook:17aba6048f44
docker exec -it d95eec0d26f8 bash - вход в терминал
docker cp appstore_games.csv d95eec0d26f8:/home/jovyan/appstore_games.csv - копирование файлов в контейнер
docker run -v /Users/artur/Documents/ds/docker_template:/home/jovyan/ -p 8888:8888 jupyter/scipy-notebook:17aba6048f44 

docker build .
docker build -t ds_template .
docker run -v /Users/artur/Documents/ds/docker_template:/home/jovyan/ -p 8888:8888 ds_template

. - текущая директория, в которой ты находишься

docker-compose up - поднять файл "docker-compose"
docker-compose down - убрать файл "docker-compose"
docker-compose build --build - забилдить и поднять настройки докеркомпоз


pwd - где находимся
ls - какие объекты есть в данной директории
clear - очистить окно от команд
quit() - выйти
. - текущая директория, в которой ты находишься
cd <name_folder> - войти в папку
cd .. - перейти в папку наверх"
