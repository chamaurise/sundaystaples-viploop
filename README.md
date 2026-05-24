# Sunday Staples VIP Loop

A small standalone VIP engagement loop for testing missions, status, access rewards, and influence feedback before merging these mechanics into the main survey/focus-group platform.

## Run Locally

This prototype is dependency-free. Open `index.html` directly, or serve the folder:

```bash
npm run dev
```

Then visit `http://localhost:4173`.

## Prototype Scope

- Seeded VIP profiles
- Active market-signal missions
- Mission response flow with confidence and rationale
- Private VIP status and access unlocks
- Influence recap and cohort signal reveal

## Vercel

This deploys as a static site. In Vercel, import the repository with:

- Framework preset: `Other`
- Build command: leave blank, or use `npm run build`
- Output directory: leave blank
- Install command: leave blank

Do not use `node server.mjs` or `npm start` on Vercel. `server.mjs` is only a local preview helper.
