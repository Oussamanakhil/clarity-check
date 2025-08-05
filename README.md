# clarity-check
Grammarly for landing pages — but savage. Clarity Check is the first AI-powered clarity audit tool for DTC founders. Built for Shopify. Built to roast.

# 🧠 Clarity Check – The Final Boss of Your Funnel

> “Grammarly for Landing Pages. But savage.”

Clarity Check is the world’s first clarity audit tool built for **DTC founders**, not UX consultants. Upload your Shopify landing page → get a brutally honest roast in seconds. No fluff. No slides. Just results.

---

## 🚀 Why It Matters

💰 Your ad worked.  
🧊 Your landing didn’t.  
🎯 Clarity Check fixes that.

We roast your landing page’s clarity across:
- 🤯 Headline confusion
- 😵 Visual-copy mismatch
- 😴 CTA invisibility
- 📱 Mobile disaster
- 💀 Bounce triggers above-the-fold

---

## ⚙️ Tech Stack

| Layer | Stack |
|-------|-------|
| Edge | Vercel Edge Functions / Cloudflare Workers |
| Frontend | Next.js + Tailwind CSS |
| Backend | FastAPI (Python) |
| AI | GPT-4 + ViT (Visual Transformer) |
| Storage | Supabase + optional S3 |
| Realtime | WebSockets / Supabase Live |
| Shopify | Embedded app, Flow triggers, Admin Blocks |
| Analytics | PostHog + Amplitude |

---

## 📦 Folder Structure

```bash
clarity-check/
├── frontend/      # UI with input form, roast results, roast card
├── backend/       # FastAPI with prompts, vision models, scorers
├── sdk/           # Optional Python SDK
├── supabase/      # DB schema and Supabase setup
├── scripts/       # Deployment scripts (edge deploy, test runs)
└── README.md
