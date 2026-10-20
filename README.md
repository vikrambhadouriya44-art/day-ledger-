# Day Ledger

Write your day, get a study plan, get reminders, and prove every study block.
Plain HTML, CSS and JavaScript. No build step, no backend. Data is saved in each
person's own browser (localStorage), so every friend gets a private copy.

## Deploy on Vercel (GitHub method)

1. Create a new GitHub repo and upload `index.html` and `vercel.json`.
2. Go to vercel.com, click Add New, then Project, and import that repo.
3. Framework Preset: Other. Leave build command and output directory empty.
4. Click Deploy. Share the `.vercel.app` link with friends.

## Deploy with Vercel CLI

```
npm i -g vercel
cd day-ledger
vercel --prod
```

## Notes

- Reminders and notifications work only while the tab is open.
- Open it over https (Vercel does this) so browser notifications can be enabled.
- Next upgrades: login + database (Supabase), AI check of proof, installable PWA.
