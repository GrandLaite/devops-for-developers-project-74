# Docker Compose Practice

![CI](https://github.com/GrandLaite/devops-for-developers-project-74/actions/workflows/push.yml/badge.svg)

JS-блог на базе Fastify, упакованный в Docker с поддержкой CI/CD и PostgreSQL.

---

## Требования

| Зависимость    | Версия   |
|----------------|----------|
| Docker         | >= 20.10 |
| Docker Compose | >= 1.27  |

---

## Запуск

**Режим разработки**

```bash
docker-compose up
```

После запуска приложение доступно по адресу `https://localhost`.

**Тесты**

```bash
make test
```

**Сборка production-образа**

```bash
docker-compose -f docker-compose.yml build app
```

---

## Docker Hub

```
grandlaite/devops-for-developers-project-74
```

[→ Открыть на Docker Hub](https://hub.docker.com/r/grandlaite/devops-for-developers-project-74)
