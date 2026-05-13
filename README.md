# 101% Club

The website and operational docs for The 101% Club — a private, referral-driven community for ambitious UK founders.

## What's in this folder

| File | What it is |
|---|---|
| `index.html` | The landing page. Single standalone HTML file. Deploys to Vercel. |
| `CLAUDE.md` | Full project context — read this first if you're new to the project. Claude Code reads this automatically at the start of every session. |
| `strategy.md` | The strategic offering document. Pricing, growth plan, competitive analysis. |
| `sales-rep-responsibilities.docx` | Sales rep role outline. |
| `commission-agreement.docx` | Commission agreement template (draft). |
| `first-claude-code-prompt.md` | The first message to send to Claude Code when starting a new session. |

## Quick start

```bash
# Start Claude Code in this folder
claude

# Or preview the site locally first
npx serve .
# then open http://localhost:3000 in your browser
```

## Deployment

- Domain: registered on Namecheap
- Hosting: Vercel (auto-deploys from GitHub)
- Form handler: Formspree
- Email: applications email directly to the founder

## Stack

- HTML/CSS/JS (no framework yet — single static page)
- Fonts: Fraunces, Geist, Geist Mono (Google Fonts)
- Form: Formspree
- Future: Circle.so for community, Stripe + Memberful for billing, custom referral app (months 9–12)
