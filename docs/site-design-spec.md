# Technical Design Specification  
## Kavishni Nanayakkara — Economics Researcher

### 1. Purpose

Design and implement a modern Quarto personal website for **Kavishni Nanayakkara**, an **Economics Researcher at Nanyang Technological University, Singapore**, whose primary intellectual focus is **AI and Human Behaviour**.

The site should function simultaneously as:

- a credible academic/research profile;
- a home for research projects and future publications;
- a gateway to writing on Substack;
- a record of speaking and public engagement;
- a curated reading and intellectual-life space;
- a sophisticated personal professional presence.

The site must **not describe Kavishni as a PhD student, PhD candidate, or doctoral researcher**.

The overall impression should be:

> **A literary academic profile with the restraint of a scholarly journal and the polish of a contemporary editorial publication.**

It should feel intelligent, calm, cultivated, approachable, and distinctive without looking like a design-agency portfolio.

---

# 2a. Core Creative Direction

Use a roughly **50/50 balance between academic restraint and editorial sophistication**.

The design should combine:

- rigorous academic information hierarchy;
- literary/editorial typography;
- generous negative space;
- restrained warm colours;
- extremely limited animation;
- subtle photography;
- high accessibility;
- understated contemporary details.

Visual references may inform the design, but the final site must **not imitate any one reference directly**.

The aesthetic should avoid both extremes:

**Do not make it:**

- a generic university faculty website;
- a Bootstrap-heavy academic template;
- a highly animated creative-agency portfolio;
- a tropical-themed Singapore website;
- an NTU-branded website;
- an influencer/personal-brand landing page;
- a newsletter sales funnel;
- a maximalist editorial experiment.

Instead, create a site that feels closer to:

> **an independent literary journal × a contemporary academic profile × a beautifully typeset research notebook**

# 2b. Personal Web / Pre-AI Character

The site should retain academic credibility and editorial restraint while
feeling personally authored, handmade and slightly idiosyncratic.

Inspiration may come from older personal academic websites and the
pre-AI-generated personal web.

Desired qualities:
- direct page structure;
- ordinary but characterful hyperlinks;
- small signs of personality;
- chronological updates;
- plain research presentation;
- custom illustration or interaction;
- restrained whimsy;
- deliberate imperfection.

The result should feel:

academic + literary + personal + handmade + quietly playful.

Do not directly reproduce another site's artwork, copy or layout.

---

# 3. Brand Positioning

Primary identity:

**Kavishni Nanayakkara**

Secondary identity:

**Economics Researcher**

Affiliation:

**Nanyang Technological University, Singapore**

Primary research theme:

**AI and Human Behaviour**

Suggested positioning language:

> Exploring AI and human behaviour through economics.

or:

> Economics research on AI, behaviour, and decision-making.

Do not overstate specialist research areas that have not yet been explicitly confirmed.

Do not imply academic credentials, degrees, or positions beyond the information provided.

---

# 4. Design Principles

## 4.1 Content first

Typography, research content, writing, and intellectual identity should dominate.

Photography is secondary.

Animation is tertiary.

Decorative UI is minimal.

The site must still look sophisticated if all animation and imagery are removed.

---

## 4.2 Editorial, not theatrical

Use:

- strong typographic scale;
- elegant serif headings;
- small uppercase or letter-spaced metadata where appropriate;
- long horizontal rules;
- asymmetric but controlled layouts;
- thoughtful whitespace;
- restrained image crops.

Avoid:

- oversized text covering entire screens;
- moving typography;
- scrolling marquees;
- excessive fade-in effects;
- parallax;
- scroll-jacking;
- cursor gimmicks;
- dramatic page transitions.

---

## 4.3 Sophisticated warmth

The site should feel inviting without becoming rustic, earthy, bohemian, botanical, or tropical.

Green should appear as a **deep intellectual accent**, not as a nature theme.

Warm colours should make the interface easier on the eyes rather than visibly “colourful.”

---

# 5. Colour System

Use a restrained warm-neutral palette.

### Primary background

**Warm Paper**  
`#F5F2E9`

Use as the dominant site background.

This should feel softer than pure white but remain visually clean.

---

### Alternate surface

**Soft Ivory**  
`#FCFBF8`

Use selectively for:

- editorial panels;
- image captions;
- small section changes;
- footer or content surfaces.

Do not create alternating colour-block sections everywhere.

---

### Primary text

**Deep Ink**  
`#202822`

Use for:

