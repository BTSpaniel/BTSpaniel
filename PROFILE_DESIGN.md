# Profile design notes

## Current direction

Particle Realms is one shared foundation for the engine, creative tools, simulation, connected worlds, and AI research. Keep **Hans / snaHt.** visible and lead with the existing blue-glass Navi artwork, not a replacement logo. The public profile is an invitation into the project, not a catalogue of unverified claims.

The banner reuses the supplied **Holographic Cyan Cube HUD** artwork. It is cropped, resized, and embedded as WebP inside two SVG compositions. The card schematics are decorative illustrations, not screenshots or output from the engine.

## Active presentation

- `assets/hero-desktop.svg` and `assets/hero-mobile.svg`: separate compositions selected with `picture`. The midnight-blue brand banner stays dark in both page themes.
- `assets/engine-card.svg`, `assets/os-card.svg`, `assets/playground-card.svg`, and `assets/academy-card.svg`: matching project cards with internal light/dark color palettes and narrow-width typography rules.
- One primary launch link, then source/download links. Native source activity is linked rather than recreated with a third-party statistics service.
- Real text headings and image alternatives. Native `details`/`summary` controls keep the research and workbench readable without a wall of text.
- Soul populations, generational learning, CPU/GPU parity, model training, and checkpoints remain qualified as research or validation goals.
- No external fonts, JavaScript, visitor counters, analytics, remote badge servers, or statistics widgets.

Earlier SVG variants remain in the repository. They are historical assets and are not referenced by the current README. Useful architecture, source-activity, population-target, and workbench details from the newer `197e903` profile revision were retained.

## Research references

- [Anthony Fu](https://github.com/antfu): direct navigation with little introductory clutter.
- [Cassidy Williams](https://github.com/cassidoo): personal voice and concrete things to explore.
- [Sindre Sorhus](https://github.com/sindresorhus): a short, recognizable introduction rather than a long skills catalogue.
- [GitHub: responsive profile images](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)
- [GitHub: collapsed sections](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections)

These are references for hierarchy and usability, not sources of copied artwork or a template.

## Self-review record

The scores below are subjective visual/editing judgments. They are not independent artist evaluations, measured quality percentages, or a rating of the engine itself.

| Pass | Art | Design | Main revision |
| --- | ---: | ---: | --- |
| Starting illustrated profile (`7323f3d`) | 8.4/10 | 8.0/10 | Clear identity, but label-like cards and small-screen hierarchy gaps |
| Local composition 1 | 9.1/10 | 9.0/10 | Existing Navi artwork, bespoke schematics, mobile banner |
| Local composition 2 | 9.4/10 | 9.3/10 | Recentered artwork, preserved highlights, corrected gradient, cleaner phone navigation |
| Local composition 3 | 9.5/10 | 9.5/10 | Theme-aware cards, larger small-screen support text, retained architecture and activity links |

## Verified locally

**229 checks passed, 0 failed.** The checks cover six SVGs, embedded-logo decoding, repository-local image references, descriptive alternatives, static/no-script assets, overflow, responsive hero selection, keyboard disclosure controls, enlarged text, SVG text bounds, and selected foreground/background contrast pairs.

Chromium exercised the GitHub-style preview at **320, 360, 390, 430, 640, 768, 980, 1024, 1280, and 1440 CSS pixels**, in both light and dark page themes. The preview uses an approximation of GitHub styling. All five displayed images decoded at every tested width and theme. The active artwork plus README is about **45 KB** before compression; historical unused assets are not included in that count.

## Verification boundary

**Live github.com rendering was not verified in the screenshot browser:** navigation was blocked by the execution environment. The local tests do not certify GitHub's sanitizer, image proxy, manual theme settings, or final native layout. A successful repository write and blob verification establish that the tested source was published, not that every client displays it identically.

No GPU/runtime audit of Particle Realms or WebGPU OS was performed as part of this profile design review. External destination uptime and full accessibility conformance are not claimed.
