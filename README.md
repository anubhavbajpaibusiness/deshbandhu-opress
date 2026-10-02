# Deshbandhu College Voicebox

Anonymous complaint & suggestion box for the Deshbandhu College Students'
Union (University of Delhi). Static frontend in `public/`, three serverless
API routes in `api/`, shared helpers in `lib/`, and data stored in Upstash
Redis.

**Deployable to Vercel in under 10 minutes. Shares the same Upstash instance
as the Aditi Mahavidyalaya Voicebox with zero key collisions.**

---

## Deploy in 5 steps

### 1. Push to GitHub
```bash
git init
git add .
git commit -m "dbc-voicebox"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main