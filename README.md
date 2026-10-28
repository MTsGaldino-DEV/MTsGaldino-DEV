<!-- ============ HEADER ============ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1b1324,50:57406b,100:c3a6e8&height=200&section=header&text=Matheus%20Galdino&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Full-Stack%20Developer%20%E2%80%A2%20Web%20%2B%20Mobile&descAlignY=58&descSize=18" width="100%" alt="Matheus Galdino" />
</p>

<p align="center">
  <a href="https://github.com/MTsGaldino-DEV">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=C3A6E8&center=true&vCenter=true&width=640&lines=I+build+software+that+runs+real+operations.;React+%C2%B7+Next.js+%C2%B7+React+Native+%C2%B7+Expo;Supabase+%C2%B7+PostgreSQL+%C2%B7+NestJS+%C2%B7+Docker;No+matter+the+problem%2C+I'll+solve+it.;Open+to+remote+roles+%F0%9F%8C%8D+EU+%C2%B7+UK+%C2%B7+US" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/matheus-galdino-4a1359328/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:matheusgaldinogv@hotmail.com"><img src="https://img.shields.io/badge/Email-57406b?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=MTsGaldino-DEV&color=57406b&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

### `> whoami`

```ts
const matheus = {
  role: "Full-Stack Developer",
  location: "Minas Gerais, Brazil 🇧🇷 (UTC-3)",
  builds: ["Internal tools", "Web apps", "Mobile apps", "Automations"],
  stack: {
    frontend: ["TypeScript", "React", "Next.js", "React Native", "Expo", "Vite"],
    backend: ["Supabase", "PostgreSQL", "Node.js", "NestJS", "Prisma"],
    quality: ["RLS", "pgTAP", "Vitest", "Playwright"],
    infra: ["Docker", "Vercel", "Cloudflare Tunnel", "n8n"],
  },
  superpower: "Turning messy business processes into software people actually use",
  currentlyLearning: ["Python"],
  openTo: "Remote full-stack roles — Europe · UK · US",
};
```

I'm a self-taught developer who learned by **shipping**. I work inside an electrical utility services company, where I design and build the systems the operation runs on: warehouse control, field service management, health & safety compliance, dispatch and approval flows — from the database schema to the app in the technician's hands.

I like putting business rules **where they can't be bypassed**: in the database, with row-level security, transactional functions and tests that prove them. I understand the business side first, then write the code. That's what makes the software stick.

---

### 🚀 Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🏭 Warefly</h4>
      <p>Warehouse management for a regional warehouse and <b>11 field bases</b>, running alongside SAP. Tracks what each base requested, what was shipped and what actually arrived. Stock is an <b>immutable ledger</b> — balance is always the sum of movements and can never go negative. Rules enforced in Postgres (RLS + RPCs) and proven by <b>262 pgTAP checks</b>, Vitest and Playwright E2E. Ships with its own design system and lint rules.</p>
      <p>
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
        <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      </p>
      <a href="https://warefly.vercel.app">Live →</a> &nbsp;·&nbsp; <a href="https://github.com/MTsGaldino-DEV/warefly">Code →</a>
    </td>
    <td width="50%" valign="top">
      <h4>🩺 GIRO</h4>
      <p>Occupational health compliance for field crews: every expiring medical exam becomes a <b>task with an owner and an SLA</b>. The workflow <b>state machine lives in the database</b> — security-definer functions and triggers reject illegal transitions and write a full audit trail, even for manual edits. RLS isolates each supervisor's team; Vercel Cron generates tasks daily and sends weekly email digests.</p>
      <p>
        <img src="https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
        <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
      </p>
      <a href="https://giro-neon.vercel.app">Live →</a> &nbsp;·&nbsp; <a href="https://github.com/MTsGaldino-DEV/GIRO">Code →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🛒 Oferta Hub</h4>
      <p>Control panel for running a WhatsApp deals community. Pulls products from <b>6 affiliate APIs</b> (Amazon, Mercado Livre, Shopee, AliExpress, Awin, Lomadee), keeps price history, <b>scores every offer 0–100</b> and only sends after human approval. Background workers, click tracking via short links and AES-256-GCM encrypted credentials.</p>
      <p>
        <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      </p>
      <a href="https://github.com/MTsGaldino-DEV/oferta-hub">Code →</a>
    </td>
    <td width="50%" valign="top">
      <h4>🔌 Visão de Dono</h4>
      <p>Field service management for power-grid contractors: a <b>web dashboard</b> for dispatch plus an <b>Android app</b> for technicians. Jobs on a map with routing, one active job per crew, mandatory before/after photo evidence with GPS stamp, and field surveys with duplicate detection. Migrated from Firebase to Supabase with RLS per team.</p>
      <p>
        <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" />
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
        <img src="https://img.shields.io/badge/Google_Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white" />
      </p>
      <a href="https://github.com/MTsGaldino-DEV/visao-de-dono-app">App →</a> &nbsp;·&nbsp; <a href="https://github.com/MTsGaldino-DEV/visao-de-dono">Web →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>📦 TraceOne</h4>
      <p>Inventory control & traceability platform. Monorepo with a <b>Next.js</b> frontend and a <b>NestJS</b> API on PostgreSQL, with spreadsheet import and Docker setup. Deployed on Vercel.</p>
      <p>
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      </p>
      <a href="https://traceone-sigma.vercel.app">Live →</a> &nbsp;·&nbsp; <a href="https://github.com/MTsGaldino-DEV/traceone">Code →</a>
    </td>
    <td width="50%" valign="top">
      <h4>📋 Central de Ocorrências</h4>
      <p>Occurrence center for field dispatch. Dispatchers log incidents with <b>photo evidence</b>; supervisors approve or reject with feedback, updated <b>in real time</b> over WebSockets. Role-based access, private storage buckets and RLS tied to auth users.</p>
      <p>
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
        <img src="https://img.shields.io/badge/Supabase_Realtime-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
      </p>
      <a href="https://github.com/MTsGaldino-DEV/central-nec">Code →</a>
    </td>
  </tr>
