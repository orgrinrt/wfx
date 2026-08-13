# wfx

A specialised data-driven game engine written in Rust

Early-stage: the workspace layout and build configuration are in place, but the
engine itself is not yet implemented. The Cargo workspace lives in `engine/` and
contains `wfx-core` (the engine core library), `wfx-runtime` (the `wfx` binary)
and `wfx-utils` (shared utilities). It builds on Bevy with a nightly toolchain.
Module API notes live in [`docs/`](docs/index.md).
