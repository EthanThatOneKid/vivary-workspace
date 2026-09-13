# vivary-dev-workspace

Workspace manifest for the `vivary-dev` org, rooted at `EthanThatOneKid/vivary-dev-workspace`.

## Layout

- `workspace.json` — source of truth for repos under `repos/` and sub-workspaces under `workspaces/`.
- `repos/` — cloned checkouts for the repositories listed in the manifest.

## Repositories

The manifest currently tracks the repositories owned by the `vivary-dev` org:

- `vivary`
- `.github`
- `vivary-workbench-handoff`
- `Vivary-New`

## Commands

Use `wspace` from the `workspace-cli` repo to inspect and manage this workspace:

```bash
wspace check
wspace install
wspace update
```
