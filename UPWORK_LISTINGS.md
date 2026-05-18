# Upwork Listings — Portfolio & Catalog (paste-ready)

Single reference for everything you upload to your Upwork profile.

**How to use:** Each section below has the exact title + description to paste into the matching Upwork field. Code blocks (```) are paste-ready as written.

**Live preview site:** [samples.oncallautomation.ai](https://samples.oncallautomation.ai) (or fall back to [oncall-studio-samples.netlify.app](https://oncall-studio-samples.netlify.app) before DNS propagates)

---

# PART 1 — Portfolio (8 pieces)

Upload each as a separate Portfolio entry. Workflow per piece:
1. Open the live URL in Chrome
2. Cmd+Shift+P → "screenshot full size"
3. Upload the PNG to Upwork as the Portfolio image
4. Paste the Title in the Portfolio title field
5. Paste the Description block in the "What I built" / project description field

---

## 01 · Halstead & Grove — Wall Street M&A law firm

**Live:** [samples.oncallautomation.ai/01-law-firm.html](https://samples.oncallautomation.ai/01-law-firm.html)

**Title:**
```
Wall Street M&A law firm site — Halstead & Grove, capital markets boutique
```

**Description:**
```
What I built: Editorial site for a Wall Street M&A boutique. Manhattan skyline hero, deal-tombstone transactions ($14.2B carve-out, $3.4B IPO, $2.8B LBO), Chambers Band 1 recognition row, 5-phase deal architecture diagram, four practice photo cards (M&A · Private Equity · Capital Markets · Restructuring), partner roster, NY/London/DC office grid.

Stack: React + Vite + Tailwind + Bespoke Serif (display) + Inter (body)
Timeline: 7–10 days end-to-end
Includes: Mobile-responsive · LocalBusiness schema · GA4 · Editorial CMS option · Engagement-letter intake form
```

---

## 02 · Rook & Well — Manhattan cosmetic + family dentistry

**Live:** [samples.oncallautomation.ai/02-dental-practice.html](https://samples.oncallautomation.ai/02-dental-practice.html)

**Title:**
```
Family + cosmetic dental practice — Rook & Well, Madison Avenue
```

**Description:**
```
What I built: Healthcare practice site modeled on the Michigan TMJ pattern. Split hero with smiling patient + 'Start Smiling Again!' headline, blue value-prop band (Smile Better / Live Better / Transform Your Life), Cosmetic Precision Approach™ intro section, 3-step process with line icons + pink STEP labels, blue assessment-tool band, Meet Dr. Rooks split section, contact form on blue-overlay photo, three patient testimonials with pink italic names, 4 service photo cards with purple bottom strips, alternating Cosmetic + Invisalign treatment sections with FAQ accordions, blue video band, black footer with Patient Stories gradient card.

Stack: React + Vite + Tailwind + Montserrat (display) + Open Sans (body)
Timeline: 7–10 days end-to-end
Includes: Mobile-responsive · LocalBusiness schema · GA4 · HIPAA-aware contact form · Insurance verifier component · Appointment request flow
```

---

## 02b · OnCall Agents — Multi-channel AI agent inbox *(product demo)*

**Live:** [samples.oncallautomation.ai/02-ai-agent-dashboard.html](https://samples.oncallautomation.ai/02-ai-agent-dashboard.html)

**Title:**
```
Multi-channel AI agent inbox — web/SMS/voice/WhatsApp/iMessage, GPT-4o lead scoring
```

**Description:**
```
What I built: Production-grade agent inbox UI. Inbox view across six channels (web · SMS · WhatsApp · voice on Vapi · iMessage · Messenger), live conversation thread with agent-drafted responses, GPT-4o lead scoring with explainable reasoning (visual ring + reasoning text), contact rail with CRM-linked metadata (insurance verified, channel source, referral keyword), quick-action queue (send pre-visit form, push to Salesforce, add to Mailchimp), Slack alert timeline. Same architecture I run in production at oncallchat.ai.

Stack: React + FastAPI + PostgreSQL + Redis + OpenAI (GPT-4o) + Twilio + Vapi
Timeline: 14–30 days
Includes: Auth · Multi-tenant data isolation · Webhook handlers · CRM sync (HubSpot/Salesforce/GHL/Pipedrive) · Slack alerts · Deployed (Railway/Vercel)
```

---

## 03 · Via dell'Orto — West Village Italian trattoria

**Live:** [samples.oncallautomation.ai/03-restaurant.html](https://samples.oncallautomation.ai/03-restaurant.html)

**Title:**
```
West Village Italian trattoria — Via dell'Orto, Awwwards-tier menu + Resy
```

**Description:**
```
What I built: Mooserhotel/Awwwards-tier West Village restaurant site. Full-bleed hero photography, three photo-card courses (Primi/Secondi/Dolci) with hand-rolled-at-4pm menu, kitchen photographer credit ('— 4:42pm, before service'), dim editorial press band with NYT/Eater/Infatuation quotes, Resy reservation flow with party-size chip picker, hours + visit grid. Erode + Cabinet Grotesk typography, terracotta + olive + gold palette — distinct from law firm and skincare.

Stack: React + Vite + Tailwind + Erode (display) + Cabinet Grotesk (body)
Timeline: 5–7 days end-to-end
Includes: Mobile-responsive · Restaurant + Menu schema · GA4 · Resy embed · Owner-editable menu CMS · Photo gallery
```

---

## 04 · NORTHFOLD & CO. — Heritage outdoor goods storefront

**Live:** [samples.oncallautomation.ai/04-ecommerce.html](https://samples.oncallautomation.ai/04-ecommerce.html)

**Title:**
```
Heritage outdoor goods storefront — NORTHFOLD & CO., multi-category retail
```

**Description:**
```
What I built: Heritage outdoor + home goods e-commerce site, multi-category. 12 products across jackets, packs, footwear, cookware, home & bedding, hand tools. Working cart with quantity controls, free-shipping threshold, tax + total math, and a slide-in cart drawer. Filter sidebar (category checks, color swatches, size, price range, rating filters) live-filters the product grid. Hero, trust strip (free shipping / 30-day returns / lifetime repairs / made in Maine), editorial 'field journal' story section, full footer with newsletter capture. Source Serif 4 (display) + Inter (UI) on a moss + cream palette.

Stack: React + Tailwind + Shopify Hydrogen OR Next.js Commerce + Stripe OR Shop Pay
Timeline: 10–18 days end-to-end
Includes: Cart + checkout · Product filtering · Search · Wishlist · Customer accounts · Order history · Reviews · Inventory sync · Email capture · SEO + product schema · Apple Pay + Shop Pay
```

---

## 05 · Lead Intake CRM *(product demo — in progress)*

**Live:** [samples.oncallautomation.ai/05-saas-landing.html](https://samples.oncallautomation.ai/05-saas-landing.html) *(placeholder — pending rebuild)*

**Title:**
```
Lead intake CRM — GPT-4o scoring, routing, multi-CRM sync, reply queue
```

**Description:**
```
What I built: Inbound lead system that scores every form submission 1–100 by GPT-4o with explainable reasoning, drafts an auto-reply that waits for one-click send, pings Slack on hot leads, and syncs the contact to HubSpot/Salesforce/GHL/Pipedrive — whichever CRM the client uses. Built around the lead-intake-system I run for my own agency.

Stack: React + FastAPI + PostgreSQL + GPT-4o + Twilio + (HubSpot / Salesforce / GHL / Pipedrive / Zoho APIs)
Timeline: 7–14 days
Includes: Custom form builder · Scoring model · Auto-reply drafts · Multi-CRM sync · Slack notifications · Weekly digest · Apollo enrichment optional
```

---

## 06 · Forge Method — Strength studio site

**Live:** [samples.oncallautomation.ai/06-fitness-studio.html](https://samples.oncallautomation.ai/06-fitness-studio.html)

**Title:**
```
Brutalist fitness studio site — small-group strength coaching, trial-week funnel
```

**Description:**
```
What I built: Brutalist editorial site for a small-group strength studio in Scarsdale. Iron + acid-green palette, ticker bar with live spot counts, no-mirror coaching ethos, six-athletes-per-session positioning. Trial-week conversion funnel for adults who outgrew big-box gyms. Mobile-first booking. Coach bios with credentials.

Stack: React + Tailwind + Cabinet Grotesk + Gambarino + Mindbody/Mariana booking API
Timeline: 7–14 days
Includes: Booking integration · Trial-week funnel · Coach pages · Schedule grid · Pricing tiers · Email capture · SEO + schema.org
```

---

## 08 · Voice Agent Analytics + Easy Mode *(product demo)*

**Live:** [samples.oncallautomation.ai/08-voice-agent-dashboard.html](https://samples.oncallautomation.ai/08-voice-agent-dashboard.html)

**Title:**
```
Voice AI dashboard with tap-to-talk demo — Vapi integration, onboarding wizard
```

**Description:**
```
What I built: Two-layer voice agent product designed on a low-floor / high-ceiling principle.

Easy view (default for first-time visitors): full-screen tap-to-talk circle button wired to a live Vapi WebRTC connection — buyers can actually speak to the agent in their browser. Three KPI tiles, status indicator, no clutter.

Pro view (one click away): full operator console with live call queue, transcript viewer with intent + sentiment tags, animated waveform, booking conversion funnel, custom greeting editor (Day / After-hours / Weekend tabs), and live hot-lead toasts.

Apple-style onboarding wizard (5 steps, one decision per screen): business name → agent name → voice picker with samples → phone number → summary card → 'Try a call now' that drops you into Easy view with a live demo running.

Day + Night theme swap.

Stack: React + FastAPI + Vapi web SDK + Twilio + PostgreSQL
Timeline: 10–14 days
Includes: Inbound number provisioning · Custom voice + greeting · Calendar booking · After-hours mode · CRM push · Recording archive · Hot-lead Slack alerts · 'Easy view' for non-technical staff
```

---

## 07 · LATERAL CO. — Independent music label e-commerce

**Live:** [samples.oncallautomation.ai/07-shopify-skincare.html](https://samples.oncallautomation.ai/07-shopify-skincare.html)

**Title:**
```
Independent music label e-commerce — LATERAL CO., EMPIRE-tier Shopify build
```

**Description:**
```
What I built: EMPIRE-tier independent label + merch Shopify store. Bold black/white minimalist aesthetic. Full-bleed artist hero with rotating featured release (slide indicators + nav arrows), huge 'SHOP' display header + filter pills (Trending/Bestsellers/Box Sets/Merch/Shop All), 5-column product grid with category badges (Vinyl/Snapback/Hoodie/Tee), 'NEWS' editorial section with feature article + 2 side cards, 'SOCIALS' image grid, 'Defining Independence' marquee with rotating logo, black footer with social icons + company/shop/legal columns. Inter Tight 900 display + Inter body.

Stack: Shopify Hydrogen + React + Inter Tight + Klaviyo
Timeline: 10–14 days
Includes: Mobile-responsive · Product schema · GA4 / GTM · Klaviyo lifecycle · Inventory sync · Discount engine · Stripe + Apple Pay + Shop Pay
```

---

# PART 2 — Project Catalog (10 listings)

Productized service listings. **Get all 10 live within 2 weeks.** Each gets pasted into Upwork → Profile → Project Catalog → Create New Project.

For each listing below:
- Paste the **Title** as the catalog listing title
- Use the **3 tiers** as the three Upwork tiers (T1 / T2 / T3)
- Paste the **Includes** as the bullet list for each tier
- Paste the **Who this is for** + **Why me** as the project description

---

## ① Custom website (existing — update tiers)

**Title:**
```
You will get a custom website that loads fast and converts visitors into clients
```

| Tier | Price | Timeline |
|---|---|---|
| T1 Starter | **$1,500** | 5 days |
| T2 Standard ★ | **$3,200** | 7 days |
| T3 Premium | **$5,800** | 10 days |

**T1 Starter includes:**
- 5-section single-page site (hero, services, about, testimonials, contact)
- Mobile-responsive · connected to your domain with SSL
- Contact form delivered to your email
- 1 round of revisions

**T2 Standard adds:**
- Up to 8 sections + interior pages (Services, About, Contact)
- SEO setup: meta tags, schema, sitemap, GA4, Search Console verified
- Custom photography integration + brand-aligned copy
- 2 rounds of revisions

**T3 Premium adds:**
- Custom CMS so you can edit copy/photos yourself
- Blog setup with first post written
- Stripe checkout if you sell anything
- 3 rounds of revisions

**Who this is for:** Service businesses (law, dental, accounting, fitness, restaurants, consulting) sick of their template Wix/Squarespace site.
**Why me:** I run my own production SaaS at oncallchat.ai. The architecture I ship to clients is the same code I run for paying customers.

---

## ② Shopify store (existing — raise pricing)

**Title:**
```
You will get a fully built Shopify store that looks hand-made
```

| Tier | Price | Timeline |
|---|---|---|
| T1 Launch | **$750** | 3 days |
| T2 Growth ★ | **$1,500** | 5 days |
| T3 Brand | **$2,800** | 8 days |

**T1 Launch includes:**
- Up to 10 products migrated/uploaded
- Custom theme based on your brand
- Mobile-responsive, fast-loading
- Stripe + Apple Pay + Shop Pay configured
- Email signup connected to Klaviyo or Mailchimp

**T2 Growth adds:**
- Up to 50 products
- Editorial product detail pages with image galleries
- Subscription + bundle builder (pause/skip/swap)
- Welcome email + abandoned-cart sequence written
- Custom collections

**T3 Brand adds:**
- Unlimited products
- Custom homepage sections (lookbook, ingredients, journal)
- Full Klaviyo lifecycle (welcome, abandon, post-purchase, win-back, VIP)
- Reviews integration (Judge.me or Yotpo)
- Custom checkout and thank-you page

**Who this is for:** DTC brands, specialty retailers, restaurants/services adding e-commerce.
**Why me:** Editorial Shopify builds with subscription mechanics — see portfolio (LATERAL CO.).

---

## ③ AI Agent (rename from "AI Chatbot")

**Title:**
```
You will get a custom AI agent that answers leads, books meetings, and texts customers 24/7
```

| Tier | Price | Timeline |
|---|---|---|
| T1 Web Agent | **$750** | 3 days |
| T2 Multi-Channel ★ | **$1,500** | 5 days |
| T3 Always-On | **$2,800** | 8 days |

**T1 Web Agent includes:**
- Custom AI agent on your website
- Trained on your services, prices, hours, FAQs
- Hands off to you when it doesn't know
- Simple lead capture form integration

**T2 Multi-Channel adds:**
- SMS via Twilio (so leads can text you)
- Calendar integration (Calendly, Google Cal, or your CRM)
- Conversation history dashboard
- Slack notifications when a hot lead comes in

**T3 Always-On adds:**
- Voice agent on your phone line (Vapi-powered)
- WhatsApp + Messenger integration
- Memory across conversations
- Custom escalation rules + after-hours coverage

**Who this is for:** Service businesses losing leads after-hours, solo operators who can't pick up every call, SaaS qualifying leads before sales talks to them.
**Why me:** I run oncallchat.ai — production multi-channel agent platform with real Stripe billing, voice, and 6 channels. The agent I build for you is the same architecture I sell to paying customers.

---

## ④ n8n workflow automation (NEW)

**Title:**
```
You will get an n8n workflow that connects your stack and kills the spreadsheet glue
```

| Tier | Price | Timeline |
|---|---|---|
| T1 Single Workflow | **$700** | 3 days |
| T2 Multi-Step ★ | **$1,500** | 5 days |
| T3 Ops Backbone | **$3,500** | 10 days |

**T1 Single Workflow:** 1 workflow up to 5 nodes · 2-3 tools connected · tested, documented, deployed.
**T2 Multi-Step adds:** Up to 3 connected workflows · conditional logic, retries, webhook + scheduled triggers · failure alerts.
**T3 Ops Backbone adds:** 5+ workflows mapped to your full ops stack · custom integrations · monitoring + replay · walkthrough video.

**Who this is for:** Agencies, consultants, RevOps teams running ops in spreadsheets. People hitting Zapier limits.
**Why me:** I run workflows at scale for my own SaaS. I know where Zapier breaks and when n8n is the right call.

---

## ⑤ Stripe billing for SaaS (NEW)

**Title:**
```
You will get production Stripe billing for your SaaS — multi-tier, portal, dunning, all of it
```

| Tier | Price | Timeline |
|---|---|---|
| T1 Single Tier | **$999** | 4 days |
| T2 Multi-Tier ★ | **$1,999** | 6 days |
| T3 SaaS Backend | **$3,499** | 10 days |

**T1 Single Tier:** One tier monthly/annual · Stripe Checkout · customer portal · webhook handlers · test + production setup.
**T2 Multi-Tier adds:** Up to 4 tiers · upgrades/downgrades with proration · trial management · dunning emails · entitlements wired into your app.
**T3 SaaS Backend adds:** Stripe Connect for marketplace/multi-tenant · custom invoices · usage-based metering · affiliate tracking · annual revenue recognition.

**Who this is for:** SaaS founders shipping their MVP. Existing apps replacing duct-taped Gumroad/Lemon Squeezy. Marketplace builders needing Connect.
**Why me:** I run a 4-tier subscription system on Stripe at oncallchat.ai. Built portal, dunning, webhooks, entitlements myself.

---

## ⑥ Lead intake automation (NEW)

**Title:**
```
You will get a lead intake system that scores, replies, and routes — so you stop losing leads
```

| Tier | Price | Timeline |
|---|---|---|
| T1 Form + Reply | **$1,200** | 4 days |
| T2 Form + CRM ★ | **$2,400** | 6 days |
| T3 Full Intake | **$4,500** | 10 days |

**T1 Form + Reply:** Custom form · AI scores leads 1–10 · auto-reply email in your voice · Slack notifications.
**T2 Form + CRM adds:** Pushes to your CRM (HubSpot/GHL/Pipedrive/Salesforce) · routing rules · SMS auto-reply via Twilio · custom fields · weekly digest.
**T3 Full Intake adds:** Multi-form support · lead enrichment (Clearbit/Apollo) · drip sequences for cold leads · calendar booking in auto-reply · admin pipeline dashboard.

**Who this is for:** Service businesses, agencies, consultants. Anyone losing leads to slow response.
**Why me:** I built lead-intake-system for my own agency — handles inbound, scores with GPT-4o, syncs to 5 CRMs in production.

---

## ⑦ Voice agent (NEW)

**Title:**
```
You will get a voice agent that answers your phone, qualifies callers, and books your calendar
```

| Tier | Price | Timeline |
|---|---|---|
| T1 Inbound Receptionist | **$1,800** | 5 days |
| T2 Booking Agent ★ | **$2,800** | 7 days |
| T3 Always-On Front Desk | **$4,500** | 10 days |

**T1 Inbound Receptionist:** Vapi/Twilio voice agent · answers in your business voice · captures caller info + reason · texts you a summary after every call.
**T2 Booking Agent adds:** Real-time calendar booking · qualifies leads before booking · hot-lead handoff · after-hours mode · voicemail transcription.
**T3 Always-On adds:** Multi-channel (voice + SMS + WhatsApp on same number) · memory across calls · custom escalation · CRM integration · trained on your full catalog.

**Who this is for:** Service businesses where the phone is the front door — dentists, law firms, real estate, salons, contractors.
**Why me:** I run a production voice agent on Vapi as part of oncallchat.ai. Voice is the hardest channel; I've already debugged it across 100+ calls.

---

## ⑧ RAG knowledge base / internal AI (NEW)

**Title:**
```
You will get a custom AI assistant trained on your docs, support tickets, and internal knowledge
```

| Tier | Price | Timeline |
|---|---|---|
| T1 Single Source | **$2,200** | 5 days |
| T2 Multi-Source ★ | **$4,000** | 8 days |
| T3 Internal Brain | **$7,500** | 14 days |

**T1 Single Source:** Trained on one source (PDF library, website, Notion, Drive) · web chat interface · citation links · hosted.
**T2 Multi-Source adds:** Up to 5 sources · daily auto-sync · custom branding + your domain · authentication · Slack integration.
**T3 Internal Brain adds:** Unlimited sources · real-time sync with version control · multi-channel (web + Slack + email) · permissions per team · analytics on knowledge gaps.

**Who this is for:** Companies with sprawling internal docs. Support teams answering the same 50 questions. Law firms with case archives.
**Why me:** RAG systems with Pinecone, pgvector, OpenAI/Anthropic embeddings — production-tested at oncallchat.ai.

---

## ⑨ Multi-tenant SaaS MVP (NEW)

**Title:**
```
You will get a launch-ready multi-tenant SaaS — login, billing, dashboard, deployed
```

| Tier | Price | Timeline |
|---|---|---|
| T1 Solo MVP | **$4,500** | 14 days |
| T2 Multi-Tenant ★ | **$7,500** | 21 days |
| T3 Production SaaS | **$12,000** | 30 days |

**T1 Solo MVP:** Auth (email + Google) · single-tenant DB · Stripe billing (1 tier) · dashboard scaffolding · deployed to Railway/Vercel.
**T2 Multi-Tenant adds:** Per-customer data isolation · multi-tier Stripe with portal · admin panel · audit logs · transactional emails.
**T3 Production SaaS adds:** SSO (Google Workspace, SAML) · webhooks for customer integrations · custom domains per tenant · advanced billing (annual, usage-based) · onboarding flows · 30 days post-launch support.

**Who this is for:** Founders with a validated idea but no engineering team. Existing apps replatforming to multi-tenant.
**Why me:** I've built and run my own multi-tenant SaaS at oncallchat.ai — every architectural call is one I've tested with paying customers.

---

## ⑩ Cold email infrastructure (NEW)

**Title:**
```
You will get a cold email system that doesn't burn your domain
```

| Tier | Price | Timeline |
|---|---|---|
| T1 Domain Setup | **$1,800** | 4 days |
| T2 Outbound Engine ★ | **$3,200** | 7 days |
| T3 Full Pipeline | **$5,500** | 14 days |

**T1 Domain Setup:** 1–2 domains warmed (SPF/DKIM/DMARC) · 3–5 inboxes · Apollo with verified-only filters · 1 campaign launched (3-email sequence).
**T2 Outbound Engine adds:** 3–5 domains, 10–15 inboxes · Instantly.ai campaigns · reply webhook auto-categorization · Slack hot-reply alerts · weekly dashboard.
**T3 Full Pipeline adds:** AI auto-reply as you (matches tone, books meetings) · multi-step sequences with conditional branching · A/B testing · lead enrichment · monthly retainer option.

**Who this is for:** Agencies, B2B SaaS, sales teams running outbound. Founders trying to land their first 10 customers.
**Why me:** I run my own cold email pipeline (Apollo + Instantly + Zoho across 5 domains). I've debugged the deliverability traps that destroy most setups.

---

# Quick reference

| # | Type | What | Live URL |
|---|---|---|---|
| 01 | Design | Halstead & Grove law firm | [/01-law-firm.html](https://samples.oncallautomation.ai/01-law-firm.html) |
| 02 | Design | Rook & Well dental practice | [/02-dental-practice.html](https://samples.oncallautomation.ai/02-dental-practice.html) |
| 02b | Product | OnCall Agents dashboard | [/02-ai-agent-dashboard.html](https://samples.oncallautomation.ai/02-ai-agent-dashboard.html) |
| 03 | Design | Via dell'Orto restaurant | [/03-restaurant.html](https://samples.oncallautomation.ai/03-restaurant.html) |
| 04 | Design | NORTHFOLD & Co. storefront | [/04-ecommerce.html](https://samples.oncallautomation.ai/04-ecommerce.html) |
| 05 | Product | Lead intake CRM | [/05-saas-landing.html](https://samples.oncallautomation.ai/05-saas-landing.html) |
| 06 | Design | Forge Method fitness studio | [/06-fitness-studio.html](https://samples.oncallautomation.ai/06-fitness-studio.html) |
| 07 | Design | LATERAL CO. music label | [/07-shopify-skincare.html](https://samples.oncallautomation.ai/07-shopify-skincare.html) |
| 08 | Product | Voice agent analytics + Vapi | [/08-voice-agent-dashboard.html](https://samples.oncallautomation.ai/08-voice-agent-dashboard.html) |

**Live client work (separate from concept showcase):** [parkwaycafe-scarsdale.com](https://parkwaycafe-scarsdale.com)
