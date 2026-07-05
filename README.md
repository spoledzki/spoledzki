# Hi, I'm Szymon Olędzki 🦭

I build backend systems, data pipelines, and automation around problems where correctness, traceability, and maintainability matter.

Most of my work is around Python-based backend engineering, document/data processing, API design, and production-oriented project setup: tests, typing, Docker, CI, and clear operational boundaries.

## What I Work With

- Backend services with Python, FastAPI, Pydantic, SQLAlchemy, and Alembic
- Data-oriented systems using PostgreSQL, Redis, object storage, and graph modelling
- Developer workflows based on `uv`, Docker, GitHub Actions, Ruff, typing, and automated tests
- LLM-assisted workflows where models support automation, extraction, or normalization without replacing explicit business rules

## Stack

| Area | Tools |
| --- | --- |
| Backend | Python, FastAPI, Pydantic, SQLAlchemy, Alembic |
| Data | PostgreSQL, Redis, Neo4j, MinIO/S3-compatible storage |
| Quality | pytest, testcontainers, Ruff, mypy, pre-commit |
| DevOps | Docker, Docker Compose, GitHub Actions, GHCR |
| Workflow | `uv`, typed code, reproducible environments, documented processes |

## Side Projects

### [SpectralPass](https://github.com/spoledzki/spectralpass)

SpectralPass is a local deterministic password generator for Chromium-based browsers.

It helps generate strong, repeatable passwords without creating a cloud account or storing a password vault. The extension runs locally, uses a side-panel workflow, and stores only metadata needed to restore saved site settings.

Key ideas behind the project:

- local-first password generation
- no stored master secret or generated passwords
- deterministic results from user-controlled inputs
- Chromium Manifest V3 extension architecture
- transparent documented protocol
- Polish and English interface
- practical safety features such as expiry, idle lock, and domain mismatch protection

**Stack:** JavaScript, HTML, CSS, Manifest V3, Chromium Extension APIs.

## Private Work

Most of my professional work is private or internal-facing, mostly around backend systems, data pipelines, document processing, automation, and API design.

I keep public repositories focused on projects that can be shared safely, documented clearly, and reviewed without exposing private implementation details or domain-specific data.

## Engineering Values

- Prefer explicit, testable logic over clever hidden behavior
- Keep security and privacy assumptions visible
- Treat CI, migrations, logging, and dependency management as part of the product
- Separate prototypes from production-ready paths
- Design systems so their outputs can be explained, reproduced, and reviewed

## Currently Exploring

- Local-first tools and privacy-focused workflows
- Reliable automation for backend and data-heavy systems
- Browser extension UX beyond simple popups
- Evidence-first APIs and auditable processing pipelines
- Better developer experience for complex Python services

## Contact

The best place to follow my work is here on GitHub: [![GitHub](https://img.shields.io/badge/GitHub-spoledzki-181717?style=flat-square&logo=github)](https://github.com/spoledzki)
