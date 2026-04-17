Backend local configuration:

- Put real secrets in `backend/.env` for local testing.
- Commit only `backend/.env.example`.
- Do not store API keys in the repo root `env` file.

Recommended workflow:

1. Copy `backend/.env.example` to `backend/.env`.
2. Fill in your real API keys in `backend/.env`.
3. Commit code and `backend/.env.example` only.
