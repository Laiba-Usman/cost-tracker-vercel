# Deploy on Vercel
1. Push this folder to a GitHub repo (app.py must be in the repo root).
2. vercel.com -> Add New -> Project -> import the repo.
3. Environment Variables: SECRET_KEY (long random), COOKIE_SECURE=1, TRUST_PROXY=1, DEMO_USER, DEMO_PASSWORD (8+ chars).
4. Deploy, then open /healthz and log in with the demo account.
Note: Vercel storage is temporary (/tmp). Data resets on a cold start; the demo account is re-created automatically.
