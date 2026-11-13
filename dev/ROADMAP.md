# textbuf-lib - Roadmap

> Path from scaffold to a stable 1.0. Hard parts are front-loaded; each phase has hard exit criteria.
>
> **Anti-deferral rule:** no listed hard task moves to a later phase unless this file records the move and the reason.

## v0.1.0 - Scaffold (DONE)
Compiles, CI green, structure correct, no domain logic.
- [x] Manifest, README, CHANGELOG, REPS, dual license, CI, deny, clippy, rustfmt, DIRECTIVES, ROADMAP.

## v0.2.0 - Foundation
- [ ] Piece tree, edits, line index, position conversion, snapshots, reference-model properties, benches on 100MB files.

## v0.5.0 - Implementation
- [ ] Edit batches with change sets (for LSP incremental sync), search.

## v0.9.0 - Hardening
- [ ] Fuzzing; memory profiling.

## v1.0.0 - Stable
- [ ] Frozen after Studio's editor and ls-tools use it (D18).
