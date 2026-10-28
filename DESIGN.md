---
name: Cyber Meme Arcade
colors:
  surface: '#121123'
  surface-dim: '#121123'
  surface-bright: '#39374a'
  surface-container-lowest: '#0d0c1d'
  surface-container-low: '#1b1a2b'
  surface-container: '#1f1e2f'
  surface-container-high: '#29283a'
  surface-container-highest: '#343346'
  on-surface: '#e4e0f8'
  on-surface-variant: '#debec8'
  inverse-surface: '#e4e0f8'
  inverse-on-surface: '#302e41'
  outline: '#a68992'
  outline-variant: '#574048'
  surface-tint: '#ffb0cd'
  primary: '#ffb0cd'
  on-primary: '#640039'
  primary-container: '#f751a1'
  on-primary-container: '#570032'
  inverse-primary: '#b4136d'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#ffb95f'
  on-tertiary: '#472a00'
  tertiary-container: '#ca8100'
  on-tertiary-container: '#3e2400'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffd9e4'
  primary-fixed-dim: '#ffb0cd'
  on-primary-fixed: '#3e0022'
  on-primary-fixed-variant: '#8c0053'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#121123'
  on-background: '#e4e0f8'
  surface-variant: '#343346'
  surface-base: '#0d0c1d'
  surface-card: '#141226'
  surface-elevated: '#1c1936'
  border-subtle: rgba(255, 255, 255, 0.08)
  border-glow: rgba(236, 72, 153, 0.35)
  accent-emerald: '#10b981'
  accent-purple: '#a855f7'
  state-correct: '#10b981'
  state-wrong: '#ef4444'
  text-primary: '#f8fafc'
  text-secondary: '#94a3b8'
  text-muted: '#64748b'
typography:
  display-xl:
    fontFamily: Outfit
    fontSize: 56px
    fontWeight: '900'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Outfit
    fontSize: 36px
    fontWeight: '900'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Outfit
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Outfit
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 30px
  title-lg:
    fontFamily: Outfit
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Outfit
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Outfit
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Outfit
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Outfit
    fontSize: 15px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Outfit
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.04em
  label-badge:
    fontFamily: Outfit
    fontSize: 11px
    fontWeight: '800'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  margin: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system is engineered for viral entertainment, competitive social trivia, and internet subculture fandom. It balances hyper-energetic arcade gamification with modern, refined digital craftsmanship. The experience feels fast, punchy, and instantly engaging—evoking late-night gaming sessions, twitchy competitive reflexes, and the shared communal joy of viral internet humor.

The aesthetic fuses **Modern Neo-Arcade Glassmorphism** with **Deep Cyberpunk Minimalism**:
- **Atmosphere:** Deep obsidian-indigo surfaces paired with neon gas emissions (electric magenta, cyber cyan, and arcade gold).
- **Depth:** High-clarity frosted glass panels with hairline prismatic borders (`rgba(255, 255, 255, 0.08)` to vibrant gradient fringes) suspended above deep atmospheric darkness.
- **Micro-interactions:** High-energy responsiveness, glow halos, tactical state toggles, and snappy gamified feedback loops (correct streaks, buzzer countdowns, rank promotions).

## Colors

The palette revolves around deep, luminous contrast. Backgrounds are intentionally kept at ultra-low luminance (`#0d0c1d` and `#141226`) to maximize the perceived brightness and kinetic energy of foreground neon elements without causing ocular fatigue.

### Color Tokens & Hierarchy
- **Primary (`#ec4899` Electric Magenta):** The signature brand accent and primary call-to-action engine. Used for play buttons, high-priority notifications, and winning rank highlights.
- **Secondary (`#06b6d4` Cyber Cyan):** Multiplayer modes, secondary interactive controls (1v1 duels), informational pills, and active quiz timers.
- **Tertiary (`#f59e0b` Arcade Amber):** Trophies, leaderboard ranks, XP multipliers, streak counts, and hot challenges.
- **Neutral (`#0d0c1d` Obsidian Slate):** Foundation background tone that provides absolute depth.

### Functional States
- **Correct Answer:** Emerald (`#10b981`) with an ambient green blur.
- **Incorrect Answer:** Crimson (`#ef4444`) accompanied by an immediate visual snap.
- **Glass Shading:** Surfaces utilize `#141226` blended with `backdrop-filter: blur(16px)` and subtle linear border highlights (`border-subtle`).

## Typography

The design system standardizes on **Outfit** to provide geometric punch, modern proportions, and high readability under frantic quiz conditions.

### Expressive Heading Hierarchy
- Display titles and heroic quiz banners use extra-bold weights (`800`–`900`) with tight letter spacing and subtle italic slant to convey speed, movement, and meme punchlines.
- Dual-color typographic emphasis: Emphasize key punchlines within headings using vibrant gradients (e.g., Electric Magenta to Cyber Cyan or Arcade Gold).

### Body & Data
- Body copy is kept clean and legible with generous line heights to preserve clarity on dark glass surfaces.
- Micro-labels, gamification tags, streak counters, and leaderboard placements leverage uppercase styling with positive tracking (`0.04em`–`0.08em`) to mimic digital arcade interfaces.

