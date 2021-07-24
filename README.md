# docker-php-nginx-template
template php-fpm with xdebug + nginx running on docker


src conteing a example app.

starts a nginx and a php-fmp servers based on oficial image.

## running:
cd docker
docker-compose up --build

nginx server will be acessible on localhost:8080

the path /src will bo monted on path /code on nginx and php-fpm 

## vscode

config template in vscode_config_template, copy to your .vscode folder