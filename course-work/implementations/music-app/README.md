# Music App

**Факултетен номер:** 2401321008
**Студент:** Христо Попов

## Описание

Уеб приложение за управление на музикално съдържание — изпълнители, албуми и концерти. Изградено с Spring Boot, Thymeleaf и PostgreSQL. Поддържа JWT автентикация и REST API.

## Технологии

- Java 17, Spring Boot 3
- Spring Security + JWT
- Spring Data JPA / PostgreSQL
- Thymeleaf (Server-side rendering)
- Docker & Docker Compose

## Инсталация и стартиране

### С Docker (препоръчително)

Изисква се инсталиран [Docker Desktop](https://www.docker.com/products/docker-desktop/).

```bash
git clone https://github.com/hristo-m-popov/distributed-applications-se
cd distributed-applications-se/course-work/implementations/music-app
docker compose up --build
```

Приложението е достъпно на: http://localhost:8080

### Локално (без Docker)

Изисква се Java 17+ и PostgreSQL.

1. Стартирайте PostgreSQL база данни `music_app` с потребител `postgres` и парола `1234`.
2. Изпълнете:

```bash
cd distributed-applications-se/course-work/implementations/music-app/music-app
./mvnw spring-boot:run
```

Приложението е достъпно на: http://localhost:8080