- body text;
- major headings;
- navigation;
- primary interface text.

This replaces pure black.

It contains a subtle green undertone without visibly appearing green.

---

### Primary accent

**Deep Forest**  
`#355244`

Use for:

- links;
- active navigation;
- focus states;
- selected editorial details;
- small graphical marks;
- interactive research visual.

Use sparingly.

This colour has strong contrast against the warm-paper background and may safely carry important link text.

---

### Darker accent

**Dark Forest**  
`#243B31`

Use occasionally where stronger contrast is required.

---

### Secondary text

**Muted Stone**  
`#5F625D`

Use for:

- dates;
- affiliations;
- metadata;
- captions;
- secondary descriptions.

Do not use extremely light grey text.

---

### Secondary decorative colour

**Muted Sage**  
`#AEBBAA`

Use only for:

- decorative backgrounds;
- subtle lines;
- nonessential interface elements;
- abstract graphical elements.

Do not use sage for important body text.

---

### Warm accent

**Muted Clay**  
Approximately `#B86F52`

Use extremely sparingly.

Possible uses:

- one node in an interactive graphic;
- tiny editorial markers;
- occasional hover embellishment.

Do not use clay for normal text because contrast is insufficient against the main background for small typography.

---

# 6. Typography

Typography should carry most of the site's personality.
Avoid fashionable product-design sans-serifs such as Inter. Inter should not
be included as a font choice or fallback anywhere in the site typography.

Use three restrained typographic roles:

1. Literary/editorial serif for identity and major headings.
2. Highly readable text face for prose.
3. System or monospace face for selected utility links, metadata and
   compact interface details.

Typography should feel authored rather than template-derived.

Do not turn the entire website into a developer/terminal aesthetic.

## Primary editorial serif

Preferred:

**Newsreader**

Use for:

- homepage name;
- H1;
- major page titles;
- editorial section headings;
- occasional short pull-lines.

Desired characteristics:

- literary;
- contemporary;
- scholarly without appearing traditional;
- highly readable;
- elegant rather than decorative.

Alternative serif fonts may be considered only if they preserve this quality.

---

## Sans-serif

Preferred:
**Work Sans**, with a system sans-serif fallback.
Use for:

- body copy;
- navigation;
- metadata;
- paper details;
- dates;
- links outside the homepage's primary editorial content;
- buttons;
- captions.

The serif/sans contrast should create the site's academic-editorial identity.

### Link typography exception

Links outside the homepage's primary editorial content may use a restrained
system monospace face to give utility links, metadata and small navigational
details a personal-web character.

Homepage content links should remain in the site's regular sans-serif or
editorial text face. They should not be rendered in monospace merely because
they are links.

---

## Typography hierarchy

Desktop targets:

Homepage display name:
approximately `clamp(3.8rem, 8vw, 7.5rem)` only if layout permits.

Page H1:
approximately `3.2–4.5rem`.

H2:
approximately `2–2.8rem`.

H3:
approximately `1.35–1.65rem`.

Body:
approximately `1.05–1.125rem`.

Metadata:
approximately `0.78–0.9rem`.

Body line-height:
approximately `1.65–1.75`.

Editorial serif headings should generally have tighter line-height.

Avoid very small text for stylistic purposes.

---

# 7. Layout System

Use generous but controlled whitespace.

Maximum global content width:

approximately `1180–1240px`.

Primary reading column:

approximately `680–760px`.

Research and list layouts may use wider widths where metadata appears alongside content.

Use CSS `clamp()` where useful for responsive spacing and typography.

Typical vertical spacing:

- major section separation: `6–10rem` desktop;
- subsection separation: `3–5rem`;
- mobile spacing reduced proportionally.

Use horizontal rules as a recurring structural device.

Prefer thin rules over boxes.

Avoid extensive card grids.

---

# 8. Navigation

The first version of the site is primarily a single-scroll homepage. The
homepage contains the main Hero, Research, Currently and About sections, with
navigation links scrolling to those sections. Speaking and Reading remain
part of the broader site structure and can be surfaced as standalone pages
when verified content is available.

Desktop navigation:

**Kavishni Nanayakkara** at left, linking to homepage.

Right-side navigation:

- About Me
- Research
- Speaking
- Writing
- Vitae
- Digital Garden

The Vitae link may point to a CV PDF when one is added.

Do not include a visible **Home** navigation item.

Do not place a large **Subscribe** button in the main navbar.

