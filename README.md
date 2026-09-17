## Hi 👋, I'm Russell

**Senior Software Engineer | Digital Health | AI & Scalable Systems**

I design and build **production-grade software systems** across healthcare, AI, and enterprise platforms. My work focuses on **scalable architectures, data-intensive applications, and secure system design**, particularly in **digital health and EMR systems**.

### 🔗 Connect with me

<a href="https://github.com/RussellJapheth" target="_blank" rel="noopener">
<img src="https://img.shields.io/badge/GitHub-%2324292e.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="https://dev.to/_russell" target="_blank" rel="noopener">
<img src="https://img.shields.io/badge/Dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" alt="Dev.to" />
</a>
<a href="https://twitter.com/the_e_3" target="_blank" rel="noopener">
<img src="https://img.shields.io/badge/Twitter-%2300acee.svg?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
</a>
<a href="https://linkedin.com/in/japheth-russell" target="_blank" rel="noopener">
<img src="https://img.shields.io/badge/LinkedIn-%231E77B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://medium.com/russell_japheth" target="_blank" rel="noopener">
<img src="https://img.shields.io/badge/Medium-%23292929.svg?style=for-the-badge&logo=medium&logoColor=white" alt="Medium" />
</a>
<a href="https://linktr.ee/russelljapheth" target="_blank" rel="noopener">
<img src="https://img.shields.io/badge/Linktree-%2343a047.svg?style=for-the-badge&logo=linktree&logoColor=white" alt="Linktree" />
</a>

