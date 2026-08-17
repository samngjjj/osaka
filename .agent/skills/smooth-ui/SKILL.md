---
name: smooth-ui
description: >-
  Design and build fluid, high-aesthetic web interfaces with buttery-smooth micro-interactions,
  spring physics, modern typography, glassmorphism depth, and tactile mobile-first ergonomics.
  Use when designing or upgrading UI/UX to feel alive, premium, and motion-rich.
---

# SmoothUI Design & Motion Engineering Skill

SmoothUI is a design and frontend engineering standard focused on crafting lively, responsive, and visually stunning web interfaces with fluid motion and tactile polish.

## Core Design Principles

1. **Fluid Motion Physics**
   - Use custom cubic bezier transitions: `cubic-bezier(0.16, 1, 0.3, 1)` for spring-like organic feels.
   - Micro-interactions on all interactive elements: hover scale (`transform: scale(1.02)`), active press (`transform: scale(0.97)`), and smooth shadow elevations.
   - Smooth tab switching with sliding indicator pills and fade-and-slide content transitions.

2. **Visual Depth & Glassmorphism**
   - Layered surface architecture: Base background with ambient glow radial gradients + semi-transparent card containers (`backdrop-filter: blur(16px)`).
   - High-contrast typography hierarchy using modern paired fonts (e.g. Plus Jakarta Sans / Outfit + Noto Sans TC).
   - Subtle sub-pixel border highlights (`border: 1px solid rgba(255, 255, 255, 0.08)` and hover `rgba(255, 255, 255, 0.2)`).

3. **Journey & Storytelling UI ("Travel Feel")**
   - Thematic color palettes reflecting the destination:
     - Osaka Neon Cyan (`#38bdf8`) & Electric Violet (`#a855f7`)
     - Kyoto Vermilion / Torii Red (`#f43f5e` / `#ea580c`)
     - Match / Nature Emerald (`#10b981`)
     - Sunset Gold (`#f59e0b`)
   - Interactive widgets: Live currency converter, checklist items with celebratory check animations, transit timeline nodes with directional indicators.

4. **Reliable Media & Error Resilience**
   - Always provide reliable CDN URLs for media (Unsplash with auto-format & quality parameters).
   - Implement graceful fallback handlers (`onerror`) with stylized SVG placeholders so no image ever appears broken.
   - Fullscreen lightbox / modal viewing for imagery.

5. **Mobile-First Touch Ergonomics**
   - Sticky tab bar with horizontal smooth drag / scroll snap.
   - Minimum tap target size >= 44px for buttons and map links.
   - Direct integration with native apps (Google Maps, Apple Maps, copy address to clipboard).
