### Ayush Kaushik

Building production systems for India — creator platforms, offline-first desktop tools, AI-powered products.

---

**Shipped**

**[AutoDoc AI](https://github.com/ww2d2vjh8c-lab/autodoc-ai)** — AI-powered documentation generator for any GitHub repo.
Paste a public URL → get a README, API docs, and technical explanation in seconds. Groq (Llama 3.3 70B) runs 3 generation tasks in parallel. Full-stack: Next.js on Vercel, Express on Railway, Prisma + PostgreSQL. [Live →](https://frontend-six-neon-59.vercel.app)

**[HustleClub](https://github.com/ww2d2vjh8c-lab/HustleClubV1)** — Multi-sided creator economy platform for India.
Courses, UGC gig jobs, and a digital marketplace in one app. Production payment FSM with idempotency and webhook deduplication. Role-based access (user to creator to admin). Full CI/CD: lint to typecheck to migrations to Vercel.

**[Bloom Cafe POS](https://github.com/ww2d2vjh8c-lab/POS-BASIC-BILLING)** — Offline-first desktop billing system. Delivered to a production client.
Atomic billing transactions, 6-table session management, 58mm thermal receipt printing, versioned SQLite migrations, and automated Windows installer via GitHub Actions. Shipped with a user manual and installation guide.

---

**Building**

**JobFit** — AI-powered resume analyzer for Indian job seekers.
Upload resume + paste JD — match score, skill gap breakdown, rewritten summary.

---

**Stack**

`TypeScript` `Next.js` `React` `Node.js` `Supabase` `PostgreSQL`
`Electron` `SQLite` `Tailwind CSS` `Groq` `GitHub Actions` `Vercel` `Railway`

---

**Systems I think about**

- Payment state machines and idempotency
  - Offline-first architecture with sync
    - Auth at the application layer + RLS at the DB layer
      - CI/CD from feature branch to production

---

CS · Open to SDE-1 roles · coc123.1607@gmail.com
