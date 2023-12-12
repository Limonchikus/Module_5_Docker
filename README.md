# Module_5_Docker
## Практическая работа по модулю 5: Docker на Linux

### Описание
Этот проект — простое Python-приложение, выводящее приветственное сообщение и текущие дату и время. Оно развертывается в Docker-контейнере, обеспечивая легкость установки, настройки и запуска в любом окружении.

### Предварительные требования
Для работы с проектом необходимо установить Docker и Docker Compose. Ниже приведены инструкции по установке.

#### Установка Docker
1. Обновите список пакетов:
'sudo apt-get update'
2. Установите Docker:
sudo apt-get install docker-ce docker-ce-cli containerd.io

#### Установка Docker Compose
1. Загрузите текущую стабильную версию Docker Compose:
sudo curl -L "https://github.com/docker/compose/releases/download/v2.4.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

2. Примените исполняемые права к бинарному файлу:
sudo chmod +x /usr/local/bin/docker-compose

### Сборка и Запуск

#### Сборка Docker-образа
Выполните следующую команду в директории проекта для сборки Docker-образа:
docker build -t my-python-app .

#### Запуск приложения
Для запуска приложения выполните:
docker run my-python-app

#### Использование Docker Compose
Для запуска приложения с помощью Docker Compose используйте команду:
docker-compose up

### Автор
[Limonchikus]
