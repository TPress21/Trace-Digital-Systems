# Trace Digital Systems — landing page

Static site (no build step). Three files: `index.html`, `styles.css`, `script.js`.
Language toggle covers English, Spanish, Chinese, and Vietnamese — Philadelphia's
top three non-English languages after Spanish/Chinese/Vietnamese per Census data.

## Deploy to Vercel

**Fastest path (no terminal):**
1. Push this folder to a new GitHub repo.
2. Go to vercel.com → **Add New → Project** → import that repo.
3. Framework preset: **Other** (it's static — no build command needed).
4. Deploy. Done in under a minute.

**Or via CLI:**
```
npm i -g vercel
cd trace-digital-systems
vercel --prod
```

See the full conversation reply for the complete list of what to connect
(domain, form backend, booking calendar, WhatsApp number, analytics, email,
LLC/insurance items) before sending this live to real clients.
