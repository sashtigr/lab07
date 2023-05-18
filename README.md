# Лабораторная работа №7

### Цель - изучене систем автоматизации развёртывания и управления приложениями на примере Docker

Установлю **docker**: 
```
$ sudo apt update && sudo apt install -y curl
$ curl -fsSL https://get.docker.com/ | sudo sh
```

Билд докера:
```
sudo docker build -t hello_world .
```
Запуск для проверки:
```
docker run hello_world
```