Substack subscription can be surfaced within Writing and the footer.

Navbar should:

- use a warm-paper background;
- remain visually quiet;
- use small-to-medium typography;
- avoid heavy shadows;
- use subtle active-state treatment;
- remain usable by keyboard;
- collapse cleanly on mobile.

Sticky navigation is acceptable if it remains unobtrusive.

---

# 9. Homepage

The homepage is the main editorial composition.

Use the following hierarchy.

## 9.1 Hero

Primary content:

**Kavishni Nanayakkara**

**Economics Researcher**

**Nanyang Technological University, Singapore**

Short intellectual positioning statement:

> Exploring AI and human behaviour through economics.

or similar.

Provide small text links:

- Research
- Writing
- About

Avoid large rounded CTA buttons.

### Portrait

Include one portrait when supplied.

Treatment:

- editorial rectangular crop;
- no circular headshot;
- no decorative frame;
- no heavy shadow;
- no gradient overlay;
- no floating animation.

The portrait should occupy approximately 30–40% of the hero at desktop widths.

Text should remain dominant.

On mobile, portrait moves underneath or between text sections.

---

# 10. Signature Research Interaction

Include a single optional interactive graphical element inspired conceptually by orbital/gravitational systems.

This should be the **only notable animated component on the site**.

Concept:

At the centre:

**AI × Human Behaviour**

Around it, a limited number of conceptual labels or abstract nodes.

Possible initial labels:

- Economics
- AI
- Behaviour
- Decision-making

Do not add unverified specialist research topics.

### Behaviour

Animation should be extremely subtle.

Use:

- slow orbital movement;
- slight hover displacement;
- gentle easing;
- very limited cursor influence.

Do not use:

- glowing particles;
- star fields;
- literal planets;
- dramatic solar-system graphics;
- 3D;
- WebGL unless absolutely necessary;
- strong physics effects;
- constant high-speed movement.

Preferred implementation:

**SVG + CSS + small vanilla JavaScript file.**

The visual should feel like a conceptual research diagram, not a game.

### Accessibility

If:

`prefers-reduced-motion: reduce`

then disable orbital motion entirely.

The component should become an attractive static research diagram.

All concepts should remain readable without hover.

The site must remain fully functional without JavaScript.

---

# 11. Selected Research Section

Immediately after the introductory portions, show a curated research section.

Do not use product-style cards.

Present projects like a sophisticated bibliography or journal contents page.

Example structure:

**Research title**

Short one- or two-sentence explanation.

Metadata:

`Working paper · 2026`

Optional links:

`Abstract →`  
`Paper →`  
`Slides →`  
`Code →`

Use horizontal rules between items.

If actual papers do not yet exist, use restrained placeholder structure rather than inventing projects.

Include:

**View all research →**

---

# 12. Location / Institutional Context

NTU should appear as professional context, not as the website's identity.

Acceptable uses:

- affiliation in hero;
- short biography;
- one carefully selected image;
- About page.

Do not:

- use NTU colours as the primary brand palette;
- use NTU logos prominently;
- create a campus-themed homepage;
- repeatedly mention NTU;
- make tropical vegetation a major visual motif.

If an NTU photograph is used, prefer:

- architecture;
- interior spaces;
- quiet campus scenes;
- research environments;
- restrained landscape photography.

Avoid cliché Singapore/tropical imagery.

One image is sufficient.

---

# 13. Writing Section

Substack remains the canonical publishing platform.

The website should curate selected or recent writing rather than duplicate the full publication system.

Homepage:

display approximately 3 selected essays.

Each entry:

**Essay title**

Short standfirst.

Date.

`Read →`

Writing page:

- short introduction;
- curated essays;
- optional categories only if useful;
- prominent but restrained link to Substack;
- optional Subscribe link.

No newsletter marketing language.

No email capture pop-up.

No intrusive subscription banner.

---

# 14. Speaking Page

Create `speaking.qmd`.

Purpose:

document talks, presentations, panels, interviews, podcasts, lectures, and public engagements.

Use chronological editorial formatting.

Example:

`2026`

**Event or talk title**

Organisation / conference  
Location or format  
Date

Optional:

`Slides →`  
`Watch →`  
`Listen →`

Include a short speaking-enquiries statement only when contact details are available.

Do not fabricate engagements.

---

# 15. Reading Page

Create `reading.qmd`.

This should feel like an intellectual notebook, not Goodreads.

Possible sections:

### Currently Reading

One or several current items with short notes.

