# Current Program State

**Observed:** 2026-08-12  
**Status:** Pre-launch / Gate 0

| Repository | Main state | Open work | Launch implication |
|---|---|---|---|
| `jenksed/project-arsenal` | `980a58d331f4ed0679e6ae306b9d55b2ee21d179` | No open PRs or issues observed | Arsenal package may pin this SHA after owner accepts Decision 0001 |
| `jenksed/loadout` | Empty repository; no branch commit | None | Must merge minimal bootstrap before an implementation agent can start |
| `jenksed/kiln` | `d3af751ebc25da04e7d3e3380dc5dbd601c1a42b` | PR #62 updates the Arsenal development pin; P1-S02-T01 remains authorized | PR #62 must be merged or closed deliberately; Kiln start SHA is recorded afterward |
| `jenksed/engineering-system` | Empty repository; no branch commit | None | Must merge program bootstrap and accept Decision 0001 |

## Settled facts

- Arsenal and Kiln remain separate.
- Loadout is the third product and default user-facing capability environment.
- `engineering-system` is coordination only, not a product.
- MiniMax M3 is the default daily implementation model.
- A different model or independent session verifies cross-product boundary and high-risk authority changes.
- No launch task may interrupt or widen Kiln P1-S02-T01.

## Unknown until launch gate

- final merged SHA for the Loadout bootstrap;
- final merged SHA for the engineering-system bootstrap;
- final Kiln main SHA after PR #62 disposition;
- whether all three agent environments can run repository verification commands;
- owner acceptance of Decision 0001 and the three work packages.

