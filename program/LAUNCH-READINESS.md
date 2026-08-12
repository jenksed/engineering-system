# Simultaneous Launch Readiness

The program manager may recommend launch only when every required box is satisfied.

## Product and contract gate

- [ ] Owner accepts Decision 0001.
- [ ] Engineering-system bootstrap is merged.
- [ ] Loadout bootstrap is merged.
- [ ] Contract v0 documents are readable and internally consistent.
- [ ] Each product package names its producer, consumer, and non-responsibilities.

## Repository gate

- [ ] Arsenal launch SHA recorded and equals current `main`.
- [ ] Loadout launch SHA recorded and equals current `main`.
- [ ] Kiln PR #62 is merged or deliberately closed.
- [ ] Kiln launch SHA recorded after PR #62 disposition.
- [ ] No unrelated open implementation branch will be mistaken for launch authority.

## Agent environment gate

- [ ] One isolated checkout/worktree exists per product.
- [ ] MiniMax M3 is available with thinking enabled.
- [ ] Each agent can read its repository instructions.
- [ ] Each agent can run the package's verification commands.
- [ ] Credentials are injected through approved environment/configuration, not committed files.

## Work-package gate

- [ ] ARS-01 is owner-approved and pinned.
- [ ] LOD-01 is owner-approved and pinned.
- [ ] KIL-01 is owner-approved and pinned.
- [ ] No owned-path collision exists.
- [ ] Every package has explicit prohibited changes and stop conditions.
- [ ] Fixture dependencies exist before launch.

## Final owner gate

- [ ] Program manager presents one combined launch prompt.
- [ ] Owner authorizes simultaneous launch.

## Launch command status

**HOLD.** Do not launch product agents until the final owner gate is checked.

