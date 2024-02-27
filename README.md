This repo contains two Next.js apps:

1. `demo` - uses `@nx/next` from Project Crystal to infer targets
2. `demo2` - uses executors from pre-Crystal for `dev` and `build` targets

There is a share `ui` library that is used in both apps.


```
npx nx dev demo --port 4201
npx nx dev demo2
```
