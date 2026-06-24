# Adam Obuchowicz
Senior Software Engineer & Team Lead — Rust, C++
Opole, Poland — open to remote / hybrid (Wrocław–Katowice)

📧 obuchowiczadam@gmail.com · 🔗 [LinkedIn](https://www.linkedin.com/in/adam-obuchowicz-7b9513413/), [GitHub](https://github.com/farmaazon)

### Selected work
[Enso](https://github.com/enso-org/enso) — open-source data-analysis platform built around a dual-representation (text <-> graph) programming language. I&nbsp;authored a large part of the Rust IDE:
- Primary author (~60–82% by git blame -w) of text rendering and the component-browser / grid-view / list-view stack in the ensogl GPU/WebGL rendering framework (Rust -> WebAssembly)
- #1 contributor to the app/gui application layer (~24%); lead of the engine-protocol client layer; work across language tooling (span-tree/AST)
- #4 author across a 267k-line Rust codebase: 250+ merged PRs
- Code @ Rust-era commit c834847: [text rendering](https://github.com/enso-org/ide/pull/62/changes) [grid-view](https://github.com/enso-org/enso/tree/c834847/lib/rust/ensogl/component/grid-view) ·
[component-browser](https://github.com/enso-org/enso/tree/c834847/app/gui/view/component-browser/component-list-panel/grid) · [engine-protocol](https://github.com/enso-org/enso/tree/c834847/app/gui/controller/engine-protocol)
- [All my merged Enso PRs](https://github.com/enso-org/enso/pulls?q=is%3Apr+author%3Afarmaazon+is%3Amerged) + [from older repository](https://github.com/enso-org/ide/pulls?q=is%3Apr+author%3Afarmaazon+is%3Amerged)

### Open-source contributions
- [rust-windowing/keyboard-types](https://github.com/rust-windowing/keyboard-types/pull/4) — implemented FromStr for Key
- [qmetaobject-rs](https://github.com/woboq/qmetaobject-rs/pull/145) (732★) — QVariant conversions (Rust↔️Qt/QML interop)
- [Slint](https://github.com/slint-ui/slint/pull/3411) (22.9k★) — derive serde for Color *(small fix)*
- [vorot/roots](https://github.com/vorot/roots/pull/24) — fixed an out-of-bounds panic in numerical root-finding

### Projects
- [Curling simulator](https://github.com/farmaazon/gielo) — Rust (Slint). A 2D curling-stone simulation optimized to batch-simulate large numbers of games for statistical analysis (e.g. shot-outcome heatmaps), with a [live browser 
version](https://farmaazon.github.io/gielo/) (same code compiled to WebAssembly).
- [Regnum](https://github.com/farmaazon/regnum) — a 2D real-time grand-strategy game engine (C++/SDL2): hierarchical Dijkstra pathfinding, viewport culling, per-edge autotiling, designed for maps of ~a million tiles. Older code developed mostly during studies and shortly after.
- [msdfgen-wasm](https://github.com/enso-org/msdfgen-wasm) — WASM wrapper of the msdfgen C/C++ multi-channel SDF font-rendering library *(authored at Enso, open source)*

### Tech
Rust · C++ (11/14/17) · C · TypeScript · concurrency/multithreading · WebAssembly · WebGL · Qt · Python/Java (moderate)
