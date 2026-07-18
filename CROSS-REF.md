# CROSS-REF — mycelium-std-spore

Mycelium-internal dependencies only (steer handoff §6.1; external crates stay in Cargo
metadata). Pinned revs are the fixed (buildable) tips recorded by the Phase-B wave;
content hash = git tree hash of the pinned rev.

| Interface consumed | Repo | Pinned rev | Content hash | Notes |
|---|---|---|---|---|
| mycelium-core | https://github.com/tzervas/mycelium-core | `46d2515cbd86d2ae4d1365f4adcd2796737e9f0b` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-core` (see monorepo `docs/api-index/INDEX.md#mycelium-core`) |
| mycelium-proj | https://github.com/tzervas/mycelium-proj | `20b8a6d264ac728e81cfe8cd90cec8d2a91370be` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-proj` (see monorepo `docs/api-index/INDEX.md#mycelium-proj`) |
| mycelium-spore | https://github.com/tzervas/mycelium-spore | `283f9fd901607841d5302d5935d15d873a32eef7` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-spore` (see monorepo `docs/api-index/INDEX.md#mycelium-spore`) |
| mycelium-std-content | https://github.com/tzervas/mycelium-std-content | `a6059bae85256fed1272f38a8cbbd2dec2e8c56c` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-content` (see monorepo `docs/api-index/INDEX.md#mycelium-std-content`) |
| mycelium-std-core | https://github.com/tzervas/mycelium-std-core | `376762cc17853e1582684ececf9e760426bcfb0c` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-core` (see monorepo `docs/api-index/INDEX.md#mycelium-std-core`) |
| mycelium-std-numerics | https://github.com/tzervas/mycelium-std-numerics | `2676276b1559f0c1c0b1c0c39ad48ba6ff89d639` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-numerics` (see monorepo `docs/api-index/INDEX.md#mycelium-std-numerics`) |
| mycelium-std-vsa | https://github.com/tzervas/mycelium-std-vsa | `3936b492b99ba204e9c156822f70041383a37056` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-vsa` (see monorepo `docs/api-index/INDEX.md#mycelium-std-vsa`) |
| mycelium-vsa | https://github.com/tzervas/mycelium-value | `6d230ad2023a716704c697ac6812a2062624b4eb` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-vsa` (see monorepo `docs/api-index/INDEX.md#mycelium-vsa`) |

**Owning docs:** `docs/spec/stdlib/spore.md` (slice in this repo) · RFC-0016.
**Source provenance:** extracted from `tzervas/mycelium` archive `aad96b7a…`; fixed by
the course-correction Phase B (workspace root, git pins, toolchain + supply-chain
replicas, CI v2). Full program record: monorepo
`docs/planning/course-correction-2026-07-18/PROGRAM.md`.
