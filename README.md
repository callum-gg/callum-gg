# Hi, I'm Callum

I build across algorithmic trading systems, AI-driven media pipelines, live game infrastructure for a multiplayer roleplay community, and full-stack web apps — usually TypeScript or Python on top, whatever the problem needs underneath.

*Some repos below are private — the links won't resolve for other visitors, but the descriptions give you the full picture.*

## Stack I reach for

**Languages:** TypeScript, Python, Go, C++, C#, Lua
**Backend:** Express, Fastify, FastAPI, Flask
**Data:** PostgreSQL, MySQL, Redis, SQLite
**ML/AI:** PyTorch, scikit-learn, XGBoost/LightGBM, Hugging Face, OpenAI-compatible LLM APIs
**Infra:** Docker, GitHub Actions, systemd

## Projects

- [Trading & Finance](#trading--finance)
- [AI & Media](#ai--media)
- [Metropolitan RP / FiveM Roleplay Community](#metropolitan-rp--fivem-roleplay-community)
- [Personal Sites & Portfolio](#personal-sites--portfolio)
- [Other Web Apps](#other-web-apps)
- [Systems & Hardware](#systems--hardware)
- [Hackathon Projects](#hackathon-projects-durham-university-durhack)
- [Coursework & Early Learning](#coursework--early-learning)

### Trading & Finance

- **[trading](https://github.com/callum-gg/trading)** *(private)* — AI/ML-driven trading platform that predicts and executes trades across stocks, crypto, and other assets. Redis-backed real-time data pipeline, feature engineering, a backtesting engine with realistic constraints, paper/live execution, and automatic model retraining. `Python · FastAPI · PyTorch/scikit-learn/LightGBM · Redis · Prisma · TypeScript · Android`
- **[go-trader](https://github.com/callum-gg/go-trader)** *(private)* — Hybrid Go + Python crypto trading bot running 30+ paper strategies across spot (Binance) and options (Deribit, IBKR/CME) markets. A lightweight Go scheduler spawns short-lived Python strategy runs and reports live P&L to Discord. `Go · Python · CCXT · XGBoost/LightGBM`

### AI & Media

- **[non-stop-pop](https://github.com/callum-gg/non-stop-pop)** *(private)* — Browser-based, GTA-style radio station: AI-generated DJ links, satirical news, and fake ads mixed with real music, with graceful fallback to prerecorded segments so the stream never drops. `TypeScript · Next.js · Web Audio API · LLM + TTS integration`
- **[AI-Socials](https://github.com/callum-gg/AI-Socials)** *(private)* — Automates short-form video generation (AI storyboards, DALL-E images, TTS narration) and multi-platform publishing to YouTube, TikTok, Instagram, and Facebook on a schedule. `Python · FastAPI · SQLAlchemy · APScheduler`
- **[referee-decisions](https://github.com/callum-gg/referee-decisions)** *(private)* — Multimodal computer vision system that classifies football referee decisions from match video and audio, with a hierarchical decision taxonomy and timestamped, confidence-scored output. `Python · PyTorch · OpenCV · SlowFast/YAMNet · FastAPI`
- **[fpl-ai](https://github.com/callum-gg/fpl-ai)** *(public)* - Web server and AI system to produce a team for the FPL fantasy football league. First used in the 2026/27 season.

### Metropolitan RP / FiveM Roleplay Community

A multi-year roleplay community I've built and maintained end-to-end — dispatch systems, the community website, Discord tooling, and the in-game gameplay resources themselves.

- **[cad.metropolitanrp.com](https://github.com/callum-gg/cad.metropolitanrp.com)** *(private)* — Computer-Aided Dispatch system with web and in-game FiveM clients, real-time dispatch over Socket.io, and Discord authentication. `TypeScript · Express · MikroORM · Socket.io`
- **[metropolitanrp.com](https://github.com/callum-gg/metropolitanrp.com)** *(private)* — The community's main site: real-time chat, Discord/local auth, an integrated CAD system, and a PayPal-powered in-game store. `TypeScript · Express/Fastify · MikroORM · Socket.io`
- **[metrorp-resources](https://github.com/callum-gg/metrorp-resources)** *(private)* — Server-side gameplay resource pack covering vehicle systems, heists, police dashcam footage, and realistic fuel/damage mechanics. `Lua · ESX · FivePD · Vue (NUI)`
- **[metrorp-discord](https://github.com/callum-gg/metrorp-discord)** *(private)* — Discord bot for job postings, embed creation, and file management, backed by MySQL. `discord.js · MySQL`
- **[fivepd.callumg.net](https://github.com/callum-gg/fivepd.callumg.net)** *(private)* — Express server rendering dynamic pages for a FivePD police-roleplay resource. `Node.js · Express`
- **[fiveom](https://github.com/callum-gg/fiveom)** *(private)* — Earlier police-roleplay FiveM mod with an RPC-style client/server framework, NUI overlays, and procedural callout generation. `Lua · JavaScript/HTML/CSS`
- **[cpfpd-scripts](https://github.com/callum-gg/cpfpd-scripts)** *(private)* — Lua script collection for a fictional PD roleplay server: actions, UI, vehicle customization, and Discord integration. `Lua · NativeUI/RageUI`
- **[cpfpd-discord-bot](https://github.com/callum-gg/cpfpd-discord-bot)** *(private)* — Discord bot for the Calcium & Paddy's FivePD community. `discord.js`
- **[shoreline](https://github.com/callum-gg/shoreline)** *(private)* — ESX-based FiveM framework with SonoraCAD-integrated dispatch across 50+ custom resources. `Lua · ESX · MySQL · SonoraCAD API`

### Personal Sites & Portfolio

- **[Stratus](https://github.com/callum-gg/Stratus)** *(private)* — Full-stack portfolio/project showcase with a JWT-authenticated admin API and Multer-based media uploads. `TypeScript · Express · Vite`
- **[callumg.net](https://github.com/callum-gg/callumg.net)** *(private)* — Personal project dashboard with GitHub integration, commit history browsing, and an AI agent (OpenClaw) for chat and project creation. `JavaScript · Express · Sequelize · WebSockets`
- **[callumg.net-old](https://github.com/callum-gg/callumg.net-old)** *(private)* — Earlier personal site with multi-subdomain routing and templated server-side rendering. `Node.js · Express`
- **[callumg.net-old-](https://github.com/callum-gg/callumg.net-old-)** *(private)* — Earliest iteration, with Discord OAuth, MySQL persistence, and dual HTTP/HTTPS serving. `Node.js · Express · Passport`

### Other Web Apps

- **[cycles](https://github.com/callum-gg/cycles)** *(private)* — Road bike customization platform with a layered bike-builder UI, Google/Apple OAuth, and PayPal checkout. `TypeScript · Express · MikroORM · Vite`

### Systems & Hardware

- **[TSM](https://github.com/callum-gg/TSM)** *(private, active development)* — Adds multiplayer networking to Train Sim World via a UE4SS client mod, an ENet UDP server, and a standalone launcher. Core networking is live; gameplay synchronization is in progress. `C++23 · Go · Lua · ENet · ImGui`
- **[desk-controller](https://github.com/callum-gg/desk-controller)** *(public)* — Raspberry Pi desk peripheral switcher: a Flask web UI drives GPIO relays to flip USB/HDMI between two machines. `Python · Flask · RPi.GPIO`

### Hackathon Projects (Durham University DurHack)

- **[DurHack24](https://github.com/callum-gg/DurHack24)** *(public)* — Chatbot web app on Botpress Cloud, with a polling-based REST API and a Framework7 frontend.
- **[DurHack23](https://github.com/callum-gg/DurHack23)** *(public)* — Document tool chaining Google Vision OCR, Bing spell-check, and Google Cloud Translation for multi-lingual document analysis.
- **[DurHack2022](https://github.com/callum-gg/DurHack2022)** *(public)* — "Vinnie's Tinnies": a pub-crawl route optimizer using Google OR-Tools' TSP solver and the Google Maps Distance Matrix API.

### Coursework & Early Learning

- **[ProgrammingProject](https://github.com/callum-gg/ProgrammingProject)** *(private)* — Space-Track API client pulling Starlink satellite catalog data.
- **[LangtonsAnt](https://github.com/callum-gg/LangtonsAnt)** *(private)* — C implementation of Langton's Ant cellular automaton with real-time ncurses visualization.
- **[projects](https://github.com/callum-gg/projects)** *(private)* — Early portfolio monorepo: FiveM gameplay scripts, a Discord bot, a POS system, and a Tkinter timetable planner.
