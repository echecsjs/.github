# echecs.dev — Agent Instructions

## Design Context

### Users
Mixed audience: hobbyist chess developers building side projects, professional teams creating tournament management and chess platform software, and open-source contributors evaluating packages for adoption. They arrive at echecs.dev to understand what packages exist, judge whether the ecosystem is trustworthy, and find their way into documentation. The page needs to serve all three jobs — directory, credibility, and routing — without feeling bloated.

### Brand Personality
**Warm, approachable, crafted.** Like a well-made wooden chess set — the craft comes first, the precision lives underneath. The site should feel like it belongs to chess culture: it's unmistakably a place for chess people, not a generic developer tool page. The warmth leans dominant over the technical — think a hand-finished board with machine-precise squares, not a terminal with warm colors.

### Aesthetic Direction
- **Tone**: Crafted and inviting. Wood-shop warmth meets library quiet. Not gamified, not sterile.
- **Reference**: chess.com's cultural identity — the feeling that you're in a chess place, not a SaaS product. Take the identity clarity, leave the commercial density and ad clutter.
- **Anti-references**: Generic npm package listing pages (no personality), AI landing pages (gradients, glow, neon-on-dark, hero metrics), enterprise SaaS (bloated sections, trust badge walls).
- **Theme**: Both light and dark, no default preference — let `prefers-color-scheme` decide.
- **Color direction**: Evolve the green accent into something that still reads "chess" but belongs to echecs specifically. Tint neutrals toward the brand hue for cohesion.

### Design Principles
1. **Chess identity first.** Every design decision should make someone feel they're in a chess space.
2. **Craft over cleverness.** Prefer the feel of a hand-crafted object over flashy techniques.
3. **Confident restraint.** Organize 23 packages without overwhelming. White space and hierarchy do the heavy lifting.
4. **Earned density.** Start simple, let users discover depth. Progressive disclosure over information dumps.
5. **No AI tells.** The design must feel as hand-crafted as the zero-dependency TypeScript libraries it represents.

### Technical Constraints
- Vanilla HTML/CSS, single `index.html` — no framework, no build step
- WCAG AA compliance
- Responsive: mobile through desktop
- Zero JS dependencies (matches the library philosophy)
