# BugData 100x Growth Sprint

## Outcome

Turn BugData from a visually polished brochure into a crawlable, conversion-led Zimbabwean growth site. The first sprint targets technical SEO, local entity clarity, a focused managed-service offer, and a WhatsApp-first lead path.

## Design direction

**Alternative styles considered:** editorial local-growth journal (0.07); high-trust operator dashboard (0.06); premium African technology studio (0.05).

**Chosen movement:** premium African technology studio.

**Core principles:** decisive hierarchy, local proof before hype, every section earns a next action, and fast mobile reading.

**Color philosophy:** retain the current deep forest and mint palette as BugData's ownable signature; use amber only for commercial urgency and violet only for supporting information.

**Layout paradigm:** asymmetric editorial sections with short proof bands and conversion cards instead of a centered collection of equal feature boxes.

**Signature elements:** mint data-line accents, compact Zimbabwe-local proof labels, and WhatsApp-forward CTA language.

**Interaction philosophy:** reduce decisions to one useful next step; forms pre-compose a WhatsApp message so the interface hands the team a qualified conversation.

**Animation:** restrained hover lift and reduced-motion support; no decorative motion that delays content or distracts from the CTA.

**Typography:** keep Space Grotesk for confident headings and Inter for readable body copy.

**Brand essence:** BugData installs the systems Zimbabwean SMEs need to turn attention into enquiries and enquiries into repeatable revenue. Personality: practical, local, ambitious.

**Brand voice:** direct and commercially useful. Example: “Stop losing warm enquiries after hours.” “Get a 7-day visibility plan built around your city, offer, and WhatsApp workflow.”

## Implementation

- Add crawlable metadata, JSON-LD, canonical domain, social previews, robots, sitemap, manifest, and a not-found page.
- Create service/location page architecture with internal links from the homepage.
- Add a lead-capture module that opens WhatsApp with the prospect's context and a clear consent note.
- Replace JS-only blog discovery with an indexable blog hub and linked articles.
- Keep static HTML publication and the existing CNAME deployment model.

## Project structure

- `index.html`: primary conversion homepage and entity schema.
- `services/`: focused money pages for AI automation and SEO.
- `locations/`: location pages only for genuine service coverage.
- `blog/`: crawlable article index and article pages.
- `assets/`: compressed brand and editorial imagery.
- `robots.txt`, `sitemap.xml`, `manifest.webmanifest`, `404.html`: search and browser infrastructure.
- `docs/`: internal strategy and evidence.
