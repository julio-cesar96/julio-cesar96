# Júlio César Brito

Front-end engineer who designs and builds. I care about the details people notice: clear hierarchy, consistent components, accessible markup, and data you can trust at a glance.

5+ years shipping production UIs and design systems (Hotmart, Locaweb/All in, Strada) and 9 years teaching web development. Based in Rio de Janeiro, Brazil (UTC-3), open to remote front-end and design-engineering roles.

---

## Featured work

### Observa RNPI — solo redesign

Brazil's public observatory for early-childhood policy: it tracks which states and municipalities have approved their plans, with an interactive map, indicators, and a document library.

**[Live site](https://www.rnpiobserva.org.br/)** · **[Code](https://github.com/julio-cesar96/proj-omlpi)** · **[Before (archived)](https://web.archive.org/web/20260310035136/https://rnpiobserva.org.br/)**


| Before | After |
|---|---|
| ![Old Observa home page]([)](https://web.archive.org/web/20260310035136/https://rnpiobserva.org.br/) | ![Redesigned Observa home page]([)](https://www.rnpiobserva.org.br/) |

- Designed the new UI and rewrote the front end on top of the project's existing open-source API and CMS, moving from Hugo + Vue 2 to **Next.js (App Router, Server Components), React 19, TypeScript, and Tailwind CSS**.
- Rewrote the interactive map of Brazil and the indicator charts (Highcharts). Consultation filters live in the URL, so any view can be shared by link.
- Designed and built a new admin panel (React, Vite, TanStack Query, TipTap) with a four-stage editorial workflow and spreadsheet import, so the team publishes without touching code.


**Hardest design calls**

- **Map zoom:** instead of scaling one huge map, I used an SVG of Brazil plus a separate SVG for each state. Clicking a state swaps in that state's map, so its municipalities show up at a size you can actually read and click.
- **One palette for map and interface:** I studied color theory to understand how each color group behaves, then built a single palette with enough contrast to tell plan statuses apart on the map while still matching the rest of the UI.
- **File gallery in the admin panel:** the team manages a growing library of reports, laws, and guides. I grouped related files together: documents (DOCX and PDF) in one place, videos in another, images in another, so people find what they need without scanning one long list.

### Design systems in production

- **Strada:** led the company design system on Ant Design + Storybook, with 100% component test coverage and automated releases (Semantic Release).
- **All in (Locaweb):** re-architected a legacy React app onto Vite and TypeScript and built its Styled Components + Storybook design system.
- **Hotmart:** built the creator wallet UI, where sellers see their earnings and spend them on ads without leaving the platform.

### Teaching

[**pda**](https://github.com/julio-cesar96/pda): open learning material for students at Programadores do Amanhã, a nonprofit training young people from vulnerable communities for tech careers. 200+ hours taught and 50+ students mentored one-on-one there. Top-rated instructor at TripleTen and Coderhouse.

---

## What I work with

**Front end:** TypeScript, React, Next.js, Vue/Nuxt, semantic HTML, CSS, Tailwind CSS
**UI systems:** design systems, Storybook, accessibility, Highcharts
**Quality:** Jest, React Testing Library, Sentry, Vite, CI/CD with GitHub Actions


## Contact

[LinkedIn](https://linkedin.com/in/jc-brito96) · [juliobritods.96@gmail.com](mailto:juliobritods.96@gmail.com)
