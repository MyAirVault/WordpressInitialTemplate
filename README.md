# WordPress Dev Environment

Docker-based WordPress development setup with editable files.

## Quick Start

```bash
docker compose up -d
```

Visit http://localhost:8080

## Structure

- `.wordpress/` - WordPress files (edit themes/plugins here)
- `.mysql/` - Database persistence

## Database

| Field    | Value        |
|----------|--------------|
| Host     | mysql:3306   |
| Database | wordpress    |
| User     | wpuser       |
| Password | wppassword   |

## Commands

```bash
docker compose up -d     # Start
docker compose down      # Stop
docker compose logs -f   # View logs
```
