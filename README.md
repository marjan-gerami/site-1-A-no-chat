# site-1-A-no-chat

Independent React + Vite site for Vita experiment. Architecture **A**, chatbot **disabled**. The architecture and chatbot condition are hardcoded, not selectable by URL.

## Run

```bash
npm install
npm run build
npm run dev
```

## Deploy

Upload the **contents of this directory** to its own GitHub repository. Import that repository as a separate Vercel project. Framework: Vite; build command: `npm run build`; output directory: `dist`.

No chatbot or chatbot API is deployed in this variant.

**Status:** Build and live LLM connection have not been verified. Order completion is a browser-only demo and does not persist to a backend.
