# MASTER PRODUCTION PROMPT — SHAN & MARFANI

You are acting as a world-class creative director, senior 3D motion designer, luxury sportswear art director, interaction designer, front-end animation engineer, and e-commerce UX lead.

Your task is to create a production-grade sneaker e-commerce website for the original brand:

**SHAN & MARFANI**
Monogram: **S&M**
Correct spelling is **MARFANI**. Never write MARFANY.

The final experience must feel premium enough to sit beside leading international sportswear and sneaker brands, but it must remain an original visual identity and must not copy Nike, Adidas, Puma, New Balance, HOKA, On, Salomon, or any other brand's logo, campaign layout, trade dress, or slogan.

---

## 1. CORE BRAND IDEA

SHAN & MARFANI is not positioned as a cheap shoe store.

It is a premium sneaker and streetwear destination for people who care about:
- silhouette
- rarity
- performance
- comfort
- color
- styling
- originality
- sneaker culture

The first impression should communicate:

**Premium sneaker culture + movement + color + confidence + product obsession.**

Brand tone:
- bold
- modern
- energetic
- urban
- cinematic
- premium
- Gen-Z aware
- never childish
- expressive but controlled

---

## 2. HERO DIRECTION

The hero is the emotional center of the site.

Primary headline:

**MOVE**
**BEYOND**
**LIMITS**

Typography structure:
- MOVE = very heavy condensed white athletic type
- BEYOND = expressive custom brush / graffiti-style lettering
- BEYOND uses a gradient from acid lime → orange → hot pink → purple → cyan
- LIMITS = very heavy condensed white athletic type
- Typography should feel kinetic, layered and campaign-level

Supporting copy:

**Premium Sneakers & Streetwear**
**For Those Who Never Settle.**

Primary CTA:
**SHOP NOW →**

Secondary CTA:
**EXPLORE →**

Brand line:
**SHAN & MARFANI**

Optional campaign line:
**Play Hard. Stay Original.**

---

## 3. HERO COMPOSITION

Desktop layout:
- typography on the left
- giant sneaker in the center
- neon color explosion behind sneaker
- subtle reflection / wet ground below
- smaller brand lockup and product feature notes on the right
- dark cinematic base
- controlled neon accents

Mobile layout:
- headline remains readable above the fold
- sneaker remains the largest visual object
- sneaker overlaps content deliberately
- CTA stays immediately visible
- effects are simplified for performance
- no cramped desktop scaling
- no horizontal overflow

---

## 4. 3D SNEAKER EXPERIENCE

Use a true GLB/GLTF sneaker model if available.

Recommended production stack:
- Three.js
- React Three Fiber
- Drei
- GSAP or Framer Motion for UI choreography

The sneaker should:
- enter with scale + rotation + depth
- float subtly when idle
- react gently to pointer movement on desktop
- react to device orientation only if permission is available and performance is safe
- rotate slightly as the user scrolls
- move vertically with scroll progress
- use premium rim lighting
- have colored reflection accents from cyan, magenta, orange and acid lime

Do not let the 3D scene block page scrolling.

On mobile:
- cap DPR
- reduce shadow samples
- reduce particle count
- simplify post-processing
- use image fallback on weak devices
- preserve touch gestures for normal page scroll

---

## 5. ASSET LAYERING SYSTEM

Layer order from back to front:

1. background base
2. subtle grain / texture
3. low-opacity glow fields
4. color explosion
5. particles and sparks
6. main sneaker / 3D model
7. rim-light streaks
8. ground reflection
9. typography
10. feature UI / CTA
11. foreground micro-particles

Each layer must move at a slightly different speed to create cinematic depth.

---

## 6. EFFECTS

Use:
- parallax
- staggered text reveal
- mask reveals
- soft light sweeps
- controlled motion blur
- glow pulses
- subtle particle drift
- perspective tilt
- scroll-linked sneaker movement
- responsive light streaks
- gentle reflection motion

Avoid:
- excessive random motion
- heavy lens flares everywhere
- unreadable text
- long blocking intro animations
- scroll hijacking
- excessive WebGL post-processing

---

## 7. LIGHTING

Main sneaker lighting:
- cool cyan fill from lower left
- magenta/pink rim light from rear right
- orange energy light from lower rear
- acid lime highlight as a controlled accent
- soft white key light on upper materials

Lighting should reveal:
- mesh
- stitching
- sole geometry
- laces
- heel texture
- material changes

The sneaker must remain believable and premium rather than looking like a toy.

---

## 8. COLOR PALETTE

Core interface:
- Near Black: #0D0D0D
- White: #FFFFFF

Accent system:
- Acid Lime: #C8FF00
- Hot Pink: #FF2ED1
- Electric Purple: #7A3DFF
- Cyan: #00D6FF
- Energy Orange: #FFB800

Use neon colors sparingly in interface UI.
Most interface surfaces should remain black, white and neutral.

---

