# SkillLink Design Directions

## Three possible approaches

### 1. Campus Relay
**Very Brief Intro:** An energetic editorial marketplace that borrows from Nigerian campus noticeboards, paired with crisp product cards and a confident red-orange signal color. It feels social, practical, and built for immediate action rather than corporate freelancing.

**Probability:** 0.06

### 2. Studio Ledger
**Very Brief Intro:** A quiet, craft-focused directory shaped by accounting ledgers and portfolio books. Warm paper colours, ink-like type, and formal service records make emerging creators feel established.

**Probability:** 0.03

### 3. Signal Grid
**Very Brief Intro:** A dark, high-contrast digital switchboard where skills light up as signals. Dense discovery tools and bright category colours prioritise technical energy and rapid browsing.

**Probability:** 0.08

---

# Chosen Direction: Campus Relay

## Design Movement

**Contemporary editorial wayfinding meets the campus noticeboard.** SkillLink will feel like the most useful poster on a well-connected campus wall: bold, local, accessible, and immediately actionable, with high-quality digital product cues rather than a generic gig-platform aesthetic.

## Core Principles

1. **Local signals, not corporate polish:** Use campus, city, and availability as useful context beside each service rather than hiding the human behind a generic profile.
2. **Action before abstraction:** Price, delivery time, and the WhatsApp action must be instantly scannable in every service card.
3. **Editorial hierarchy:** Big, directional type and offset compositions carry attention; compact detail panels support decision-making without visual noise.
4. **Friendly momentum:** A warm, strong palette and physical interaction feedback make a first marketplace contact feel low-stakes and natural.

## Color Philosophy

The page will be grounded in **warm canvas** rather than cold white, as a visual nod to printed flyers. A deep ink navy establishes clarity and trust; SkillLink’s ownable **Signal Coral** creates a reliable action path without defaulting to a fintech-blue brand. Palm green quietly marks verified, available, and growing status. Occasional cobalt is reserved for active-filter and digital-service moments. All text sits on high-contrast solid or translucent surfaces, never directly on busy imagery.

## Layout Paradigm

The homepage moves in a **relay composition**, not a centered landing-page stack. A left-aligned, oversized hero passes into a slim category “signal strip,” then a two-column browsing zone: a compact discovery rail and a wider, deliberately staggered service feed. On wide screens, the headline interrupts the feature image; on mobile, the relay becomes a vertically ordered journey with filters in a horizontal scroll.

## Signature Elements

1. **The relay arrow:** A small diagonal arrow/check mark appears in the logo, category labels, and selected filter state to imply a skill travelling from student to customer.
2. **Skill stickers:** Category labels use compact paper-sticker treatments with a tiny colour tab rather than generic pills.
3. **Signal dots:** A dot pair marks locality and availability, repeated from service cards to the location selector.

## Interaction Philosophy

Interactions should make marketplace browsing feel certain. Filters visibly count results, saved items switch from outline to filled ink, and WhatsApp contact clicks form a clear bridge from card to conversation. Unsupported navigation options show a concise “Coming shortly” acknowledgement rather than dead-ending. Reactions are immediate, tactile, and do not interrupt scanning.

## Animation

Entrances are limited to a short 180–280ms opacity-and-translate cascade when the page first loads. Cards lift by 3px on hover and compress slightly on press. Filter chips use a 160ms colour change and a discreet arrow nudge. The hero collage has a very slow, single 2px float only when reduced motion is not requested; scrolling, navigation, and keyboard actions remain instant. All nonessential motion is disabled under `prefers-reduced-motion`.

## Typography System

**Space Grotesk** is the structural display face: bold and slightly technical for numbers, headings, service titles, and price calls. **DM Sans** carries body copy with a calmer, friendly rhythm. Headlines use tight tracking and asymmetric line breaks; navigation and metadata use uppercase micro-labels with generous tracking. Avoid centered all-caps text blocks and avoid generic large gradient type.

## Brand Essence

**SkillLink is the nearby and online service board that helps Nigerian students turn practical digital talent into paid work, without platform friction.** Its personality is **resourceful, direct, and encouraging**.

## Brand Voice

Headlines should be confident, plain-spoken, and useful. CTAs should tell the visitor exactly what happens next. Microcopy should reduce uncertainty, never exaggerate.

> “Your next project has someone closer than you think.”

> “See the work. Agree the details. Start on WhatsApp.”

## Wordmark & Logo

The mark is a bold, rounded **relay arrow** built from two offset coral strokes: one travels forward, one anchors it, creating an abstract `S` without using the letter literally. It works as a solid favicon and as a compact app mark. The accompanying wordmark uses custom-spaced Space Grotesk, with the `i` dot replaced by the small Signal Coral dot.

## Signature Brand Color

**Signal Coral — `#F15B43`**. It is the unmistakable SkillLink action colour, used for core calls to action, the relay mark, and a small number of directional highlights.

## Style Decisions

- Use warm canvas, deep ink navy, Signal Coral, palm green, and restrained cobalt; avoid purple gradients.
- Use an editorial asymmetric layout with substantial breathing room and selectively angled accents.
- Treat naira prices, location, delivery speed, and WhatsApp contact as primary marketplace information.
- Use only clearly labelled sample service listings, not reviews, ratings, or testimonials.
- Skill stickers are compact paper labels with a visible colour tab, relay arrow, and tactile noticeboard feel; avoid large generic pastel tiles or pill-only filters.
- Every listing must make price, delivery time, location, and WhatsApp handoff read as the primary marketplace triad, with decorative badges secondary.
- The relay arrow/check is the recurring SkillLink signature and should appear in the logo, primary actions, selected states, and directional labels often enough to be recognisable without the wordmark.
