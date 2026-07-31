# Local pi-caveman fork

Upstream base: `pi-caveman@1.0.8`.

## Local change

Footer status label shortened from `caveman level: FULL` to `caveman: FULL`.

One-line source change in `extensions/caveman.ts` (`setStatus` muted prefix).

Reapply after upgrading upstream. Do **not** drop upstream config-directory resolution or `appendSystemPrompt` / OMP array handling when replaying this patch.
