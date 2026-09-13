# vivary-dev-workspace

Workspace manifest for the `vivary-dev` org, rooted at `EthanThatOneKid/vivary-workspace`.

## Layout

- `workspace.json` — source of truth for repos under `repos/`.
- `repos/` — cloned checkouts for the repositories listed in the manifest.

## Commands

Use `wspace` to inspect and manage this workspace:

```bash
wspace check
wspace install
wspace update
```
