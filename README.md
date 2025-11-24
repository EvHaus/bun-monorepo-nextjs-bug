# bun-monorepo-nextjs-bug

To reproduce the bug:

1. Run `bun i`
2. Run `bun dev`

Note that for some reason `@types/node` is in `bun.lock` here, even though I never ask for it to be installed. This is not the same when using a monorepo/workspaces setup.