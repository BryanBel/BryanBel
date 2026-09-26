## Bryan Belandria

Full-stack developer in Caracas, working remotely. I build web products with **Astro**,
**React**, **TypeScript**, **Node** and **PostgreSQL**.

Before this I spent four years monitoring production server infrastructure at CANTV,
Venezuela's largest telecom operator. That is where I learned what actually breaks in
production, and why uptime is a design decision rather than an afterthought.

### What I'm building

**[Latam Med Gas](https://github.com/BryanBel/latam-med-gas-landing-page)** ·
[latammedgas.com](https://latammedgas.com)
Production site for a Miami medical-gas supplier — a paying client, live since August 2026.
Static Astro with React islands, Sanity CMS so the client edits their own content, and a
contact form whose database policy allows inserts and nothing else.

**[DigiClin](https://github.com/BryanBel/digiclin-system-v2)** ·
[live demo](https://digiclin-system-v2.onrender.com)
Clinic management system: appointments and medical records behind separate patient, doctor
and admin areas. Express API over PostgreSQL, 28 endpoints, sessions in an httpOnly cookie,
and role checks enforced on the server rather than hidden in the interface.

**[Shield Link](https://github.com/BryanBel/shield-link)** ·
[live demo](https://shield-link.vercel.app)
URL safety scanner. Six layers ordered cheapest first, so most links are settled before
reaching VirusTotal. Verdicts have three levels instead of two, because a couple of
detections out of ninety engines is usually noise — `google.com` included.

**[Vibra](https://github.com/BryanBel/vibra-web)** ·
[vibracompany.netlify.app](https://vibracompany.netlify.app)
Storefront for an accessories brand. The `feat/monorepo-api` branch holds where it is
going: a pnpm + Turborepo monorepo with a NestJS API, an oRPC contract typed end to end,
Drizzle over Postgres, and argon2 password hashing.

### Stack

Astro · React · TypeScript · Node · Express · NestJS · PostgreSQL · Tailwind · pnpm · Git

### Studying

Computer Engineering at Universidad Alejandro de Humboldt.
Spanish (native) · English (C1, certified)

[LinkedIn](https://linkedin.com/in/bryanbel) · bryanbelandriav@gmail.com
