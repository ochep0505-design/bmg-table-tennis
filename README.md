# BMG TABLE TENNIS COMPETITION

Live round-robin tournament website powered by GitHub Pages + Supabase.

- `index.html` — public, no login
- `admin.html` — private admin login
- `config.js` — Supabase URL + publishable key

The publishable key is safe to expose in browser code when Supabase Row Level Security is correctly configured. Never put a service-role key or database password in this repository.
