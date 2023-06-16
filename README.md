## Reproduce

1. pnpm install
2. open file `packages/api/src/index.ts`
3. try import `./add`, but no suggestion

## Note

1. if I move `packages/api/src` and `packages/api/package.json` to project root, no this issue
2. this issue started from 4.8.4 and still exits in latest dev version
