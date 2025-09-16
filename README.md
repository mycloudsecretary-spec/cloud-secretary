# Cloud Secretary — Unified (GitHub Pages + Replit)

Turnkey **AI Business Concierge** with a static **frontend** (GitHub Pages) and a **Flask backend** (Replit).

## Deploy
### GitHub Pages
- Upload `/frontend` contents to repo root.
- Settings → Pages → Deploy from branch (main / root).
### Replit Backend
- Import the repo, install: `pip install -r backend/requirements.txt`
- Set secrets: `CS_ALLOWED_ORIGINS`, `CS_TEST_MODE=1` (optional), `STRIPE_SECRET_KEY` (optional), `GHL_WEBHOOK_URL` or `ZAPIER_HOOK_URL` (optional)
- Run: `python backend/app.py`
### Wire Up
- Edit `frontend/assets/js/app.js`: set `BACKEND_BASE`, `CHECKOUT_URL`, `FEEDBACK_URL`.
