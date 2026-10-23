# Anatomesh · 3D 解剖跑台測驗 (3D Anatomy Practical Quiz)

**A free, browser-based 3D anatomy "spotter" exam in Traditional Chinese + English** — bones, muscles and peripheral nerves. Practise identifying structures on interactive 3D models — no install, just open the page.

**免費的網頁版 3D 解剖跑台練習系統（繁體中文＋English）**：骨頭、肌肉、周邊神經。在可旋轉的 3D 模型上練習辨認構造，免安裝。

▶ **Live / 線上使用：** [`https://jason355.github.io/anatomesh/`](https://jason355.github.io/anatomesh/
)


## Modules / 模組
| Page | Content 
|---|---|
| `index.html` | Landing page (module menu, per-module score history) |
| `src/bones.html` | 3D bone quiz — skull, spine, thorax, girdles, limbs; foramina, joints, ligaments |
| `src/muscles.html` | 3D muscle quiz — 60 Lab-list muscles: name, locate, origin, insertion, action, nerve supply, compartment |
| `src/nerves.html` | 3D peripheral-nerve quiz — cervical, brachial, lumbar and sacral plexuses (16 Lab-list nerves + 22 lecture branches): name, locate, roots, plexus, origin in brachial plexus, muscles supplied, cutaneous area, course, injury |
| *(next)* | Cranial nerves / CNS |

## Features
- Exam (timed), practice (instant feedback) and Explorer modes; lenient typo grading with a correction note
- Free 360° rotation (drag), zoom (wheel), pan (right-drag); **R** resets the view
- **Shuffled, non-repeating question deck** (Fisher–Yates): every question in the selected scope is asked once before any repeats; progress is saved in your browser (`localStorage`), wrong answers come back a few cards later
- Muscles: overlying muscles are automatically "dissected" away so the target is visible; origin (blue) and insertion (green) areas are shown on reveal
- Nerves: the target nerve is highlighted orange-red among pale-yellow neighbouring nerves (with an X-ray overlay so short branches stay visible); the muscles it supplies appear on reveal; click or hover a nerve in Explorer mode to identify it
- **Phone friendly:** icon-only top bar, a collapsible bottom sheet for questions (side panels in landscape), a list drawer in Explorer mode, larger touch targets; one file per module adapts to the screen size
- Each page is a single self-contained HTML file (bones ≈22 MB, muscles ≈10 MB, nerves ≈8 MB); needs a desktop browser with WebGL

## Files
`index.html`, `src/bones.html`, `src/muscles.html`, `src/nerves.html`, `.nojekyll`, `LICENSE`, `README.md`, `docs/` (NOTICE.md, MUSCLE_DATA.md, NERVE_DATA.md, COVERAGE.md).

## Credits
3D models are derived from **[BodyParts3D](https://lifesciencedb.jp/bp3d/)** (© The Database Center for Life Science, CC BY-SA 2.1 Japan; bones) and **[Z-Anatomy](https://www.z-anatomy.com/)** (CC BY-SA 4.0; muscles, ligaments, menisci, origin/insertion areas, nerve/vessel paths). Both were modified for this project (re-registered, smoothed, simplified). Details: [NOTICE.md](docs/NOTICE.md).

## License
Shared under **CC BY-SA 4.0** — see [LICENSE](LICENSE) and [NOTICE.md](docs/NOTICE.md). For study purposes only; not for clinical or medical use. Muscle and nerve data (origin/insertion/action/innervation; nerve roots/course/supply/injury) are written from standard anatomy references and the course lecture — see [MUSCLE_DATA.md](docs/MUSCLE_DATA.md) and [NERVE_DATA.md](docs/NERVE_DATA.md) and verify against your course material.
