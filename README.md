# nexfit-ugc-ads
# NexFit — UGC Ad Content Pack
### Prompt Engineering Task 2 — AI Content Marketing using UGC Ads (Future Interns)

## Overview
This repo contains a full UGC (User Generated Content) ad system built using AI prompt engineering, for a fictional but realistic Bengaluru gym brand: **NexFit**.

The goal: generate high-converting, authentic-feeling UGC ad content — the kind real content marketing agencies produce for D2C and local business clients — using a reusable AI prompt structure.

## Brand Chosen
**NexFit** — a Bengaluru-based fitness studio.

- **Category:** Local business (fitness/gym)
- **USP:** Aesthetic-focused training programs — built around helping people get a toned, lean, "put-together" look, instead of the generic "get big and lift heavy" approach most gyms push.
- **Core problem the ad solves:** Most gyms design programs around raw strength/size goals, not the aesthetic look people actually want. This creates frustration for people who train consistently but don't end up with the physique they're after.

## What's in this repo

```
aesthetic-ugc-ads/
├── README.md
├── prompts/
│   └── ugc_prompt_template.md   → reusable AI prompt system (works for any brand)
└── outputs/
    ├── hooks.md                  → 15 hooks across 4 different angles
    ├── scripts.md                → 3 full ad scripts (Problem → Discovery → Solution → CTA)
    └── captions_ctas.md          → CTA variations (soft/medium/hard) + captions with hashtags
```

## How the Content Was Generated
All content was generated using a single reusable prompt template (see `/prompts/ugc_prompt_template.md`). The template takes 6 inputs — brand, product/service, audience, pain point, USP, and tone — and outputs hooks, a full script, CTA variations, and a caption.

This same prompt can be reused for any other brand by just swapping those 6 fields, which was a core requirement of the task (reusable prompt structure for multiple brands).

## Key Features Demonstrated
- ✅ Authentic UGC tone (no corporate/salesy language — scripts explicitly avoid words like "premium," "revolutionary")
- ✅ Multiple hooks for one product (15 hooks across 4 angles)
- ✅ Clear conversion intent (structured CTAs at 3 intensity levels)
- ✅ Platform-specific content (built for Instagram Reels, 30-45 sec spoken length)
- ✅ Reusable prompt structure (single template, works across brands)

## Key Features (App Version)
- ✅ Business Input Form (name, category, audience, pain point, USP)
- ✅ AI-generated UGC Ad Scripts (Gemini API)
- ✅ Multiple Hooks, CTAs & Ad Copy Variations
- ✅ Instagram, Facebook & Short-form Content Generation
- ✅ 7-Day Content Calendar
- ✅ Interactive Campaign Dashboard
- ✅ PDF Export of full campaign
- ✅ Modern UI/UX with animations, fully responsive

*(Scoped down from a full "business discovery wizard + campaign DNA + audience psychology
engine" version to keep the build realistic for a solo prompt-engineering task — see
`antigravity_build_prompt_fullstack.md` for exact scope decisions.)*

## Tools & Technologies Used
- React.js
- FastAPI (Python)
- Tailwind CSS
- Framer Motion
- Google Gemini API
- Prompt Engineering
- REST APIs
- Git & GitHub

## What I Learned
- Structuring AI prompts to return strict, parseable JSON output
- Connecting a React frontend to a FastAPI backend via REST APIs
- Integrating the Google Gemini API into a real application flow
- Building an interactive multi-tab dashboard UI
- Client-side PDF export of generated content
- Scoping a project realistically — deciding what to build vs. what to cut

## Author
Shivaraj — Prompt Engineering Intern, Future Interns
