# First Claude Code Prompt

Copy and paste the prompt below into Claude Code as your very first message in the project. It briefs the new Claude on context, sets the working style, and lays out the immediate task list.

---

## How to use this

1. Open Terminal in your `101-club` project folder
2. Type `claude` and hit enter
3. When the prompt loads, paste the message below in full
4. Hit enter — Claude Code will read the context files and confirm it's ready

---

## The prompt to paste

```
Hi Claude. I'm picking up a project we've been building together — The 101% Club, a private community for ambitious UK founders.

Before we start, please:

1. Read CLAUDE.md in full — it has the complete project context (business, brand, pricing, growth plan, tech stack)
2. Skim README.md to understand the folder structure
3. Open index.html and take a look at the current state of the landing page

Once you've done that, confirm you've got context and we'll work through the immediate task list below.

## How I'd like us to work together

- Direct and concise. Skip the preamble, just do the thing.
- Show me the change before you make it on anything substantial. For small edits (typos, formatting, single-line tweaks), just do it.
- When you suggest something, give me your honest opinion — not a list of options. If you think A is better than B, tell me.
- Run commands yourself when it's faster than walking me through. If you need my input (login, payment, domain DNS), pause and explain what you need.
- Test as you go. Don't write 200 lines of code and hope it works — preview the site after each meaningful change.

## Immediate task list (in priority order)

1. **Wire up Formspree properly.** I'll create a Formspree account and paste my form ID into the chat. You update index.html.

2. **Set up the GitHub repo and Vercel deployment.** Walk me through:
   - Creating the GitHub repo (called `101-club-site`)
   - Pushing this folder to it
   - Connecting Vercel to auto-deploy
   - Connecting my Namecheap domain (I'll tell you which one)

3. **Add Open Graph meta tags and favicon setup** to index.html so the link previews properly on LinkedIn, WhatsApp, and email.

4. **Add a simple analytics script** — recommend either Plausible or Fathom (privacy-friendly, lightweight). I want to see visits, conversions, and traffic sources without bloating the page.

5. **Sanity check the live site on mobile** — once it's deployed, walk me through what to test.

After that, we'll move onto:
- Applicant email sequence (welcome → review → call invite → accept/decline)
- Privacy policy, terms, and the refund guarantee terms
- Setting up Circle.so or Skool for the actual community space
- Stripe + Memberful for membership billing

Don't tackle any of that yet — let's get the foundations live first.

Ready when you are.
```

---

## Why this prompt works

A few deliberate choices worth knowing:

**It tells Claude to read the context files first.** Without this, Claude Code can answer questions, but won't have the strategic and brand context — and you'd spend the first 10 minutes re-explaining the business.

**It sets the working style up front.** Direct, concise, no preamble. This saves you from getting verbose responses to simple questions for the rest of the project.

**It gives a clear priority order.** Claude Code is excellent at multi-step work, but only if it knows what's first, second, third. The numbered list keeps it focused.

**It defers the bigger workstreams.** "Don't tackle that yet" prevents Claude Code from running ahead and starting the email sequence when you just want the site live.

## What happens after

Once the foundations are live (steps 1–5 done), open a new Claude Code session for each major workstream. Good chunks to break into:

- **Session 1:** Site live + analytics (steps 1–5 above)
- **Session 2:** Email sequences for applicants
- **Session 3:** Legal docs (privacy, terms, refund guarantee)
- **Session 4:** Circle.so / Skool community setup
- **Session 5:** Stripe + Memberful billing integration
- **Session 6:** LinkedIn content batch — first 30 posts
- **Session 7+:** Custom app build (months 9–12 — much bigger session)

Each session, Claude Code re-reads `CLAUDE.md` automatically. As the project evolves, update `CLAUDE.md` so future sessions start with current context.

## One last tip

When you finish a session and have made decisions worth remembering (e.g., "we went with Circle over Skool", "the founding member rate is locked at £79"), ask Claude Code at the end of the session:

> "Update CLAUDE.md with anything we decided this session that future sessions need to know."

This keeps your context file alive instead of going stale. It's the single biggest difference between Claude Code feeling like a fresh hire every session vs. feeling like a teammate who's been with you the whole way.
