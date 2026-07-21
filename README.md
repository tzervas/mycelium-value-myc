# mycelium-value-myc

<!-- FLEET-BADGES:BEGIN -->
[![CI](https://github.com/tzervas/mycelium-value-myc/actions/workflows/fleet-ci.yml/badge.svg?branch=main)](https://github.com/tzervas/mycelium-value-myc/actions/workflows/fleet-ci.yml?query=branch%3Amain)
[![Security](https://github.com/tzervas/mycelium-value-myc/actions/workflows/fleet-security.yml/badge.svg?branch=main)](https://github.com/tzervas/mycelium-value-myc/actions/workflows/fleet-security.yml?query=branch%3Amain)
[![Runner](https://img.shields.io/badge/runs--on-self--hosted%20podman-informational)](https://github.com/tzervas/gha-runner-ctl)
<!-- FLEET-BADGES:END -->


Mycelium-language sibling of [`tzervas/mycelium-value`](https://github.com/tzervas/mycelium-value).

| Field | Value |
|---|---|
| **Program** | PROGRAM-SELFHOST-DECOMPOSE Phase T |
| **Rust twin** | tzervas/mycelium-value |
| **Transpile tip** | monorepo `3277b99618c858f03b1f482ed9ae15e10b9c3909` (post G-β when available) |
| **Archive provenance** | monorepo main `aad96b7a425710db5e91094d4fc2ca21a129e41a` |
| **Honesty** | Emissions are **Declared/Empirical** gap-profiler output until differential-witnessed port (M-993). Not production-ready DN-88 §3. |

## Layout

- `lib/` — `.myc` nodules (transpile + optional hand-port seed)
- `experiments/vet/` — gap profiles + vet artifacts

## Check

When `myc-check` is available:

```bash
myc check lib/*.myc
```
