# DESIGN.md — MIRRIS by Attic & Keller Dashboard

## Brand Identity
- Brand: MIRRIS by Attic & Keller (A&K)
- Theme: Dark premium restaurant analytics
- Accent Color: `#FF6B35` (warm orange — signature A&K)
- Secondary: `#3B9AFF` (cool blue contrast)

## Color Palette
- Background: `#0A0A0F`
- Surface: `#12121A`
- Surface elevated: `#1A1A26`
- Border: `#2A2A3A`
- Text primary: `#F0F0F5`
- Text secondary: `#8888A0`
- Accent primary: `#FF6B35`
- Accent secondary: `#3B9AFF`
- Success: `#22C55E`
- Danger: `#EF4444`
- Warning: `#FBBF24`

## Typography
- Display: `Inter` (700, 800)
- Body: `Inter` (400, 500, 600)
- Monospace: `JetBrains Mono` (for numbers)

## Shape
- Border radius: `12px` (cards), `8px` (badges), `50%` (avatars)
- Border: `1px solid rgba(255,255,255,0.06)`

## Animation
- Counters: Animate from 0 to final value over 1.5s (ease-out)
- Bars: Grow from left 0% to final width over 1s (staggered 100ms)
- Donut: Animate stroke-dasharray from 0 over 1.2s
- Cards: Fade in + translateY(20px → 0) over 0.6s (staggered 150ms)
- Hover: Scale 1.02 + border-glow accent color

## Components
- KPI Card: Surface bg + left accent bar + value + label + delta badge
- Bar Chart: Horizontal bars + gradient fill + value label
- Donut Chart: SVG + center label + legend below
- Spark Line: Minimal line chart for daily trend
- Table: Alternating row shading + hover highlight