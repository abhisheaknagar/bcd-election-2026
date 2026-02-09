# BCD Election 2026 — Electoral Roll Portal

Campaign portal for **Jaibir Singh Nagar** (Ballot No. 126) — Bar Council of Delhi Election 2026.

## Features
- Search 98,000+ lawyers by phone number, name, registration number, or serial number
- View voter card, photo, and QR code
- Download cards as PNG
- Share via WhatsApp
- Search logging and admin dashboard
- Mobile responsive

## Tech Stack
- **Frontend:** Single HTML file with React (CDN)
- **Database:** Supabase (PostgreSQL)
- **Image Storage:** Supabase Storage
- **Hosting:** Vercel

## Deploy
1. Push this repo to GitHub
2. Connect to Vercel → auto-deploys
3. Done!

## Configuration
All config is in `index.html`:
- `SUPABASE_URL` — Your Supabase project URL
- `SUPABASE_ANON_KEY` — Your Supabase publishable/anon key
- `CANDIDATE` — Candidate details (name, phone, ballot number)
