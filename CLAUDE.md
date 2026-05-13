# 101% Club — Project Context

*This file gives Claude Code (or any future collaborator) the full context of the business so they can pick up where we left off without re-explaining everything.*

---

## The business

**Name:** The 101% Club
**Tagline:** A private club for the 1% extra that compounds.
**Category:** Digital-first, referral-driven private community for ambitious UK founders.

**Inspiration:** Built in the gap between BNI (rigid referral network, dated, for tradespeople) and Game Changers (premium mastermind, London-only, small). The 101% Club takes BNI's referral engine, Game Changers' community quality, and makes it digital-first, nationally accessible, and mid-market priced.

## Target member

- UK-based founders, agency owners, service businesses, ambitious SMBs
- Mixed turnover: ambitious solo founders (£50k–£500k) and established SMBs (£500k–£2m)
- Tier-matched to their stage

## Membership structure

### Founding Member — £79/month or £790/year *(first 100 only, price locked for life)*
Same access as Standard. Created scarcity and rewards early believers.

### Standard — £129/month or £1,290/year
- Full app access (referral engine, directory, asks board, wins feed)
- Monthly virtual mastermind (small group, facilitated)
- Weekly accountability circles (pods of 4)
- Monthly virtual masterclass with guest experts
- Quarterly referral roundtables
- Private community space
- Member-only event ticket pricing

### Premium / Inner Circle — £400/month or £4,000/year *(launches month 9–12 once 100+ Standard members are in)*
- Smaller, vetted masterminds (members £500k+ turnover)
- 1:1 introductions facilitated personally
- Quarterly in-person Inner Circle dinners
- Profile elevation: podcast features, speaking slots
- 4× coaching credits per year
- Private WhatsApp with the founder
- Free or heavily discounted flagship event ticket

## The promise

**One-client guarantee:** If you don't win at least one new client through the club in your first year, full refund. No major competitor offers this — strong differentiator.

## The rhythm

- **Weekly** — Accountability pods (groups of 4, 30 min)
- **Monthly** — Mastermind + masterclass
- **Quarterly** — Referral roundtables + in-person meetup (once 50+ members)
- **Annually** — Flagship event (year 1 target: ~150–300 attendees)

## Tech stack (current and planned)

**Now (off-the-shelf MVP):**
- Membership platform: Circle.so or Skool (to be decided)
- Payments: Stripe + Memberful or Outseta
- Calendar: Calendly
- Newsletter: Beehiiv
- Video: Zoom
- CRM: HubSpot Free or Pipedrive
- Website: standalone HTML on Vercel
- Form handler: Formspree
- Domain: registered on Namecheap

**Later (custom app, month 9–12):**
- Smart referral matching engine with ICP-tagged member profiles
- One-tap warm intro flow
- Referral value tracker (£ generated per member)
- Live "asks" board with push notifications
- One-to-one booking
- Wins feed

## Business model & growth path

**Target:** £1m ARR by month 18, 65–70% net margin.

**Member growth path:**

| Month | Founding @ £79 | Standard @ £129 | Premium @ £400 | ARR |
|---|---|---|---|---|
| 3 | 30 | 0 | 0 | £29k |
| 6 | 100 | 30 | 0 | £141k |
| 9 | 100 | 100 | 0 | £250k |
| 12 | 100 | 200 | 20 | £499k |
| 18 | 100 | 350 | 50 | £876k |
| 24 | 100 | 450 | 80 | £1.18m |

Plus event revenue: £150k–£200k by year 2.

## Growth levers (priority order)

1. **Annual billing as default** — push £790/£1,290/£4,000 upfront
2. **Member-as-affiliate** — refer a new member, get £200 credit or a free month
3. **Premium tier upsell** at month 12
4. **Events as pre-sold profit centres** — never book a venue until tickets are sold
5. **Founder LinkedIn build-in-public** — single highest-ROI activity, daily posting

## Sales

**Hire:** Commission-only full-cycle sales rep, already onboarded.
**Comp:** 15% MRR monthly, 25% annual contracts upfront, 30% Premium, £100 bonus per founding member close, 10% on event tickets.
**Targets:** 15 new members/month by month 3.
**Channels:** LinkedIn outbound + cold email (digital-first only at this stage).
**Reporting:** Daily CRM updates + weekly pipeline review.

## Brand & site

**Visual direction:** Refined editorial minimalism. Charcoal background (#1a1a1a), off-white text (#f5f3ee). Magazine-style layout with alternating dark/light sections.

**Typography:**
- Display: Fraunces (serif, italic variants in headlines for character)
- Body: Geist (sans-serif)
- Labels: Geist Mono (monospaced)

**Tone:** Direct, ambitious, grown-up. Not bro-y, not corporate, not wellness-heavy. Think *Monocle for entrepreneurs*.

**Brand voice rules:**
- Sell outcomes (clients, peers, access), not feelings (transformation, mindset)
- Confident without being arrogant
- Plain English, no jargon
- Italics for emotional accents in headlines
- The "%" in 101% is the strongest visual asset

**Website:** Single-page landing site, `index.html`, deployed on Vercel from a GitHub repo, custom domain via Namecheap.

## Things already built

- ✅ Market positioning and competitor analysis
- ✅ Membership structure and pricing
- ✅ Sales rep responsibilities document
- ✅ Landing page (single HTML file, charcoal/off-white, application form, Formspree-wired)
- ✅ Founding member offer locked in

## Things to build next

- [ ] Configure Formspree form ID in the HTML
- [ ] Deploy to Vercel and connect Namecheap domain
- [ ] Set up Google Workspace email (hello@, apply@)
- [ ] Open Graph meta tags + favicon
- [ ] Privacy policy, terms, member agreement, refund guarantee terms (legal essentials)
- [ ] Set up Circle.so or Skool community space
- [ ] Configure Stripe + Memberful/Outseta for billing
- [ ] Applicant email sequence (welcome, review, call invite, accept, decline)
- [ ] Sales playbook v1 (ICP, discovery questions, objection responses, closing script)
- [ ] CRM setup (HubSpot or Pipedrive)
- [ ] Mastermind facilitation guide
- [ ] First 30 LinkedIn posts for build-in-public launch
- [ ] Newsletter setup on Beehiiv — "The 101% Letter"
- [ ] Loom-recorded sales pitch
- [ ] One-pager PDF for DM/email distribution

## Founder's commitments

- Daily LinkedIn build-in-public content
- Personal outreach to top 50 contacts for founding members
- Weekly pipeline review with sales rep
- 1:1 facilitation of early masterminds (until contractor facilitators hired)

## Constraints

- **Lean ops** — no full-time hires until month 9; founder + commission sales rep + contractors only
- **Margin discipline** — target 70%+ net margin
- **No paid marketing in year one** — content engine + outbound only
- **Digital-first** — no venues, no events until 50+ paying members

---

*Last updated by the founder during initial setup. Edit this file as the business evolves.*
