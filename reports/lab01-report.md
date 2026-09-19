# Отчёт по лабораторной работе №1
## Настройка локального окружения разработчика

**Студент:** Украсин Никита Андреевич
**Группа:** 23-ИСбо-1
**Дата:** 17.09.2026

---

## 1. Информация о системе

### 1.1. Версия ОС
```
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 22.04.5 LTS
Release:        22.04
Codename:       jammy
```

### 1.2. Версия ядра Linux
```
6.6.114.1-microsoft-standard-WSL2
```

## 2. Установленные инструменты

git version 2.34.1
Docker version 29.8.1, build 4a63305
Docker Compose version v5.5.1
GNU Make 4.3
curl 7.81.0 (x86_64-pc-linux-gnu) libcurl/7.81.0 OpenSSL/3.0.2 zlib/1.2.11 brotli/1.0.9 zstd/1.4.8 libidn2/2.3.2 libpsl/0.21.0 (+libidn2/2.3.2) libssh/0.9.6/openssl/zlib nghttp2/1.43.0 librtmp/2.3 OpenLDAP/2.5.20
jq-1.6
Client Version: v1.37.0
Kustomize Version: v5.8.1
v3.22.0+g144ca65

## 3. Настройка Git

### 3.1. Конфигурация Git
```
user.name=Украсин Никита
user.email=nikita.ykrasin@gmail.com
init.defaultbranch=main
core.autocrlf=input
core.editor=nano
pull.rebase=true
fetch.prune=true
alias.st=status
alias.co=checkout
alias.br=branch
alias.ci=commit
alias.lg=log --graph --oneline --decorate --all
```

## 4. SSH-ключ

### 4.1. Проверка подключения к GitLab
```
Hi YkrasinNikita! You've successfully authenticated, but GitHub does not provide shell access.
```

### 4.2. Отпечаток ключа
```
256 SHA256:46xzSFbWw/johJ7keT6Xy3KJiD93BtljuIELVnmpXM0 nikita.ykrasin@gmail.com (ED25519)
```

## 5. Проверка Docker

### 5.1. Запуск hello-world
```
Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://hub.docker.com/

For more examples and ideas, visit:
 https://docs.docker.com/get-started/

```

## 6. Выводы

Были настроены ВМ и git, установлены требуемы инструменты и настроено подключение к GitHub.
Возникла проблема с GitLab, т.к. там требовалась регистрация через иностранную карту, зарегестрироваться не получилось.
При использивании git.kosgos.ru не получилось подключиться через SSH. 
Было принято решение подключиться и создать репозиторий на GitHub.

