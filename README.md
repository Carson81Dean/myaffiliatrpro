# MyAffiliatePro — Phase 1 (Vercel-ready)

## What this package contains
- Next.js frontend + serverless API routes (pages/api) for OpenAI integration and Stripe webhook placeholders.
- Tailwind CSS setup for quick styling.
- Firebase auth hooks placeholder.
- `.env.example` with required environment variables.

## How to deploy (one-click to Vercel)
1. Create a GitHub repository in your account.
2. Upload the contents of this repo (or push using git).
3. In Vercel: Import Project → select your GitHub repo → Deploy.
4. Set the following Environment Variables in Vercel (Settings → Environment Variables):
   - OPENAI_API_KEY
   - NEXT_PUBLIC_FIREBASE_API_KEY
   - NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN
   - FIREBASE_PROJECT_ID
   - STRIPE_SECRET_KEY
   - STRIPE_WEBHOOK_SECRET
5. Deploy. Your site will be available at `https://<project>.vercel.app`

## Local dev
- `npm install`
- `npm run dev`
- Open http://localhost:3000

## Notes
- The OpenAI and Stripe endpoints are placeholders. Add your API keys in Vercel before using the production features.
- This is an MVP scaffold: adjust prompts, pricing pages, and Stripe product IDs to match your business.
