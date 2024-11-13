# Alembic Migrations Guide

This guide covers the setup and usage of Alembic for database migrations in this project.

## What is Alembic?

Alembic is a lightweight database migration tool for SQLAlchemy-based applications. It helps manage changes to the database schema over time, allowing for version control on migrations, similar to how Git handles source code changes.

Initial Setup
If this is your first time setting up Alembic in the project, follow these steps:

## Initialize Alembic:

```bash 
alembic init migrations
```

## Create migrations:

```bash 
alembic revision --autogenerate -m "comment"
```

## Run migrations:

```bash 
alembic upgrade heads
```

