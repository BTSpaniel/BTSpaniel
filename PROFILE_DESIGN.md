# Profile design notes

## Direction

Particle Realms is the shared foundation, not a collection of unrelated projects. Keep Hans / snaHt. visible, lead with Navi-inspired cyan geometry, and make the engine, WebGPU OS, Playground, and Academy easy to reach.

The new mark is an original, simplified vector interpretation of the Navi cube, with the same five-square arrangement on every face. It is branding artwork, not an engine screenshot. Existing assets in this repository were preserved, not deleted.

## Choices

- Locally stored SVG artwork; no external badge/stat servers, counters, trackers, scripts, or fonts.
- Separate desktop/mobile compositions and light/dark assets selected with `picture`.
- Real headings, descriptive link names and image alternatives. Optional depth uses native `details` elements.
- Soul populations, generations, training and checkpoints are described as research goals, not finished capabilities.
- Native GitHub source activity is linked instead of fabricating or duplicating contribution statistics.

## References researched

- [GitHub: accessible profile READMEs](https://github.blog/developer-skills/github/5-tips-for-making-your-github-profile-page-accessible/)
- [GitHub: light/dark Markdown images](https://github.blog/developer-skills/github/how-to-make-your-images-in-markdown-on-github-adjust-for-dark-mode-and-light-mode/)
- [Anthony Fu's profile source](https://github.com/antfu/antfu): restrained navigation.
- [Caneco's profile source](https://github.com/caneco/caneco): concise personal positioning and concrete work.
- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme): comparison across minimal, graphical and badge-heavy approaches.

## Review and validation

Three local visual iterations addressed mobile typography, card spacing, compact copy, uniform cube geometry, light-theme contrast and restrained glow. Scores are subjective self-reviews, not independent artist evaluations or measured quality percentages.

| Stage | Art | Design |
|---|---:|---:|
| Initial text/badge README | 5.0/10 | 6.0/10 |
| First local composition | 8.6/10 | 8.4/10 |
| Mobile/spacing revision | 9.2/10 | 9.2/10 |
| Final local composition | 9.5/10 | 9.5/10 |

Chromium local GitHub-style previews were exercised at 320, 390, 768, 1024 and 1440 CSS pixels in both themes. Image loading, variant selection, horizontal overflow, mouse and keyboard disclosure controls passed. All 20 new SVGs parse and their text bounds fit; all 20 README image references resolve locally. Selected foreground/background pairs have a minimum contrast of 6.12:1.

**Limit:** this is a GitHub-style preview, not GitHub's renderer. Live GitHub browser navigation was blocked in the execution environment. Local checks do not prove GitHub sanitization, image-proxy behavior or the final live profile layout. Application links were inspected as web/documentation resources; this is not a GPU runtime audit of the engine or OS.

A newer profile revision was discovered during the final repository check. Its population target, creative-workbench scope and useful links were retained, and the final changes are based on that newer commit rather than the earlier README snapshot.
