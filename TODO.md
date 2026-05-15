# TODO

- [x] Repo scan: identify existing Phi-3 local FastAPI flow.
- [x] Add Grok service (backend/services/grokService.js) that calls xAI Grok Chat Completions.
- [x] Update /api/chat/chat controller to use Grok by default and fallback to Phi-3 if Grok fails.
- [ ] Configure environment variables (GROK_API, optional GROK_API_URL / GROK_MODEL).
- [ ] Install deps if needed and run backend to test endpoint.
- [ ] Verify chat response `source` is `grok` or `phi-3`.

