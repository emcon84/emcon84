# Hi, I'm Emiliano Conti 👋

Software Frontend Engineer focused on clean, scalable architectures — TypeScript across the stack, from API design to AI-assisted tooling.

## 🛠️ Tech Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat&logo=bun&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

## 🚀 Featured Projects

### 🎙️ MAX — Voice AI Assistant for Hormax
A production voice assistant for Hormax, a concrete & construction materials manufacturer. Workers on-site ask technical questions out loud and get spoken answers in under 3 seconds — no manuals, no calls to support, hands stay free.

- **Stack:** Next.js, TypeScript, Anthropic Claude (reasoning), Groq Whisper (speech-to-text), ElevenLabs (text-to-speech), Supabase, Clerk, Vercel
- **Architecture:** Installable PWA, full voice pipeline (STT → LLM with job-site context & conversation history → streamed TTS) end-to-end in under 3 seconds
- **Impact:** query resolution time cut from minutes to seconds; removed the bottleneck of 2-3 senior technicians holding all the product knowledge; full audit trail of queries
- 🟢 **Live demo:** [hormaxia.vercel.app](https://hormaxia.vercel.app)

### 🏗️ Arki — AI Architecture Assistant
An AI-powered senior architect that interviews you about your project through a structured conversation and generates a complete technical blueprint: architecture style (monolith / microservices / modular), recommended stack with rationale, Mermaid diagrams, data models, infrastructure & deployment plans, risk analysis with mitigations, and Architecture Decision Records — plus ready-to-paste developer specs for Claude Code, Cursor or Bolt.

- **Stack:** Next.js 15 (App Router), TypeScript (strict), Drizzle ORM + PostgreSQL, Bun
- **AI:** Anthropic Claude SDK — dual-model strategy (Sonnet 4.6 for the fast streaming interview, Opus 4.8 for deep blueprint generation)
- **Architecture:** Screaming Architecture — folder structure mirrors intent (`services/`, `hooks/`, `db/`, `components/`), Server Components for direct DB access
- **Extras:** Admin dashboard, ES/EN i18n, Docker Compose, test coverage
- 🟢 **Live demo:** [ar-ki-tech.vercel.app](https://ar-ki-tech.vercel.app) · 💻 **Code:** [github.com/emcon84/arki](https://github.com/emcon84/arki)

### 📍 Warning App — Civic Issue Reporting Platform
A decentralized platform for citizens to report urban issues (trash, broken streets, faulty services) with geolocation and photo evidence. Reports are plotted on interactive maps, filterable by category and neighborhood, with public analytics and community-driven coordination.

- **Frontend:** Next.js 16 (App Router, Turbopack), React 19, TypeScript, Tailwind CSS v4, Leaflet maps, Framer Motion
- **Backend:** Bun + Elysia.js, Prisma ORM, PostgreSQL
- **Infra:** AWS S3 (photo storage), Clerk (auth), Web Push notifications, PWA with offline support
- **Architecture:** Modular backend (`reports`, `professionals`, `pharmacies`, `events`...) with router → service → data separation, rate limiting, public analytics API
- **Quality:** 270+ tests
- 🟢 **Live demo (Reconquista, Santa Fe):** [reportesreconquista.com](https://reportesreconquista.com)
- 💻 **Code:** [warning-app-front](https://github.com/emcon84/warning-app-front) · [warning-app-api](https://github.com/emcon84/warning-app-api)

## 📫 Get in touch

- LinkedIn: [linkedin.com/in/emiliano-conti](https://www.linkedin.com/in/emiliano-conti)
- Email: emcon84@gmail.com

---

<details>
<summary>🇪🇸 Versión en español</summary>

# ¡Hola! Soy Emiliano Conti 👋

Software Frontend Engineer enfocado en arquitecturas limpias y escalables — TypeScript en todo el stack, desde el diseño de APIs hasta herramientas asistidas por IA.

## 🚀 Proyectos destacados

### 🎙️ MAX — Asistente de Voz con IA para Hormax
Un asistente de voz en producción para Hormax, fabricante de hormigón y materiales de construcción. Los operarios en obra hacen consultas técnicas por voz y reciben respuestas habladas en menos de 3 segundos — sin manuales, sin llamar a soporte, con las manos libres.

- **Stack:** Next.js, TypeScript, Anthropic Claude (razonamiento), Groq Whisper (speech-to-text), ElevenLabs (text-to-speech), Supabase, Clerk, Vercel
- **Arquitectura:** PWA instalable, pipeline de voz completo (STT → LLM con contexto de la obra e historial conversacional → TTS streameado) en menos de 3 segundos de punta a punta
- **Impacto:** el tiempo de resolución de consultas pasó de minutos a segundos; se eliminó la dependencia de 2-3 técnicos senior que concentraban todo el conocimiento del producto; queda historial auditable de consultas
- 🟢 **Demo en vivo:** [hormaxia.vercel.app](https://hormaxia.vercel.app)

### 🏗️ Arki — Asistente de Arquitectura con IA
Una herramienta de IA que actúa como arquitecto senior: te entrevista de forma conversacional sobre tu proyecto y genera automáticamente un blueprint técnico completo — estilo de arquitectura (monolito / microservicios / modular), stack recomendado con justificación, diagramas Mermaid, modelo de datos, plan de infraestructura y deployment, análisis de riesgos con mitigaciones y ADRs, además de specs listos para copiar a Claude Code, Cursor o Bolt.

- **Stack:** Next.js 15 (App Router), TypeScript (strict), Drizzle ORM + PostgreSQL, Bun
- **IA:** Anthropic Claude SDK — estrategia de doble modelo (Sonnet 4.6 para la entrevista en streaming, Opus 4.8 para la generación profunda del blueprint)
- **Arquitectura:** Screaming Architecture — la estructura de carpetas refleja la intención (`services/`, `hooks/`, `db/`, `components/`), Server Components para acceso directo a la DB
- **Extras:** Dashboard de admin, i18n ES/EN, Docker Compose, cobertura de tests
- 🟢 **Demo en vivo:** [ar-ki-tech.vercel.app](https://ar-ki-tech.vercel.app) · 💻 **Código:** [github.com/emcon84/arki](https://github.com/emcon84/arki)

### 📍 Warning App — Plataforma ciudadana de reportes urbanos
Una plataforma descentralizada para que los ciudadanos reporten problemas urbanos (basura, calles rotas, servicios deficientes) con geolocalización y evidencia fotográfica. Los reportes se visualizan en mapas interactivos, son filtrables por categoría y barrio, e incluyen analytics públicos y coordinación comunitaria.

- **Frontend:** Next.js 16 (App Router, Turbopack), React 19, TypeScript, Tailwind CSS v4, mapas con Leaflet, Framer Motion
- **Backend:** Bun + Elysia.js, Prisma ORM, PostgreSQL
- **Infra:** AWS S3 (almacenamiento de fotos), Clerk (auth), notificaciones Web Push, PWA con soporte offline
- **Arquitectura:** Backend modular (`reports`, `professionals`, `pharmacies`, `events`...) con separación router → service → data, rate limiting, API de analytics pública
- **Calidad:** Más de 270 tests
- 🟢 **Demo en vivo (Reconquista, Santa Fe):** [reportesreconquista.com](https://reportesreconquista.com)
- 💻 **Código:** [warning-app-front](https://github.com/emcon84/warning-app-front) · [warning-app-api](https://github.com/emcon84/warning-app-api)

## 📫 Contacto

- LinkedIn: [linkedin.com/in/emiliano-conti](https://www.linkedin.com/in/emiliano-conti)
- Email: emcon84@gmail.com

</details>
