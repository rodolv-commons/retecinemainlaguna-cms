# retecinemainlaguna-cms

# Rete Cinema in Laguna – CMS (Strapi)

This repository contains the Strapi-based headless CMS for the **Rete Cinema in Laguna** project.  
The frontend is developed with [SvelteKit](https://github.com/rodolv-commons/retecinemainlaguna).

## 🧱 Tech Stack

- **Strapi** – Open-source headless CMS (Node.js)
- **PostgreSQL** – Production database (SQLite can be used for development)
- **Docker** – Containerized development and production environments
- **SvelteKit** – Frontend connected to this CMS

## 📦 Getting Started

### Local Development

```bash
git clone https://github.com/rodolv-commons/retecinemainlaguna-cms.git
cd retecinemainlaguna-cms
npm install
npm run develop
```

> You can also use Docker (see below).

### With Docker

```bash
docker-compose up --build
```

(Work in progress: docker-compose configuration coming soon.)

## 🌍 API Endpoints

Once running, the CMS exposes:

- **REST API:** `http://localhost:1337/api`
- **Admin Panel:** `http://localhost:1337/admin`

## 🔗 Related Projects

- **Frontend repo (SvelteKit):** [github.com/rodolv-commons/retecinemainlaguna](https://github.com/rodolv-commons/retecinemainlaguna)
- **Strapi documentation:** https://docs.strapi.io

## 📁 Content Types (planned)

- 🎞️ Films and Screenings
- 🏛️ Venues and Locations
- 📅 Events and Festivals
- 📣 News and Announcements

## 🛠️ TODO

- [ ] Add `docker-compose.yml` configuration
- [ ] Define initial content types and collections
- [ ] Connect frontend to CMS API
- [ ] Set up production deployment (with NGINX reverse proxy)

---
