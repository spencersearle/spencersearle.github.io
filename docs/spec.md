# spencersearle.github.io: portfolio v1

Decided 2026-10-12 in a brainstorming session.

## Purpose

1. A link for the resume that shows finished work in one place.
2. A permanent home for app privacy policies and support pages, so new apps stop needing their own one-off repos.

## Scope of v1

- **Home page** (`index.html`): hero, five projects, a short about section, contact.
  - Projects, in order: Monolito Truco, Quantum Fence Builder, Connect, Plaite, AIC capstone.
  - In-progress and smaller builds are left off on purpose.
- **Connect pages**: `connect/privacy/` and `connect/support/`. These are the URLs App Store Connect will point at.
- **404 page**.
- Resume: a slot exists in the markup but is not linked until a PDF is chosen.

Out of scope: project detail pages, a blog, analytics, a custom domain, moving Quantum's privacy policy (a later step, which also means updating its URL in App Store Connect and Play Console before archiving `quantum-fence-privacy`).

## Design: "Editorial" (direction A)

- Warm paper background (`#F6F3EC`), near-black ink, one accent (`#7A3B2E`), plus a dark theme that follows the system setting.
- Newsreader (serif) for headings, Inter Tight for body text, JetBrains Mono for small uppercase metadata.
- The work section is a numbered index: number, title and description, then right-aligned platform and status.
- Plain static HTML and one stylesheet. No framework and no build step, so GitHub Pages serves it as-is.
- Works down to a 360px phone width.

## Copy

The hero is option 3 from the session ("I build apps for real people..."). A placeholder Spencer wants to rewrite himself. All copy follows the `spencers-voice` practical register.

## Not live

No GitHub repo exists yet and Pages is off. Going live means creating a **public** repo named exactly `spencersearle.github.io` and pushing. Only on Spencer's explicit go.

## Before going live, check

- Contact email is the one he wants public.
- LinkedIn URL added (or left off).
- Intro rewritten.
- Plaite and AIC descriptions are at a level of detail he is comfortable making public.
