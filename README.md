# Serratus Website

## Run locally
```
npm install
npm run dev
```
Opens at http://localhost:5173

## Deploy live (easiest → Vercel)
1. Create a free account at https://vercel.com (sign in with GitHub/email)
2. Go to https://vercel.com/new
3. Drag this whole `serratus-site` folder onto the upload area
   — OR push it to a GitHub repo first and import that repo instead
4. Vercel auto-detects Vite, click **Deploy**
5. You'll get a live URL like `serratus-site.vercel.app` in ~1 minute

## Alternative: Netlify
1. `npm run build` (creates a `dist` folder)
2. Go to https://app.netlify.com/drop and drag the `dist` folder in
3. You get a live URL instantly

## Custom domain (e.g. serratus.com / serratus.fit)
1. Buy the domain (Namecheap, GoDaddy, Google Domains, etc.)
2. In Vercel/Netlify project settings → Domains → add your domain
3. Update the DNS records at your domain registrar as instructed on screen
4. Live in a few minutes to a few hours (DNS propagation)

## Notes
- The consultation form opens the visitor's email app pre-filled with their
  details — it does not submit anywhere automatically. If you want it to
  send straight to an inbox or a spreadsheet, that needs a small backend
  (e.g. Formspree, Google Forms embed, or a simple serverless function) —
  ask and it can be wired in.
