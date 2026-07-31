# @local/pi-caveman-custom

Local fork of [pi-caveman](https://github.com/jonjonrankin/pi-caveman) (`1.0.8`).

Upstream README preserved verbatim in [`original_readme.md`](./original_readme.md).
Patch notes in [`CUSTOM_PATCHES.md`](./CUSTOM_PATCHES.md).

## Intentional local change

| Area | Upstream | Local |
|------|----------|--------|
| Footer status label | `caveman level: FULL` | `caveman: FULL` |

Keeps upstream `PI_CODING_AGENT_DIR` / `XDG_CONFIG_HOME` config resolution and OMP `systemPrompt` `string \| string[]` coercion.

## Package identity

- **name:** `@local/pi-caveman-custom`
- **version:** `1.0.8-custom.1`
- **private:** `true`

## Test

```bash
bun scripts/test-systemprompt-coerce.mjs
# or
npm test
```

## Install (local path)

Point pi at this checkout / package path instead of npm upstream.
