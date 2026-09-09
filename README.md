# Railway Schedule Database

Full-stack database coursework project for managing **railway/public-transport schedules**, combining relational modelling, SQL, a PHP web interface, and Dockerized MySQL infrastructure.

## Highlights

- Entity/relationship modelling followed by relational implementation.
- MySQL schema with primary/foreign keys and integrity constraints.
- Service calendars and exceptions.
- Recursive SQL views for active service dates.
- Analytical views for stop/trip statistics and timing information.
- PHP/PDO application layer with prepared statements.
- Docker Compose development environment with MySQL and phpMyAdmin.

## Security cleanup for the portfolio copy

The original coursework configuration contained fixed development credentials. This copy replaces those values with environment variables and an `.env.example` template. **Do not use the example passwords in a real deployment.**

## Run locally

```bash
cp .env.example .env
# Edit the passwords in .env
docker compose up --build
```

Then open the PHP application on `http://localhost:8081` and phpMyAdmin on `http://localhost:8080`.

## Repository structure

```text
dump/      schema and seed CSV files
www/       PHP application
conf/      MySQL configuration
docs/      design notes
```

## Academic context

Database project, academic year **2024-2025**, completed by a **team of three students**. The work was delivered in two stages: conceptual/relational design and database/application implementation.

The original course starter repository included its own public-domain `LICENSE`; that file is preserved. The raw assignments, reports, feedback, and submission identifiers are excluded. See [NOTICE.md](NOTICE.md).