## 9. TYPOGRAPHY

Use real HTML text for accessibility and responsiveness.

Recommended direction:
- Display: Anton / Oswald / Archivo Black / another heavy condensed display family
- UI/Body: Inter / Poppins / modern grotesk
- BEYOND: custom brush-style lettering treatment, preferably SVG or a licensed brush font

Never turn every heading into an image.

Typography animation:
- MOVE reveals first
- BEYOND paints/reveals across the screen
- LIMITS lands last
- each line appears with slight depth offset
- the animation must finish quickly enough that the user can shop immediately

---

## 10. DARK + LIGHT MODE

Dark mode:
- black cinematic environment
- stronger neon bloom
- glossy reflections
- premium nightlife energy

Light mode:
- warm off-white / bone base
- black typography
- softer but still colorful effects
- less bloom
- sharper editorial shadows
- sneaker remains visually dominant

Theme switch must be animated subtly and preserve user preference.

---

## 11. MOBILE PERFORMANCE

Treat mobile as a first-class design.

Performance rules:
- use WebP/AVIF
- use responsive image sizes
- lazy-load below-fold media
- preload only hero-critical assets
- cap Three.js DPR around 1.5 on mobile
- use reduced particle density
- keep first meaningful render fast
- avoid giant JS bundles
- use prefers-reduced-motion
- provide static hero fallback for weak devices

---

## 12. E-COMMERCE STRUCTURE

Required pages:
- Home
- New Arrivals
- Men
- Women
- Running
- Lifestyle
- Collections
- Product Detail
- Cart
- Checkout
- Wishlist
- Account
- Order Tracking
- About
- FAQ
- Shipping & Returns
- Size Guide
- Contact / WhatsApp

Pakistan-ready:
- PKR
- Cash on Delivery
- digital payment placeholder
- nationwide delivery
- WhatsApp support
- clear returns workflow

---

## 13. PRODUCT CARD SYSTEM

Cards must feel editorial but practical.

Each product card should include:
- large product image
- product name
- category
- price
- size
- condition if pre-loved
- quick add
- wishlist
- hover image
- badge
- subtle tilt or depth effect

Do not let animation interfere with product information.

---

## 14. MICRO-INTERACTIONS

Use:
- magnetic CTA hover
- card lift
- image zoom
- underline growth
- button press feedback
- animated cart count
- smooth nav transition
- subtle cursor interaction on desktop
- touch-safe behavior on mobile

---

## 15. OPENING SEQUENCE

Recommended choreography:

0.0–0.25s:
dark frame with subtle ambient glow

0.25–0.6s:
brand mark appears

0.45–0.9s:
background color energy begins

0.6–1.15s:
sneaker enters with depth and rotation

0.8–1.3s:
MOVE reveals

1.0–1.5s:
BEYOND brush reveal

1.15–1.65s:
LIMITS reveals

1.3–1.8s:
CTA and navigation settle

Total sequence should feel premium but should not delay shopping.

---

## 16. SCROLL SEQUENCE

As user scrolls:
- sneaker rotates 8–18 degrees total
- sneaker shifts slightly upward
- background explosion moves slower
- typography separates subtly
- reflection moves with lower parallax
- particles drift independently
- next section enters beneath hero

Do not create aggressive scroll-jacking.

---

## 17. ACCESSIBILITY

Must include:
- semantic HTML
- keyboard navigation
- visible focus states
- accessible contrast
- alt text
- reduced motion mode
- no flashing
- real text for important messages

---

## 18. PRODUCTION QUALITY BAR

The site must NOT look like:
- a generic Shopify template
- a cheap theme
- a simple AI landing page
- a copied Nike homepage
- a collage of random neon effects

It should feel art-directed.

Every effect needs a purpose:
- sneaker = hero
- color explosion = energy
- reflection = depth
- particles = motion
- typography = identity
- UI = conversion

---

## 19. REQUIRED OUTPUT FROM AI / DEVELOPER

When generating the site, return:
1. complete responsive code
2. component structure
3. asset paths
4. animation logic
5. mobile fallback logic
6. dark/light mode
7. optimized loading strategy
8. README
9. deployment instructions
10. editable content/data structure

Preferred stack:
**Next.js + TypeScript + Tailwind CSS + Framer Motion + Three.js/React Three Fiber**

If the environment cannot support that stack:
use clean HTML/CSS/JavaScript with progressive enhancement.

---

## 20. FINAL TEST

Before calling the build complete, verify:

- Does the first screen instantly feel like premium sneaker culture?
- Is the sneaker clearly the hero?
- Is MOVE BEYOND LIMITS immediately legible?
- Does mobile feel intentionally designed?
- Are motion effects smooth?
- Does dark/light mode both feel premium?
- Can a user shop without fighting the animation?
- Is the brand always written SHAN & MARFANI?
- Does the experience remain original rather than copying another brand?

If any answer is no, refine the implementation before final output.