</table>

<sub>Also built: <a href="https://upmusic-iota.vercel.app">UPMusic GV</a> (landing page for a music school, Next.js) · <a href="https://nerdrop-links.vercel.app">NerdDrop</a> (link page for a deals community) · <a href="https://github.com/MTsGaldino-DEV/central-neo">Central NEO</a> (operations hub, Vite + TS)</sub>

---

### 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,vite,tailwind,nodejs,nestjs&theme=dark" alt="Languages and frameworks" /><br/>
  <img src="https://skillicons.dev/icons?i=supabase,postgres,prisma,firebase,docker,cloudflare,vercel&theme=dark" alt="Data and infra" /><br/>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,androidstudio,linux&theme=dark" alt="Tools" />
</p>

---

### 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=MTsGaldino-DEV&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&bg_color=1b1324&title_color=c3a6e8&icon_color=e8955a&text_color=c9d1d9&rank_icon=github" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MTsGaldino-DEV&layout=compact&langs_count=6&hide_border=true&bg_color=1b1324&title_color=c3a6e8&text_color=c9d1d9" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=MTsGaldino-DEV&hide_border=true&background=1B1324&ring=8E6FB8&fire=E8955A&currStreakLabel=C3A6E8&sideLabels=C9D1D9&dates=8B949E&currStreakNum=FFFFFF&sideNums=FFFFFF" alt="Streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=MTsGaldino-DEV&bg_color=1b1324&color=c9d1d9&line=8e6fb8&point=e8955a&area=true&area_color=57406b&hide_border=true" alt="Activity graph" />
</p>

<!-- Snake: gerada pelo workflow .github/workflows/snake.yml -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MTsGaldino-DEV/MTsGaldino-DEV/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MTsGaldino-DEV/MTsGaldino-DEV/output/github-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/MTsGaldino-DEV/MTsGaldino-DEV/output/github-snake-dark.svg" />
  </picture>
</p>

---

<details>
<summary><b>🇧🇷 Leia em português</b></summary>
<br/>

Sou desenvolvedor full-stack autodidata e aprendi **construindo**. Trabalho numa empresa de serviços para o setor elétrico, onde projeto e desenvolvo os sistemas que sustentam a operação: almoxarifado, gestão de serviços de campo, conformidade de saúde ocupacional, despacho e fluxos de aprovação — do banco de dados ao app na mão do técnico.

Gosto de colocar as regras de negócio **onde não dá pra burlar**: no banco, com RLS, funções transacionais e testes que provam que elas funcionam. Primeiro entendo o negócio, depois escrevo o código.

**Stack:** TypeScript, React, Next.js, React Native/Expo, Supabase, PostgreSQL, NestJS, Docker.
**Contato:** [LinkedIn](https://www.linkedin.com/in/matheus-galdino-4a1359328/) · [matheusgaldinogv@hotmail.com](mailto:matheusgaldinogv@hotmail.com)

</details>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:c3a6e8,50:57406b,100:1b1324&height=110&section=footer" width="100%" alt="" />
</p>
