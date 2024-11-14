# Docker

# Инструкиця

1. Склонируйте репозиторий:

```bash
    git clone https://github.com/Gidralit/docker.git
```

2. Перейдите в директорию проекта: 

```bash
    cd .../docker
```

3. Ждя запуска окружения введите следующие команды в терминал:

3.1 Для запуска окружения разработки:
```bash
    cd dev
    Создайте файл .env на основе .env.example
    docker-compose up --build
```

3.2 Для запуска окружения продакшна:
```bash
    cd prod
    Создайте файл .env на основе .env.example
    docker-compose up --build
```