### Recently

Recent books, papers, essays, or reports.

### Returning To

A deliberately small collection of influential or frequently revisited works.

Do not build a giant database initially.

Do not automate Zotero during the first implementation.

Manual curation is preferred.

---

# 16. About Page

Create a sophisticated but concise biography.

Hierarchy:

### Short professional biography

Economics researcher at Nanyang Technological University, Singapore.

Focus on AI and Human Behaviour.

### Research interests

Only verified interests.

### Background

Education/career details when supplied.

### Beyond research

Brief, understated reference to:

- reading;
- writing;
- hobbies;
- other interests.

This should humanise the researcher profile without turning the page into a lifestyle biography.

A second tasteful photograph may appear here.

---

# 17. Visual Asset Rules

Photography should be limited and intentional.

Target:

approximately **3–5 meaningful images across the entire core site**, excluding writing thumbnails if added later.

Suggested distribution:

- homepage portrait;
- one subtle NTU/location/context image;
- one secondary personal/editorial image;
- optional speaking image;
- optional About image.

Avoid:

- stock photography;
- decorative imagery with no narrative purpose;
- galleries on every page;
- image-heavy research cards;
- image backgrounds behind body text.

Image treatment:

- natural aspect ratios;
- rectangular;
- minimal cropping;
- no exaggerated rounded corners;
- no heavy filters;
- no strong colour grading;
- descriptive alt text.

---

# 18. Motion System

Motion should be almost imperceptible.

Allowed:

- subtle link underline transitions;
- modest colour transitions;
- slight opacity transitions;
- research orbit interaction;
- very mild image hover where useful.

Transition durations:

approximately `150–300ms` for interface states.

Research orbit may use considerably slower movement.

Avoid entrance animations for every section.

Do not animate content simply because it enters the viewport.

No scroll-jacking.

No parallax.

No animated navbar.

No continuously moving decorative text.

No auto-playing visual media.

---

# 19. Accessibility Requirements

Target **WCAG 2.2 AA** where reasonably achievable.

Requirements:

- sufficient foreground/background contrast;
- body text minimum approximately 16–17px;
- no essential information communicated solely by colour;
- visible keyboard focus states;
- semantic heading order;
- semantic HTML wherever possible;
- keyboard-accessible navigation;
- descriptive image alt text;
- no hover-only information;
- reduced-motion support;
- responsive zoom without layout failure;
- comfortable line lengths;
- adequate interactive target sizes;
- meaningful link labels.

Primary text colours should comfortably exceed AA contrast.

Deep Forest may be used for text links against Warm Paper.

Muted Sage and Clay should generally remain decorative.

Use underlines or another non-colour cue for inline hyperlinks.

---

# 20. Responsive Behaviour

Design desktop-first only conceptually; implementation must be genuinely responsive.

Breakpoints should be based on layout needs rather than device brands.

### Desktop

- asymmetric editorial compositions;
- occasional two-column layouts;
- portrait alongside hero text;
- generous whitespace.

### Tablet

- reduce display typography;
- collapse complex grids;
- retain editorial rhythm.

### Mobile

- predominantly single-column;
- images appear beneath relevant text;
- navigation collapses;
- orbital interaction becomes simplified or static;
- generous side padding;
- no horizontal scrolling;
- headings must not overflow viewport.

Mobile should feel deliberately designed rather than like a compressed desktop page.

---

# 21. Quarto Technical Architecture

Use a simple GitHub Flow deployment model.

**`main` branch**

contains the approved, editable Quarto source. Each website change should be
developed on a short-lived branch and merged into `main` through a pull
request after the `Build website` check passes.

**GitHub Actions**

renders the Quarto project and deploys the `_site/` artifact to GitHub Pages
when a pull request is merged into `main`. Pull requests build the site but do
not deploy it. The rendered website is not committed to a source branch.

Do not manually edit or publish to `gh-pages`. It is a legacy deployment
branch and may be retained only until the Actions deployment has been verified.

Suggested source structure:

```text
/
├── _quarto.yml
├── _brand.yml
├── styles.css
├── index.qmd
├── digital-garden.qmd
├── writing.qmd
├── speaking.qmd
├── reading.qmd
├── about.qmd
├── assets/
│   ├── images/
│   │   ├── portrait/
│   │   ├── editorial/
│   │   └── speaking/
│   └── js/
│       └── research-orbit.js
└── includes/
    └── optional reusable HTML fragments
```

