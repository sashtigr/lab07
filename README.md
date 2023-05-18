# Лабораторная работа №7

### Цель - изучене систем автоматизации развёртывания и управления приложениями на примере Docker

Убедимся что наша система обновлена и установим **docker**: 
```
$ sudo pacman -Syu && sudo pacman -S docker
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
