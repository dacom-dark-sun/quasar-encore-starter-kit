# 🚀 QUASAR & ENCORE & PUG STARTER KIT
A monorepo for SPA frontend on QUASAR and backend on ENCORE.

Frontend is structured for sustainable growth using Feature Sliced Design methodology. The appropriate folder structure is prepared.

Instead of HTML, we use PUG in Quasar - it looks elegant, concise, and gets rid of excess textual clutter in the code.

We use LERNA for version management. It allows consistent version switching in the monorepo.

You'll need encore-cli and lerna installed (install from official websites).

## Installation
```
pnpm install
```
## Launch
```
lerna run dev
```

Lerna will run both packages in a single debug window.

Encore: http://127.0.0.1:4000
Quasar: http://127.0.0.1:3010

```Build Encore Client
pnpm run gen
```

The client file will be moved to frontend/shared/api, allowing backend interaction based on its interfaces.

