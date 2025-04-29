# PLAN34 – Project Environment Planning

This document details the technical and collaborative environment used for the Reservify project. It includes development tools, server requirements, and maintenance considerations to ensure smooth delivery and continuity.

---

## 1. Development and Collaboration Tools

| Tool               | Used By               |
|--------------------|------------------------|
| GitHub             | All developers         |
| Visual Studio Code | Frontend/Backend devs  |
| Postman            | API testers            |
| Slack / WhatsApp   | Team communication     |
| Google Docs        | Shared documentation   |

---

## 2. Setup and Maintenance Needs

| Setup Need               | Documentation Location                 |
|--------------------------|-----------------------------------------|
| Frontend Dev Environment | `frontend/README.md > Setup`           |
| Backend Dev Environment  | `backend/README.md > Setup`            |
| Testing Environment      | `docs/testing-setup.md`                |
| Deployment Server Config | `deployment/server-config.md`          |
| GitHub Actions (CI/CD)   | `.github/workflows/deploy.yml`         |

---

## 3. Security and Access

- GitHub repo is public, with team-specific write access.
- Only maintainers can modify workflow or server config files.
- Password management and API keys stored via environment variables.

---

## 4. Summary

PLAN34 ensures that the infrastructure, tools, and collaboration channels are well-defined and maintained to support the full software development lifecycle of Reservify.