Do not introduce unnecessary build tools.

Do not add React, Vue, Svelte, Node-based frontend frameworks, or a JavaScript package manager.

The site should remain fundamentally a **Quarto static website**.

The initial implementation should favour a single-scroll homepage over
duplicating empty sections across multiple pages. Standalone Speaking,
Reading and other pages should be introduced when they provide enough
verified content to justify them.

---

# 22. `_brand.yml`

Use Quarto brand configuration where appropriate to centralise:

- core colours;
- typography;
- foreground/background relationships.

Use CSS for more detailed page-specific styling.

The brand layer and CSS variables should agree rather than duplicate conflicting values.

Suggested CSS variables:

```css
:root {
  --paper: #F5F2E9;
  --ivory: #FCFBF8;
  --ink: #202822;
  --forest: #355244;
  --forest-dark: #243B31;
  --stone: #5F625D;
  --sage: #AEBBAA;
  --clay: #B86F52;

  --content-wide: 1200px;
  --content-reading: 720px;

  --rule: rgba(32, 40, 34, 0.18);
}
```

---

# 23. `_quarto.yml`

Configure:

- website title;
- site URL;
- navigation;
- footer;
- page metadata;
- social metadata;
- CSS;
- optional custom JavaScript;
- sensible page title behaviour.

Disable unnecessary UI.

Do not expose Quarto's default visual language more than necessary.

Do not show a table of contents globally by default.

TOC may be enabled selectively on long research/writing pages.

Do not add site search initially unless the amount of content later justifies it.

---

# 24. CSS Architecture

`styles.css` should be organised clearly.

Suggested sections:

```text
1. Design tokens
2. Global typography
3. Links and focus states
4. Navigation
5. Layout primitives
6. Homepage hero
7. Editorial section headers
8. Research lists
9. Writing lists
10. Speaking lists
11. Reading layout
12. Images and captions
13. Research orbit
14. Footer
15. Responsive breakpoints
16. Reduced-motion rules
17. Accessibility utilities
```

Global link styling should distinguish between homepage editorial links and
utility links elsewhere in the site. Monospace styling belongs on selected
utility links, metadata and compact interface details; it should not be
applied globally to every homepage link.

Avoid excessive `!important`.

Avoid overly specific selectors.

Use reusable classes.

Use semantic class naming.

---

# 25. Page Components

Create a small reusable component vocabulary.

Examples:

### `.eyebrow`

Small contextual label such as:

`SELECTED RESEARCH`

### `.section-rule`

Thin horizontal rule.

### `.editorial-list`

Reusable structure for research, writing, speaking.

### `.meta`

Dates, affiliations and publication types.

### `.text-link`

Text + arrow navigation.

### `.lede`

Larger introductory paragraph.

### `.image-caption`

Accessible editorial caption.

### `.currently-grid`

Compact structure for:

Researching  
Reading  
Writing

Components should remain subtle and typographic.

---

# 26. Homepage “Currently” Component

Include a compact section near the lower half of the homepage.

Possible items:

**Researching**  
AI and Human Behaviour

**Reading**  
Current book or paper

**Writing**  
Latest essay or topic

Do not include false placeholder content in production.

Design should resemble marginalia or an editorial notebook rather than dashboard cards.

---

# 27. Footer

Keep minimal.

Suggested contents:

**Kavishni Nanayakkara**

Economics Researcher

Links:

- Email
- GitHub
- LinkedIn
- Substack

Optional:

`Singapore`

Do not show a large site map.

Do not use social-media icon clutter if text links are clearer.

Include copyright year automatically if simple to implement.

---

# 28. Performance

The site should remain lightweight.

Requirements:

- optimise images;
- use modern image formats where practical;
- lazy-load below-fold images;
- minimise custom JavaScript;
- no heavy animation library;
- no unnecessary tracking scripts;
- no large background videos;
- avoid excessive webfont weights.

The custom interactive element should not materially delay first content paint.

Core content must render before JavaScript enhancement.

---

# 29. SEO and Metadata

Configure:

- descriptive site title;
- site description;
- canonical site URL;
- page-specific titles;
- page descriptions where appropriate;
- Open Graph metadata;
- social preview image when an appropriate asset exists.

Suggested site description:

> Kavishni Nanayakkara is an economics researcher at Nanyang Technological University, Singapore, interested in AI and human behaviour.

Do not add keywords or credentials that have not been confirmed.

---

# 30. Tone of Written Content

Copy should be:

