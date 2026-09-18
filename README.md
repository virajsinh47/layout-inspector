# Layout Inspector

Visual DOM element picker by **Virajsinh Zala** — React + TypeScript.

Click any element on the page, get its selector, tag, text preview, and HTML context. Built for developer tools, AI coding workflows, and UI debugging.

## Features

- Visual highlight on hover
- Single or multi-select
- CSS selector generation
- Insert / lasso modes
- Works with React (peer deps) or standalone bundle
- Keyboard: Enter confirm · Escape cancel

## Quick start

```bash
npm install
npm run dev
```

Open the URL Vite prints (usually http://localhost:5173).

Click **Start inspecting**, then click any sample element on the page.

## Use in your app

```bash
npm install layout-inspector
# or link locally after npm run build
```

```ts
import { launchSelector } from "layout-inspector";

const result = await launchSelector();
console.log(result);
```

Standalone (no React peer required):

```ts
import { launchSelector } from "layout-inspector/standalone";
```

## Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Demo app |
| `npm run build` | Build library + standalone bundle |
| `npm test` | Tests |

## License

MIT — see `LICENSE.md` and `NOTICE.md`.
