# Platform 🚀

Platform repo for Homebrain-ai. Handles workflow in dev repos and deploying their code!

Holds majority of logic for workflows used by other repos.

## Workflows

* `build-image.yml`
* `deploy.yml`
* `pr-template-check.yml`
* `run-ci.yml`
* `security.yml`

## Quick Start ⚡

Create and fill out `.env`, from `.env.template`.

* **dev** use `BACKEND_TAG=latest`
* **stable** pin a version like `BACKEND_TAG=v1.2.3`

### Docker compose

```bash
# From the `compose/` directory:
docker compose pull
docker compose up -d

# Check status
docker compose ps
docker compose logs -f backend
```