## Layout & Spacing

The layout operates on a fluid 12-column responsive grid anchored around an 8px base rhythm. It is built to present video-first content, split interactive options, and real-time multiplayer status rails.

### Responsive Breakpoints
- **Mobile (< 768px):** 4-column layout, `1rem` edge margin. Video quiz questions snap to full-width or a 4:5 vertical reel ratio. Answer options stack vertically as high-touch hit targets (minimum height: 56px).
- **Tablet (768px - 1024px):** 8-column layout, `1.5rem` margins. Two-column layout pairing media players with quiz controls side by side.
- **Desktop (> 1024px):** 12-column layout centered with max-width `1280px`. Left/center stage hosts the main game arena, and right rails support leaderboards, user streak medals, and chat.

### Spacing Philosophy
- Dense internal card padding (`space-md` to `space-lg`) keeps the interface compact, game-ready, and tactile.
- Generous outer section margins (`space-xl`) isolate distinct game categories, FAQ drawers, and community footers.

## Elevation & Depth

Visual hierarchy uses layered translucent surfaces, perimeter glow effects, and deep chromatic shadows rather than standard opaque grey drop shadows.

### Surface Tiers
- **Tier 0 (Canvas):** Pure dark background (`#0d0c1d`) complemented by soft background radial blurs in magenta and cyan at 10% opacity.
- **Tier 1 (Panels & Cards):** Translucent card surface (`rgba(20, 18, 38, 0.75)`) with `backdrop-filter: blur(16px)` and a crisp outer stroke (`1px solid rgba(255, 255, 255, 0.08)`).
- **Tier 2 (Modals & Floating HUDs):** Elevated surface (`rgba(28, 25, 54, 0.90)`) with a dynamic drop shadow: `0 20px 40px -15px rgba(0, 0, 0, 0.7), 0 0 20px rgba(236, 72, 153, 0.15)`.

### Interactive Glow States
- Focused and hovered elements trigger neon energy spillover: `box-shadow: 0 0 20px rgba(236, 72, 153, 0.45)`.
- Correct answers pulse with emerald diffusion: `0 0 24px rgba(16, 185, 129, 0.5)`.

## Shapes

The design system implements a **Rounded (Level 2)** shape standard:
- Standard buttons, input fields, badge cards, and options use `0.75rem` to `1rem` corner radii.
- Modals, large game preview cards, and video containers use `1.25rem` to `1.5rem`.
- Status pills, streak counters, and notification chips use full pill shapes (`rounded-full` / `9999px`) to reinforce casual arcade tactile cues.
- Slanted clip-paths (e.g., `-6deg` skew) are optionally applied to special promotional tags ("YARIŞMA BAŞLADI", "X2 PUAN") for competitive flair.

## Components

### Buttons & Action Controls
- **Primary CTA ("Hemen Başla"):** Solid gradient fill (`linear-gradient(135deg, #ec4899 0%, #db2777 100%)`) with white bold text, subtle inner top bevel (`inset 0 1px 1px rgba(255,255,255,0.3)`), and high-intensity magenta hover glow.
- **Secondary Game Modes (1v1 Düello, Grup Yarışma):** Translucent neon fills (Cyan `#06b6d4` and Emerald `#10b981`) with glassy sheen overlays and 1px matching borders.
- **Icon Quick-Actions:** Square rounded glass tiles (`#141226`) with centered colored icon and label underneath; responds to hover with a 2px upward translate and perimeter border brightening.

### Quiz State Components
- **Multiple-Choice Tiles:** Wide rectangular glass cards with uppercase key indicators (A, B, C, D) inside circular frosted badges.
  - *Default:* Dark slate border (`rgba(255, 255, 255, 0.08)`).
  - *Selected:* Glowing cyber-cyan stroke and subtle cyan gradient wash.
  - *Success (Correct):* Emerald background tint, green perimeter glow, checkmark flare.
  - *Failure (Wrong):* Crimson outline with shake animation and dimmed opacity on unselected answers.
- **Timer / Buzz Bar:** Linear progress bar with an animated gradient traveling from cyan to magenta, shifting to flashing crimson when `< 3s` remains.

### Gamified Badges & Chips
- **Status Pills:** Small, pill-shaped indicators containing a pulsating dot (e.g., green dot + "Online Yarışma Başladı") over `rgba(16, 185, 129, 0.12)`.
- **Leaderboard Ranks:** Gold (`#f59e0b`), Silver (`#94a3b8`), and Bronze (`#b45309`) badge crowns with embedded avatar frames and point counters.

### Inputs & Text Areas
- Obsidian glass container with inset border (`1.5px solid rgba(255, 255, 255, 0.12)`).
- On focus: Transition border to `#ec4899` with `0 0 12px rgba(236, 72, 153, 0.25)` halo. Placeholder text styled in `#64748b`.

### Video & Meme Cards
- 16:9 or 9:16 aspect ratio containers with smooth rounded corners, hairline glass border, and dark scrim gradients at the bottom for superimposed question subtitles and source tags.