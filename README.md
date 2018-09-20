# gogs-docker-compose

ship gogs with docker compose.

Notice: replace `your_mysql_root_password` with whatever you want.

## usage

* copy `docker-compose.yml` to your server.
* run `docker-compose up`, pay attention to the logs.
* visit the website on browser, the website url may be `http://server_ip:10080`.
* setup mysql host with `mysql:3306`.
* setup other params properly.
* install and finish.
* press `Ctrl+C` to stop docker, and run `docker-compose up -d` to run in background.

For more infomation, please visit [https://gogs.io/](https://gogs.io/).
