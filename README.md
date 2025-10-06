# DevOps Todo API (FastAPI)

A minimal FastAPI service built for a complete DevOps workflow:
- Dockerized application  
- GitHub Actions CI (build → test → scan → push)  
- Image published to GitHub Container Registry (GHCR)

## Endpoint
`GET /health` → `{"status":"ok"}`

## Run locally
```bash
docker compose up --build
# open http://localhost:8000/health
