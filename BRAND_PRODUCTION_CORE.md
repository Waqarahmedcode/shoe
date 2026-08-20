# SHAN & MARFANI — Brand & Production Core

## Correct Brand Name
**SHAN & MARFANI**
Primary monogram: **S&M**

The spelling **MARFANI** is locked. Do not use MARFANY.

## Core Idea
SHAN & MARFANI is conceived as a premium, high-energy sneaker and streetwear e-commerce identity for people who treat footwear as part of personal identity rather than a basic utility product.

## Visual Philosophy
The brand should feel:
- International and premium
- Gen-Z aware without looking childish
- Athletic, kinetic and energetic
- Bold but controlled
- Dark, cinematic and high-contrast
- Equally strong in a premium light mode
- Product-first: the sneaker is always the visual hero

## Hero Philosophy
The opening screen must create immediate impact.

Structure:
1. Bold kinetic typography on the left
2. Large floating sneaker in the visual center
3. Color explosion behind the sneaker
4. Ground/reflection layer below for depth
5. Minimal product/brand information
6. Strong primary CTA
7. Controlled motion, not random animation

Hero headline:
**MOVE BEYOND LIMITS**

Supporting line:
**Premium Sneakers & Streetwear — For Those Who Never Settle.**

## Motion Philosophy
Animation must reinforce product desirability.

Recommended production behavior:
- Sneaker enters with scale + rotation + depth
- Subtle idle floating motion
- Pointer/touch parallax
- Scroll-linked rotation and vertical movement
- Explosion layer moves slower than sneaker to create depth
- Reflection responds subtly to sneaker position
- Typography reveals in staggered blocks
- CTAs and navigation appear after the main visual
- Respect `prefers-reduced-motion`

For true 3D production, use a GLB/GLTF sneaker model with Three.js or React Three Fiber. These PNG/WebP assets are the fallback and art-direction layer.

## Color System
- Acid Lime: `#C8FF00`
- Hot Pink: `#FF2ED1`
- Electric Purple: `#7A3DFF`
- Cyan: `#00D6FF`
- Energy Orange: `#FFB800`
- White: `#FFFFFF`
- Near Black: `#0D0D0D`

Use neon colors as controlled accents. Black/white should carry most of the interface.

## Typography Direction
Headline: condensed, heavy, athletic display typography.
“BEYOND”: expressive brush/street lettering with lime → orange → pink → purple/cyan energy.
UI/body: clean modern sans-serif.

Do not rely on the typography PNG for every heading. Use real HTML text for accessibility, SEO and responsiveness; the PNG is primarily a campaign/hero art asset.

## Mobile Rules
Mobile is not a reduced desktop screenshot.
- Keep the headline readable above the fold.
- Let the sneaker overlap the content area deliberately.
- Keep the shoe as the largest visual object.
- Reduce particle density on mobile.
- Use smaller/lighter animation workloads.
- Preserve touch scrolling; do not hijack gestures.
- Load WebP first, PNG as fallback where appropriate.

## Desktop Rules
- Use larger negative space.
- Allow deeper parallax.
- Keep the hero shoe between typography and secondary information.
- Avoid excessive simultaneous movement.

## Production Asset Roles
1. `01_hero_sneaker_transparent` — primary product visual / fallback for 3D model.
2. `02_color_explosion_transparent` — rear energy/background layer.
3. `03_ground_reflection_transparent` — lower depth/reflection layer.
4. `04_move_beyond_limits_typography` — campaign typography art.
5. `05_SM_logo_SHAN_MARFANI` — brand lockup.

Both PNG and lossless WebP versions are included.

## E-commerce UX Principle
Visual impact must never make shopping harder. Product name, size, price, condition, CTA, cart and navigation remain clear and fast.

## Technical Direction
Recommended production stack:
- Next.js
- TypeScript
- Tailwind CSS
- Framer Motion / GSAP for interface motion
- Three.js / React Three Fiber only for the hero 3D experience
- Responsive WebP/AVIF image delivery
- Lazy loading below the fold
- Mobile performance budget first

## Brand Guardrails
Do not copy Nike, Adidas or another existing brand's logo, campaign composition, slogan or trade dress. The target is equivalent production quality and confidence, not imitation.

## Final Standard
The first 3 seconds should communicate:
**premium sneaker culture + movement + color + confidence + product obsession.**

Every later page should feel like it belongs to the same system.
