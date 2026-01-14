# The Open Agentic AI Foundation

A static website presenting the Open Agentic AI Foundation, its mission, strategic pillars, programs, member organizations, and community resources. The site includes a home page and an about page with consistent navigation, content sections, and language switching.

## Overview

The foundation is presented as a global coalition advancing safe, open, and interoperable agentic AI through shared standards, funding, and governance. The site highlights a public roadmap, community participation, and multi-region programs.

## Home Page Content (index.html)

- Hero: mission statement, primary calls to action, and key metrics.
- Live timeline: quarterly milestones for safety benchmarks, interoperability standards, and global summits.
- Mission: open protocols, safety and assurance, and inclusive governance.
- Strategic pillars: infrastructure (reference architecture), standards (interoperability and trust), and impact (ecosystem programs).
- Programs: 2024-2025 initiatives such as the Open Agent Safety Benchmark, Interoperability Lab, Global Builder Summits, and the Open Impact Fund.
- Members: founding organizations (AWS, Anthropic, Block, Bloomberg, Cloudflare, Google, Microsoft, OpenAI).
- Community: open and neutral governance, safety-first practices, and global access.
- Resources: roadmap, community forum, and grant programs.
- Call to action: join the coalition or browse resources.

## About Page Content (about.html)

- Foundation overview and mission.
- Strategic pillars (charter) and member organizations.
- Resources section for roadmap, community, and funding links.

## Internationalization

The site uses data attributes (`data-i18n`) and a language switcher. Translations live in `assets/js/app.js` and are persisted in `localStorage` under the key `oaif-lang`. Supported languages include English, Simplified Chinese, Traditional Chinese, Japanese, and French.

## Project Structure

- `index.html`: Home page.
- `about.html`: About page.
- `assets/css/style.css`: Global styles.
- `assets/js/app.js`: Language switching, smooth scroll, and navigation state.

## Local Preview

Open `index.html` directly in a browser, or serve the directory with any static file server.

## License

MIT. See `LICENSE`.
