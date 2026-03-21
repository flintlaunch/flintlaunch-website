# FlintLaunch Redesign — Design Brief

## Top 5 Design Patterns to Borrow

### 1. OLED Black Depth (Linear)
Linear uses `#08090A` — a near-true black that makes everything feel premium and intentional. Our current `#0a0f1a` is already close, but we can push it slightly. More importantly: no gradients on large backgrounds. The depth comes from contrast and layering, not gradient transitions.

**Apply to:** Background refinement, card surfaces

---

### 2. Characterful Body Typography (Loom)
Loom's Charlie Display/Text creates instant brand recognition. We're keeping Space Grotesk for display — it's part of the brand. But Inter for body copy is generic. Replacing with **Outfit** (Google Fonts) gives a more rounded, technical-yet-approachable personality that reads more distinctively at body sizes.

**Apply to:** All body copy, descriptions, and paragraph text

---

### 3. Bold Hero Presence (Loom)
Loom's 70px hero h1 and confident one-liner headline creates authority from first scroll. Our "AI Venture Builder." is already bold — we just need the staging to match: animated backdrop, glow behind the headline, and aurora-like ambient motion that makes it feel alive without being loud.

**Apply to:** Hero section — animated glow, aurora blobs, headline staging

---

### 4. Geometric Precision (Linear)
Linear's tight 2-4px border radius on components signals engineering discipline. Our cards use 12-18px radius, which reads as consumer-friendly. The tiered card system (t1/t2/t3) already creates hierarchy — we deepen it with colored box shadows (jade/gold-tinted) rather than just border changes.

**Apply to:** Card hover states, button hover effects, shadow system

---

### 5. Editorial Restraint (read.cv + Linear)
Both sites use whitespace as a design element. Less motion is more attention. The key insight: **animate with purpose, not decoration**. One well-orchestrated scroll reveal per section beats scattered micro-animations. The process tracker should feel like watching code execute — step by step, mechanical, deliberate.

**Apply to:** Process tracker (sequential step-by-step reveal), section fade-in timing

---

## Direction
**Dark OLED luxury meets engineering discipline.**

The site should feel like something a 10x engineer built for themselves — not a marketing page someone commissioned. Every effect has a reason. Nothing flickers or bounces for attention. The motion intensity is just high enough to feel alive, not high enough to distract.

Gold is the human warmth signal. Jade is the system signal. Use them with intent.