- intelligent;
- concise;
- precise;
- warm but unsentimental;
- academically credible;
- free of personal-brand clichés.

Avoid phrases such as:

- “passionate about”;
- “thought leader”;
- “at the cutting edge”;
- “driven by curiosity” unless context genuinely justifies it;
- exaggerated claims about research impact.

Prefer concrete descriptions of work and interests.

---

# 31. Explicit Design Guardrails

Do **not** implement:

- heavy Bootstrap cards;
- gradients;
- glassmorphism;
- giant pill buttons;
- excessive rounded corners;
- drop shadows on every component;
- neon colours;
- dark mode in version 1;
- auto-playing media;
- animated backgrounds;
- decorative particles;
- scrolling marquees;
- typewriter effects;
- full-screen splash pages;
- cursor replacement;
- excessive hover transformations;
- parallax;
- page transition libraries;
- elaborate loading screens;
- tropical illustration;
- botanical ornamentation;
- NTU-themed branding;
- large institutional logos;
- generic academic stock photos.

---

# 32. Desired Emotional Result

The visitor should experience the site as:

**calm**  
**serious**  
**cultivated**  
**thoughtful**  
**contemporary**  
**warm**  
**precise**  
**quietly distinctive**

Not sterile.

Not corporate.

Not whimsical.

Not trendy for trend's sake.

Not aggressively minimal.

The site should feel as though careful editorial decisions have been made, but very little is demanding attention.

---

# 33. Priority Hierarchy

When design choices conflict, prioritise in this order:

1. Research credibility
2. Readability and accessibility
3. Content clarity
4. Typographic quality
5. Editorial sophistication
6. Performance
7. Visual imagery
8. Animation

Animation must never compromise any higher priority.

---

# 34. Implementation Sequence

Build in this order:

1. `_brand.yml`
2. `_quarto.yml`
3. global CSS design system
4. navigation and footer
5. homepage typography/layout
6. research page
7. writing page
8. speaking page
9. reading page
10. about page
11. responsive refinements
12. accessibility audit
13. photography integration
14. research-orbit enhancement
15. metadata/SEO
16. final mobile testing

The site should already look complete before step 13.

Photography and animation are enhancements, not structural dependencies.

---

# 35. Acceptance Criteria

The implementation is successful when:

- the first impression clearly communicates **Kavishni Nanayakkara — Economics Researcher**;
- the site mentions Nanyang Technological University without feeling institutionally branded;
- no PhD status is implied;
- AI and Human Behaviour is clearly visible as the research focus;
- typography provides most of the visual identity;
- the palette feels warm, sophisticated and easy on the eyes;
- green feels refined rather than botanical;
- imagery is secondary to content;
- animation is noticeably less prominent than on typical editorial/design portfolio sites;
- only one meaningful interactive feature exists;
- research presentation resembles scholarly/editorial listings rather than product cards;
- the site remains attractive with JavaScript disabled;
- reduced-motion users receive a complete static experience;
- keyboard navigation is usable;
- colour contrast meets accessibility goals;
- mobile presentation feels intentional;
- the site remains recognisably Quarto in maintainability but not visually like a default Quarto template;
- future research papers, writing, talks and reading entries can be added without redesigning the site.
- the initial public experience works as a coherent single-scroll homepage;
- homepage editorial links retain the regular site text treatment;
- monospace link styling is limited to selected utility links outside the
  homepage's primary editorial content;
- Inter is not used as a font or fallback.

---

# 36. Final Generation Instruction

Using this specification, generate the complete Quarto source implementation for the website.

The implementation should include:

- `_brand.yml`;
- revised `_quarto.yml`;
- revised `styles.css`;
- `index.qmd`;
- `research.qmd`;
- `writing.qmd`;
- `speaking.qmd`;
- `reading.qmd`;
- `about.qmd`;
- optional lightweight `assets/js/research-orbit.js`;
- clearly identified placeholder paths for portrait and editorial photography.

Use placeholders only where user-specific content or images have not yet been provided.

Do not invent research publications, qualifications, talks, educational history, hobbies, awards, or professional experience.

Where information is missing, preserve a clean structure that can be populated later rather than displaying obvious lorem ipsum or fake content.

Preserve the Quarto/GitHub Pages workflow:

**temporary branch → pull request → `main` → GitHub Actions → GitHub Pages**

The completed implementation should prioritise sophisticated typography, clarity, accessibility, restraint, and long-term maintainability over novelty.
