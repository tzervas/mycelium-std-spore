# CROSS-REF — mycelium-std-spore

Mycelium-internal dependencies only (steer handoff §6.1; external crates stay in Cargo
metadata). Pinned revs are the fixed (buildable) tips recorded by the Phase-B wave;
content hash = git tree hash of the pinned rev.

| Interface consumed | Repo | Pinned rev | Content hash | Notes |
|---|---|---|---|---|
| mycelium-core | https://github.com/tzervas/mycelium-core | `781d3fcceba82acfe6b0eb46650513bd78a2416b` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-core` (see monorepo `docs/api-index/INDEX.md#mycelium-core`) |
| mycelium-proj | https://github.com/tzervas/mycelium-proj | `cfc934b32c0b7b57becbb7ddfe3c516712c6ec0e` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-proj` (see monorepo `docs/api-index/INDEX.md#mycelium-proj`) |
| mycelium-spore | https://github.com/tzervas/mycelium-spore | `12f117d395545ee89ba144eb858de11f0b36ab16` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-spore` (see monorepo `docs/api-index/INDEX.md#mycelium-spore`) |
| mycelium-std-content | https://github.com/tzervas/mycelium-std-content | `792eb7fe476ebf50bae1d8a20e3a7fba83a16d8b` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-content` (see monorepo `docs/api-index/INDEX.md#mycelium-std-content`) |
| mycelium-std-core | https://github.com/tzervas/mycelium-std-core | `580b64316774e22f0b7d5d495ca1d9b9d6536a60` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-core` (see monorepo `docs/api-index/INDEX.md#mycelium-std-core`) |
| mycelium-std-numerics | https://github.com/tzervas/mycelium-std-numerics | `cdfb2cdef08818091d47ec99f592947c1ccc4085` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-numerics` (see monorepo `docs/api-index/INDEX.md#mycelium-std-numerics`) |
| mycelium-std-vsa | https://github.com/tzervas/mycelium-std-vsa | `514798245c507d515c3a53ea1ec4152b409e821d` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-vsa` (see monorepo `docs/api-index/INDEX.md#mycelium-std-vsa`) |
| mycelium-vsa | https://github.com/tzervas/mycelium-value | `fce92daed05e9f10202c202648ec43fb0a6991d7` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-vsa` (see monorepo `docs/api-index/INDEX.md#mycelium-vsa`) |

**Owning docs:** `docs/spec/stdlib/spore.md` (slice in this repo) · RFC-0016.
**Source provenance:** extracted from `tzervas/mycelium` archive `aad96b7a…`; fixed by
the course-correction Phase B (workspace root, git pins, toolchain + supply-chain
replicas, CI v2). Full program record: monorepo
`docs/planning/course-correction-2026-07-18/PROGRAM.md`.
