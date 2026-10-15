# COCURRICULARS.

A TASKT-inspired student co-curricular tracker and opportunity discovery prototype.

## Features
- Animated, responsive landing page
- Dashboard with custom hour targets, category breakdown, badges and streaks
- Manual activity logging, editing via deletion/re-entry, evidence file-name attachment
- Opportunity Hub with curated illustrative cards, search/category filters, saved bookmarks, and LinkedIn search links
- Green Missions with one-click prefilled activity logging
- Copyable resume summary and downloadable PDF portfolio
- Browser LocalStorage persistence

## Run locally
Requires Node.js 18+ (Node 20 LTS recommended).

```bash
npm install
npm run dev
```

Open the localhost URL printed by Vite.

## Deploy to Vercel
1. Upload the project folder to a GitHub repository.
2. Import the repository at https://vercel.com/new.
3. Framework preset: **Vite**; build command: `npm run build`; output directory: `dist`.
4. Deploy.

## Important demo limitations
- The opportunity cards are **illustrative**, not live vacancies. LinkedIn buttons launch searches on LinkedIn, not a live API feed.
- Hours are **self-reported**, not verified by organisations.
- The upload field stores only the file name in the activity record; it does not preserve or upload the file itself.
- LocalStorage data stays in the same browser and can be cleared by browser settings. No user authentication or cloud sync.
- Sample activity records are preloaded to make the demo useful immediately; they are illustrative.
