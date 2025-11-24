# bun-monorepo-nextjs-bug

To reproduce the bug:

1. Run `bun i`
2. Run `bun --elide-lines=0 --filter './packages/my-next-app' dev`

If you add the `@types/node` package to `/packages/my-next-app/package.json` and reinstall -- then it works.