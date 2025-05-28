# Flask CI/CD App 🚀

Простое Flask-приложение с настроенным CI/CD пайплайном:  
Docker + GitHub Actions + автосборка и деплой на Docker Hub.

## 🔧 Стек технологий

- [Python 3.10](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Docker](https://www.docker.com/)
- [GitHub Actions](https://github.com/features/actions)

## 📦 Установка и запуск

### 1. Локальный запуск с Docker Compose

```bash
git clone git@github.com:your-username/flask-ci-cd-app.git
cd flask-ci-cd-app
docker-compose up --build

localhost:5000
