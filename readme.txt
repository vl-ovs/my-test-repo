IN PROCESS!!!
1. На Гитхаб выложена структура/скелет проекта для создания среды под Zabbix сервер: БД, Веб-фронт-енд, сам сервер Zabbix.
2. В процессе поиска решения стал использовать docker-compose. В файле docker-compose.yml описал требуемые Zabbix сервисы: 
MySQL, web-frontend-nginx, zabbix
При старте docker-compose up -d поднимает сервер Zabbix, который доступен on Localhost:80
3. Репозиторий в Github синхронизировал с Travis-CI. Но конфиг .travis.yml до конца не доделал, чтобы была полностью рабочая цепочка 
github-> Travis-CI (with docker services) -> DockerHub. In process!
