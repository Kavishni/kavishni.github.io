# Kavishni Academic Website

This repository contains the Quarto source for
https://kavishni.github.io.

## Source of truth

Before making design or frontend decisions, consult:

docs/site-design-spec.md

Treat that document as the authoritative design specification.

## Content source of truth

Factual information about Kavishni and her work is stored in:

content/

Before writing or revising website copy, consult the relevant files there.

Content files are the factual source of truth.

You may:
- rewrite for clarity;
- shorten;
- reorganise;
- adapt tone to the site's design.

You may not:
- invent facts;
- infer credentials;
- invent publications or research findings;
- invent talks;
- invent education or employment;
- turn tentative interests into claimed expertise.

If information is missing, omit it rather than fabricate it.

Homepage updates must come from content/updates.md.

## Architecture

This is a Quarto static website.

Do not introduce:
- React
- Vue
- Svelte
- Node-based frontend frameworks
- npm dependencies
- JavaScript frameworks
- unnecessary build tooling

Prefer:
- Quarto
- semantic HTML
- CSS
- minimal vanilla JavaScript

## Git and publishing

main = editable Quarto source
gh-pages = generated published website

Never manually modify gh-pages.

Do not run `quarto publish gh-pages` unless I explicitly ask you to publish.

## Content integrity

Do not invent:
- publications
- qualifications
- degrees
- research projects
- talks
- awards
- employment history
- hobbies
- biographical details

Use restrained structure or placeholders where information is unavailable.

Do not describe Kavishni as a PhD student, PhD candidate, or doctoral researcher.

## Development process

Make changes incrementally.

For substantial changes:
1. inspect the existing implementation;
2. explain what you intend to change;
3. change only the requested phase;
4. run an appropriate Quarto render/check;
5. report which files changed and why.

Do not redesign unrelated parts of the site.

Keep the implementation readable for a beginner learning HTML, CSS, Quarto, Git, and JavaScript.

## Design priorities

When requirements conflict, prioritize:

1. research credibility
2. accessibility and readability
3. content clarity
4. typography
5. editorial sophistication
6. performance
7. imagery
8. animation

Animation must never compromise a higher priority.

## Visual character

The site should feel personally authored rather than like a generic
AI-generated portfolio.

Consult the Personal Web, typography, bracket-link, anti-template and
signature-graphic requirements in docs/site-design-spec.md before making
frontend design decisions.

Prefer:
- typography;
- ordinary text links;
- simple HTML;
- bespoke details;
- mild idiosyncrasy;
- a small number of individually designed elements.

Avoid generic component-library and AI-template aesthetics.

Do not directly imitate another researcher's website.

## Accessibility

Preserve:
- semantic headings
- keyboard accessibility
- visible focus styles
- readable text sizing
- WCAG-oriented contrast
- reduced-motion support
- meaningful link text
- responsive layouts

## Dependencies

Do not install a new package or dependency without explaining why it is necessary and asking first.