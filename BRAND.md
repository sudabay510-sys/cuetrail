# CueTrail — Brand identity

**Slug:** `cuetrail`  
**Tagline:** A day-by-day dog training plan shaped by your dog, home, and schedule.  
**Local port:** `5103`  
**Status:** Live. Payments processed by Gumroad (Monthly or Quarterly).

## Audience persona
New puppy parents and frustrated dog owners who want a structured plan that fits apartment or house life.

Primary personas:
- **New puppy home:** Potty, biting, and crate basics in tiny daily chunks.
- **Busy adult-dog home:** Leash manners and recall without hour-long sessions.
- **Multi-pet household:** Plans that respect shared space and overstimulation.

## Voice & tone
- Clear, encouraging, specific — never hype or fear.
- Honest about limits (General education only — not a vet or behaviorist replacement. No outcome guarantees.).
- Short sentences on landing; checklist language in plans.

## Color palette
Defined in `static/brand.css` (`:root` variables). Accent drives CTAs; background stays calm for long reading.

## Fonts (Google Fonts)
Linked via `https://fonts.googleapis.com/css2?family=Nunito:wght@600;700…` in templates.

## Logo
`static/logo.svg` — simple wordmark-friendly monogram on rounded square. Use on white/light headers; keep clear space ≈ 0.25× logo height.

## Iconography / illustration
Prefer flat geometric icons, soft corners matching `--radius`, no stock-photo people with fake quotes. Plan peeks use list + accent dots.

## Sample copy lines
- Hero CTA: “Build my dog’s plan”
- Honesty: “General education only — not a vet or behaviorist replacement. No outcome guarantees.”
- Paywall: “Start my plan” links to the Gumroad checkout URL.

## Do
- Show Monthly and Quarterly prices, plus the renewal sentence, before checkout.
- Save the customer’s email before sending them to Gumroad.
- Keep disclaimers visible near plans.
- Mobile-first quiz (one question per screen).

## Don’t
- Fake testimonials, stats, or press logos.
- Guarantee results (income, rankings, behavior, bookings).
- Fake urgency (“only 2 spots left”).
- Auto-edit third-party listings (SignMatch) or promise AI magic without saying plans are rule-based in this prototype.

## Explicit palette (hex)

| Token | Hex |
|-------|-----|
| Background | `#F3F6F1` |
| Alt background | `#E6EEE4` |
| Card | `#FCFFFB` |
| Ink | `#1E2A1F` |
| Muted | `#5D6B5E` |
| Accent | `#4F7A4E` |
| Accent hover | `#3D623C` |
| On-accent | `#F5FFF3` |

**Display font:** Nunito  
**Body font:** Nunito Sans

## Logo file
`static/logo.svg`


## Identity refresh (Nov 2026)

Visual layer only (`static/identity.css`, `static/logo.svg`, Google Fonts URL). Quiz questions, plan generation, routes, pricing, checkout/unlock, and safety notes are unchanged.

- **Concept:** Trail map adventure. Training as a walk you take together: a dotted trail, milestone markers, and a dog-tag result badge.
- **Type:** Fredoka (display) / Nunito Sans (body)
- **Voice:** A patient trainer friend at the park: short steps, small wins, and a straight answer when it’s time for a professional.
- **Persona (design assumption, not research):** Priya, first-time puppy owner in an apartment (assumption): Brought home a 5-month-old mix. Leash walks are a tug-of-war and the neighbors notice.

| Color | Hex |
|---|---|
| Trail cream | `#F7F4EA` |
| Meadow | `#2F6B3F` |
| Tennis ball | `#D7F05B` |
| Sky | `#CDE7F0` |
| Bark | `#6B4A2F` |
| Forest ink | `#1F2A1E` |

Full brand guide, persona, and journey: `quiz-to-plan-redesign/products/cuetrail/brand.html`.
