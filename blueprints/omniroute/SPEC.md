# OmniRoute Dokploy Template

OmniRoute is a self-hosted AI gateway/proxy with an OpenAI-compatible `/v1` endpoint, dashboard, provider management, prompt compression, fallback routing, and multimodal APIs.

## Ports

- Dashboard/API: `20128`
- Public API base URL: `https://<domain>/v1`

## Important environment variables

This template auto-generates secure defaults for:

- `JWT_SECRET`
- `API_KEY_SECRET`
- `INITIAL_PASSWORD`
- `STORAGE_ENCRYPTION_KEY`

Keep the generated `INITIAL_PASSWORD`; it is the first dashboard login password.
