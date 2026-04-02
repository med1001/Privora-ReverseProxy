# Privora-ReverseProxy

nginx configuration and Docker image for routing **HTTPS / WSS** to the Privora backend and static frontend in production.

| Route | Target |
|-------|--------|
| `/` | Frontend (SPA) |
| `/api/` | FastAPI |
| `/ws` | WebSocket |

## Related repositories

- [**Privora**](https://github.com/med1001/Privora) — FastAPI backend  
- [**Privora-GUI**](https://github.com/med1001/Privora-GUI) — React client  
- [**Privora-Workspace**](https://github.com/med1001/Privora-Workspace) — meta repo (submodules + local `docker compose`; optional for production)

## License

See [LICENSE](./LICENSE) in this repository.