📫 Open to **senior engineering roles, technical consulting, and collaboration** — reach me on [LinkedIn](https://linkedin.com/in/japheth-russell) or open an issue on any repo.

## 🚀 Current Focus

* 🔭 Building **AI-powered health systems** including diagnostic and risk assessment tools
* 🧠 Applying **Machine Learning & Computer Vision** to disease detection (mpox, imaging workflows)
* 🏥 Developing **EMR / HMS platforms** with offline-first architecture and NDPR-compliant data security
* ⚙️ Designing **distributed systems, APIs, and cloud-native infrastructure**

## 💡 What I Bring

* **Fullstack Engineering**: Frontend, backend, and system design
* **Cloud & DevOps**: CI/CD, containerisation, infrastructure automation
* **Digital Health Expertise**: EMR systems, interoperability, health data pipelines
* **AI Systems**: Model training, inference pipelines, and real-world deployment
* **Performance & Scalability**: Optimised systems for high-load environments

## 🛠️ Tech Stack

**Languages**
`TypeScript` `JavaScript` `Python` `Go` `PHP` `SQL` `Bash`

**Frontend**
`React` `Svelte` `SvelteKit` `Vue` `Angular` `Redux`
`TailwindCSS` `Bootstrap` `Sass` `HTML5` `CSS3`
`HTMX` `Alpine.js`

**Backend & APIs**
`Node.js` `Express` `NestJS`
`Django` `Flask` `FastAPI`
`Laravel` `CodeIgniter`
`REST` `GraphQL`

**Databases & Caching**
`PostgreSQL` `MySQL` `MariaDB` `MongoDB`
`Redis` `SQLite`

**Cloud, DevOps & Infra**
`Docker` `AWS` `GCP` `Nginx` `Linux` `Jenkins`

**Messaging & Systems**
`Kafka` `RabbitMQ`

**Mobile & Cross-Platform**
`Cordova` `NativeScript` `Electron`

**AI / Data**
`ONNX Runtime` `InsightFace` `OpenCV` `CLIP`
Machine Learning, Computer Vision, Inference Pipelines

**Tools & Platforms**
`Git` `Postman` `Figma` `Firebase` `Heroku` `Appwrite`
`Bun` `PM2` `Netlify`

## 🧪 Highlight Projects

### [Kimera](https://github.com/RussellJapheth/kimera)

Fully **offline, self-hosted media gallery** with state-of-the-art **face recognition and clustering** — Google Photos–style people organization with no cloud, no telemetry, and no data leaving your machine.

* Local inference via **ONNX Runtime**: InsightFace `buffalo_l` (SCRFD detector + ArcFace ResNet-50, 512-d embeddings) with CPU/GPU auto-selection
* **Multi-algorithm face clustering** — agglomerative, DBSCAN, Chinese Whispers, HDBSCAN — plus multi-exemplar identity matching and intra-video face merge
* **CLIP visual embeddings** for similarity search and automatic tag suggestions
* **FastAPI + HTMX/Alpine.js** gallery over SQLite, with a WebP thumbnail cache and FFmpeg video keyframe sampling
* [`github.com/RussellJapheth/kimera`](https://github.com/RussellJapheth/kimera) · AGPL-3.0 · 87 tests passing

### [FlashCards](https://github.com/RussellJapheth/flash-two)

A modern, **offline-first spaced repetition flashcards app** for learning languages, built with Svelte 5.

* **SM-2-inspired scheduler** with per-deck review queues and due-date spread (`src/lib/utils/srs.ts`)
* **Offline-first**: study data persists in the browser (IndexedDB) with a service worker and debounced background sync to a small JSON API
* **Chinese learning focus**: HSK-aligned decks, pinyin, tones, tone-sandhi detection, and cloze (sentence-fill) practice with multiple accepted answers
* **Speech practice** via the Web Speech API with accuracy evaluation, plus arcade games (Match Blitz, Number Rush) with combo scoring
* **Progress system**: XP, levels, streaks (with streak freezes), milestones, and weekly/monthly leaderboards
* **SvelteKit + TypeScript + Tailwind CSS v4**, deployed on Netlify · AGPL-3.0

### [Cliff-Drop](https://github.com/RussellJapheth/cliff-drop)

A **self-hosted, cross-device text and file sharing app** inspired by Microsoft Edge Drop — single-user, minimal, and secure.

* **Real-time sync** over native WebSockets with a chat-style timeline, sticky day grouping, and lazy loading
* Text/link sharing, drag-and-drop **multi-file uploads**, clipboard paste, and EXIF-aware thumbnails via `sharp`
* Password auth with **Argon2id** + HTTP-only cookies; SQLite through **Drizzle ORM** (local or Turso) and local/S3-compatible storage
* **SvelteKit + Tailwind CSS**, PWA-installable · MIT

### [Focus Flow](https://github.com/RussellJapheth/focus-flow)

A simple, elegant **Pomodoro-style work timer and todo list**.

* Customizable interval timer paired with a persistent task list
* **Fully client-side** — tasks and settings stay in `localStorage`, no account required
* **SvelteKit + Tailwind CSS + Bun**, deployable to Netlify or any SvelteKit adapter · GLWTPL

### CheckLens *(proprietary)*

AI-powered web platform for **mpox risk assessment** using image classification.

* Computer vision model for symptom detection
* Real-time inference pipeline
* Healthcare-focused risk scoring system
* Designed for **scalability and field usability**

## 📦 More Open Source

A few other public repos:

* [**Rcopy**](https://github.com/RussellJapheth/Rcopy) — curl-based remote file copy with a CLI, real-time progress, and resumable downloads
* [**CheckIN**](https://github.com/RussellJapheth/CheckIN) — a streak calendar built with SvelteKit
* [**my-minimal-finance**](https://github.com/RussellJapheth/my-minimal-finance) — privacy-focused personal finance tracker, fully in-browser (IndexedDB)
* [**codeigniter4-db-explorer**](https://github.com/RussellJapheth/codeigniter4-db-explorer) — interactive terminal database explorer/editor for CodeIgniter 4

## 📊 Areas of Expertise

* Software Engineering
* Full Stack Development
* System Architecture
* Cloud Computing
* DevOps Engineering
* Machine Learning
* Computer Vision
* Digital Health
* Electronic Medical Records (EMR)
* Health Information Systems (HIS)
* API Design & Integration
* Distributed Systems
* Data Engineering
* Secure Systems (NDPR Compliance)

## ⚡ Quick Notes

* 💬 Open to discussions on **software engineering, AI, and system design**
* 🧩 Strong focus on **real-world problem solving and production systems**
* 🛠️ Building **open-source, offline-first AI tools** (see [Kimera](https://github.com/RussellJapheth/kimera))
* ⚙️ Preference: **spaces over tabs**
