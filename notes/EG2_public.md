# EG2 Public Note (Capture and Restart)

Mature wording: `transport / local-to-global transfer`.

In-paper anchor: `paper/SECTION_CONJECTURE_PREPRINT.md` (`SC_G2`).

## Goal
Expand the compressed capture/restart language into the local-to-global transport gate for `proving existence and identification of rational sections of the étale fundamental exact sequence through an admissible section-packet closure architecture`.

## Objects

- transport carrier: the admissible evolution, deformation, or routed lattice declared in the preprint.
- capture floor: `sigma_fundamental`.
- restart law: the normalization/re-entry rule that keeps corrective steps inside the admissible class.
- carried losses: defect, restart, and normalization losses that must remain explicit.

## Closure Criterion

`SC_G2` closes when `sigma_fundamental` survives admissible losses and restart corrections: fundamental-group defect stays above capture floor across admissible section losses.
This is the transport contribution to `M_SC`.

## Lemma Chain and Proof Payload

### Lemma EG2.1 (transport accounting)
Every transport step used by the lane is charged to the declared defect ledger instead of being absorbed into prose.

Payload: verify that the capture constant `sigma_fundamental` is present in the constants registry and extraction inputs.

### Lemma EG2.2 (restart preservation)
Restart or normalization preserves the declared admissible class and does not create an untracked remainder.

Payload: inspect the repro script and guard output for the gate tied to `sigma_fundamental`.

### Theorem EG2.3 (capture gate closure)
If transport accounting and restart preservation hold, then `SC_G2` carries local control forward without breaking admissibility.

## Current Instantiation

- gate: `SC_G2`
- artifact key: `sigma_fundamental`
- mature equivalent: `transport / local-to-global transfer`
- audit surface: `repro/run_repro.sh` and `repro/certificate_runtime.json`
