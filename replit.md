# MAVLIT landing page

A single static landing page for MAVLIT ("Find the brand deals you deserve — without the guesswork."). Every "Get early access" button goes to https://mavlit.com/dashboard.

## Run & Operate

- `pnpm --filter @workspace/mavlit run dev` — run the page locally (needs `PORT` and `BASE_PATH`)
- `pnpm --filter @workspace/mavlit run build` — build to `artifacts/mavlit/dist/public`
- `pnpm run typecheck` — typecheck

## Stack

- pnpm workspace, Node.js 24, TypeScript 5.9
- React 19 + Vite + Tailwind

## Where things live

- `artifacts/mavlit/src/pages/Home.tsx` — the whole page
- `artifacts/mavlit/src/components/ui` — shared UI kit
