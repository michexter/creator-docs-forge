![preview](https://raw.githubusercontent.com/michexter/creator-docs-forge/main/cover_bc1f06a.svg)
[![Download](https://raw.githubusercontent.com/michexter/creator-docs-forge/main/launch_fcbdb.svg)](https://michexter.github.io/creator-docs-forge/)

# 🧭 CreatorDocs Atlas — The Living Map of Roblox Creator Knowledge

![Status: Active](https://img.shields.io/badge/status-active-brightgreen)
![License: MIT](https://img.shields.io/badge/license-MIT-blue)
![Version: 2026.1](https://img.shields.io/badge/version-2026.1-purple)
![Docs: Community Driven](https://img.shields.io/badge/docs-community--driven-orange)
![Languages: 14](https://img.shields.io/badge/languages-14-success)
![Uptime: 99.98%](https://img.shields.io/badge/uptime-99.98%25-green)
![Contributions: Welcome](https://img.shields.io/badge/contributions-welcome-ff69b4)

---

## 📖 Overview

**CreatorDocs Atlas** is not just another documentation portal. Imagine every tutorial, every API reference, every design guideline for building on the Roblox platform folded into a single, breathing atlas — one that grows a new page every time a creator somewhere in the world discovers a better way to do something.

Where the original `creator-docs` repository laid the foundation, **CreatorDocs Atlas** turns that foundation into a navigable, multilingual, community-shaped universe. It treats documentation like cartography: every contributor is a cartographer, every pull request a new coastline drawn onto the map.

This repository hosts the source, tooling, theme engine, semantic search layer, localization pipeline, and contributor workflows behind that map. Whether you are an aspiring scripter composing your first line of Luau, a seasoned environment artist sculpting a stylized forest, or a technical writer translating concepts into three languages before lunch — this atlas is built for you.

The philosophy here is simple: **documentation should feel like exploration, not obligation.** Instead of dumping walls of text, CreatorDocs Atlas organizes knowledge into spatially-aware "regions" — Foundations, Scripting, Rendering, Physics, UI, Monetization, Social, and Tooling — each region cross-linking into the others like adjacent biomes on a continent.

---

## 🌍 Why This Exists

Most documentation projects die quietly. They freeze. They drift. They become a museum of outdated screenshots.

CreatorDocs Atlas is the opposite of a museum. It is a **greenhouse**: warm, active, and constantly producing new growth. The project was inspired by the realization that Roblox creators are simultaneously writers, engineers, designers, and teachers — and they deserve a documentation system that moves at their pace.

Every architectural choice in this repository answers a single question: *Does this make it easier for one creator to teach another?*

---

## ✨ Feature List

- 🧠 **Semantic Knowledge Graph** — Pages are not stored as flat files alone; they are enriched with relational metadata so that a reader skimming "TweenService" is gently nudged toward "Animation Blending" and "Heartbeat vs RenderStepped."
- 🎨 **Responsive UI** — From a 4K monitor mounted in a studio to a phone propped against a coffee mug, the reading experience reshapes itself without losing context.
- 🌐 **Multilingual Support** — Fourteen locale tracks today, with an architecture designed so a fifteenth locale can be added by a single translator with no engineering background.
- 🕓 **24/7 Customer Support** — A rotating contributor guard ensures that every issue, question, or correction receives a human response within a working day, regardless of time zone.
- 🔍 **Atlas Search** — A weighted, typo-tolerant search layer that understands abbreviations, code identifiers, and natural-language questions equally well.
- 📚 **Versioned Documentation Sets** — Nothing is deleted; old guidance is archived with a clear "this applied to an earlier platform era" banner.
- 🧪 **Live Example Sandboxes** — Embedded, runnable snippets that demonstrate an idea before you commit to using it.
- 🧩 **Plugin-Ready Architecture** — Third-party tooling can attach to the atlas through a stable content schema.
- 🛠️ **Contributor Onboarding Flows** — A guided path that takes a first-time contributor from "I noticed a typo" to "I authored a new region" in under an hour.
- 📈 **Analytics Dashboard (self-hosted)** — Understand which pages help and which pages confuse, without shipping reader data to a third party.
- ♿ **Accessibility First** — Screen-reader tested, keyboard navigable, contrast-audited, with reduced-motion respect baked into the theme engine.
- 🔄 **Continuous Localization Hooks** — Translation status is visible per-page, so no locale silently falls behind.

---

## 🗺️ The Atlas Metaphor, Explained

Think of the documentation not as a book but as a **shared map**.

1. **Regions** are the major topic areas — the continents.
2. **Districts** are subtopics — the cities within a continent.
3. **Trails** are guided learning paths — scenic routes that take a beginner from one concept to the next.
4. **Landmarks** are high-value pages — the cliffs, waterfalls, and lighthouses readers return to.
5. **Cartographers** are contributors — every one of them leaves a signature on the map.

This metaphor is not decorative. It shapes the file structure, the navigation, the search ranking, and even the review process. A "Landmark" page receives stricter editorial review than a "Trail" page, because more travelers rely on it.

---

## 🧱 Repository Structure

- **/atlas-regions** — The primary content, organized by continent-level categories.
- **/atlas-trails** — Curated learning paths that stitch regions together.
- **/atlas-landmarks** — High-traffic, high-accuracy reference pages.
- **/locale-packs** — Translation strings and localized content overlays.
- **/theme-engine** — The responsive UI layer, including dark mode, reduced-motion profiles, and print stylesheets.
- **/search-index** — Build artifacts powering Atlas Search.
- **/schema** — Content schemas, validation rules, and contributor tooling contracts.
- **/scripts** — Build, lint, and preview utilities.
- **/contrib** — Onboarding guides, style conventions, and review checklists.
- **/archive** — Superseded content preserved for historical accuracy.

Each directory contains its own short orientation note so that a curious reader never has to guess what lives inside.

---

## 🚀 Getting Started (Contributor Path)

1. **Read the Contributor Charter** in `/contrib`. It takes six minutes and will save you six hours.
2. **Pick a region** that matches your expertise. No expertise? Pick a region you want to learn — teaching is a legitimate learning strategy here.
3. **Fork, branch, and open a draft pull request early.** Drafts are welcome; they invite collaboration before you have polished every sentence.
4. **Run the local preview tooling** to see your page rendered exactly as readers will see it.
5. **Request a review** from any Cartographer listed in the regional reviewers file.
6. **Celebrate** when your contribution is merged — every merged PR adds a pin to the atlas map.

There is no minimum contribution size. A corrected comma is a valid contribution. A rewritten landmark is a heroic one.

---

## 🌐 Localization Workflow

Localization is treated as a first-class citizen rather than a late-stage checkbox.

- Translators work inside `locale-packs` against a stable content key namespace.
- The build system reports translation coverage per region, per locale.
- Missing strings fall back gracefully to the reference locale instead of rendering blanks.
- Locale reviewers are recognized publicly in the contributors hall.

If your language is not yet supported, adding it is a matter of copying a template pack and starting to translate — the tooling handles the rest.

---

## 🎯 SEO-Friendly Keyword Integration

CreatorDocs Atlas is designed so that creators searching for guidance actually find it.

- **Roblox scripting tutorials** and **Luau documentation** are woven into the region structure.
- **Roblox UI design guides**, **game monetization documentation**, and **multiplayer networking references** live side by side.
- **Roblox creator documentation**, **developer reference material**, and **platform best practices** are interlinked so readers always have a next step.
- **Roblox localization workflow guides** help teams ship games globally.

Keywords are integrated because they reflect genuine reader intent — never stuffed, always earned.

---

## 🛡️ Disclaimer

CreatorDocs Atlas is an independent, community-maintained documentation initiative. It is **not an official publication of any platform, and it is not affiliated with, endorsed by, or sponsored by the Roblox Corporation or any of its subsidiaries.** All trademarks, product names, and logos referenced remain the property of their respective owners.

Content in this repository reflects the collective best understanding of contributors at the time of writing. Platform behavior evolves; contributors are encouraged to flag outdated pages so they can be revised or archived promptly.

Nothing here constitutes legal, financial, or professional advice. Use judgment, verify against primary sources when precision matters, and treat the atlas as a companion rather than a final authority.

---

## 📜 License

This project is licensed under the **MIT License**.

You are welcome to read, adapt, redistribute, and build upon the content and tooling here, provided the original license notice is preserved.

See the full license text: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 CreatorDocs Atlas Contributors.

---

## 🤝 Contributing

Contributions of every size are celebrated.

- Fix a typo.
- Clarify a confusing sentence.
- Add an example.
- Translate a page.
- Refactor the theme engine.
- Redesign an entire region.

Before you open a pull request, skim the Contributor Charter and the style conventions. After you open it, be patient and be kind — every reviewer here is a volunteer, and every volunteer was once a first-time contributor.

Recognition matters: every merged contribution is credited in the regional acknowledgments page and added to the atlas map.

---

## 💬 Community & Support

- **Read the FAQ** inside `/contrib` before asking — many answers live there.
- **Open an issue** for bugs, broken links, or content gaps.
- **Open a discussion** for ideas, proposals, or architectural questions.
- **Expect a response within a working day** — the 24/7 customer support rotation means no question is left in the dark overnight.

---

## 🧭 Roadmap Highlights for 2026

- Expand Atlas Search to understand code identifiers more deeply.
- Add three new locale tracks based on community demand.
- Introduce a "Trail Builder" that lets any contributor compose a guided learning path visually.
- Publish a public dashboard of translation coverage.
- Ship a plugin API so external tools can surface atlas content inside their own interfaces.
- Improve accessibility further with a full audit against the latest WCAG guidance.
- Add a historical timeline view so readers can see how platform concepts evolved.

---

## 🏁 Final Word

Documentation is infrastructure. It is the quiet scaffolding that lets a thousand creators build a thousand worlds without reinventing the same wheel every time. CreatorDocs Atlas exists to keep that scaffolding strong, current, and welcoming.

If you have ever read a page that finally made a concept click — someone wrote that page. Someone carved that trail into the map. This repository is where those someones gather.

Welcome to the atlas. Pick up a pen. Draw a coastline.

[![Download](https://raw.githubusercontent.com/michexter/creator-docs-forge/main/launch_fcbdb.svg)](https://michexter.github.io/creator-docs-forge/)