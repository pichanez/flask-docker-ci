# 📦 Flask Docker CI Project

## 🚀 Цель
Показать базовые навыки CI/CD с помощью GitHub Actions и Docker. Приложение запускается через Flask.

## ⚙️ Стек
- Python / Flask
- Docker
- GitHub Actions

## 🔧 Установка и запуск
```bash
git clone https://github.com/pichanez/flask-docker-ci.git
cd flask-docker-ci
docker build -t flask-docker-ci .
docker run -p 3000:3000 flask-docker-ci
```

## 🔁 CI/CD
Пайплайн запускается при каждом `push` в репозиторий. Он собирает Docker-образ и проверяет сборку.

## 🧠 Чему научился
- Писать Dockerfile
- Работать с GitHub Actions
- Деплоить Flask в Docker

