PubliTracker — Waiting-List Landing Page Blueprint

Goal: capture qualified leads (e-mail + optional company + influencer-volume field) for private beta.

Another commit
⸻

1 · Above-the-Fold “Hero”

Element Copy / Design Guidance
Headline “Know the moment your brand gets dropped—or doesn’t.”
Sub-headline “PubliTracker listens, watches and reads every influencer post on Instagram, TikTok & YouTube so you never miss a promised mention.”
Primary CTA → Join the Private Beta (button opens a short modal form)
Secondary CTA See How It Works ↓ (smooth-scroll anchor)
Visual Split layout: left 60 % punchy headline/CTA, right 40 % looping hero animation (phone screen auto-scrolling Reels while coloured bounding boxes highlight detected logo + transcript line appears).
Trust badges Tiny greyscale logos / placeholders: “Backed by ML engineers from Meta, ex-TikTok, ex-Shopify”.

⸻

2 · Problem → Promise Strip

Dark section with diagonal cut, quick copy-swap marquee.

Pain: “500 creators, 5 000 videos… and your team is still checking clips one-by-one.”
Promise: “Flip the script: automation that flags misses before finance wires the invoice.”

⸻

3 · Value Prop Tiles (Three-up Grid) 1. Real-time Alerts
“Slack, e-mail or webhook the second a shout-out happens—or doesn’t.” 2. Multimodal AI Accuracy
“Speech, text and pixels cross-checked, confidence-scored.” 3. Audit-Ready Evidence
“Screenshots & 6-sec clips stored for contract compliance.”

⸻

4 · “Under the Hood” Interactive Stepper

Numbered horizontal stepper; each step swaps a short GIF and 50-word blurb. 1. Connect Campaigns
Creator handles, coupon codes & key phrases into our dashboard. 2. Continuous Listening
24/7 ingestion of posts, shorts, lives. 3. AI Triangulation
OCR + ASR + CV vote on every mention. 4. Instant Insight
Alert → evidence card → analytics. 5. ROI Loop-Back
Shopify / GA4 integration maps conversions to shout-outs.

⸻

5 · Benefits for Growth Teams (Targeted to ICP)

Metric Manual World With PubliTracker
Verification Time ~4 h / creator / month < 4 min (99 % automated)
Missed Mentions ~12 % undetected < 1 % (confidence-scored)
Campaign Debrief Next quarter Live dashboard

Footnote: Data sampled from pilot with a 600 M R$ Brazilian DTC brand.

⸻

6 · Social Proof & Roadmap

“Phase 1 closed beta: Insider Store & 3 stealth brands. Phase 2 opens July 2025—your slot awaits.”
Add rotating testimonials carousel placeholder.

⸻

7 · Wait-List Form (Sticky or Modal)

Fields: Work e-mail (required) · Brand / Agency · Influencer volume (#/month) · Main platform (dropdown).
Copy under button:

“⚡ We’ll review applications weekly and onboard early adopters in batches of 20.”

⸻

8 · Security / Privacy Ribbon

Lock icon · “GDPR-ready” · “Read-only OAuth scopes” · “Data encrypted in transit & at rest.”
Short 2-sentence disclosure to allay compliance teams.

⸻

9 · Light Preview of Pricing (Optional)

Small card:
Starter (up to 50 creators) – starting at US $199/mo.
Enterprise – let’s talk.
Text: “Founding-customer discounts for wait-list sign-ups.”

⸻

10 · FAQ Accordion (4-6 items)
• Does it work with podcasts? (Yes, via YouTube & RSS ingestion)
• Can I push data to Looker / Tableau? (Webhook + API)
• Accuracy? (Internal benchmarks: 92 % F1 across 30 k videos)
• Will you support Twitch / Twitter? (Road-mapped Q4 2025)

⸻

11 · Footer

Minimal: logo, one-liner, social icons, contact e-mail, legal links, subtle signup repetition.

⸻

Copy & Tone Cheatsheet
• Conversational, data-backed, emoji-light.
• Sprinkle Brazil-friendly references where relevant (“Não deixe nenhum #publi passar batido”).
• Micro-humour: “Stop doom-scrolling your own ads, let the robots do it.”

⸻

Visual & Brand Guidelines

Theme Guidance
Palette Midnight #0B0F1A (background) · Electric Magenta #F72585 (accents) · Sky #4CC9F0 (links) · Mint #BDF9DA (success) – energetic yet credible tech + creative vibe.
Typography Headings: Inter Bold 900, text: Inter Regular 400; letter-spacing tight for headlines.
Imagery Neon outlines around UGC thumbnails, subtle waveforms to hint at audio analysis, blurred gradient blobs for depth.
Motion 0.3 s ease-out fades, scroll-triggered slide-ups; hero GIF <1 MB loop.

Implementation Sequence 1. Lock domain & DNS. 2. Set colours & typography in a Tailwind config (optional). 3. Craft hero animation (Lottie or MP4). 4. Build section skeleton, mobile-first. 5. Integrate form endpoint + success modal. 6. Add Plausible snippet, goal = wait-list-signup. 7. Accessibility pass (contrast, alt tags, focus outlines). 8. Deploy to main branch → GitHub Pages.

Next step: polish your logo in the new palette, then ship the hero section first—iteration beats perfection. 🚀
