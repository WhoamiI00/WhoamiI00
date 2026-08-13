<p align="center">
  <img src="https://raw.githubusercontent.com/WhoamiI00/WhoamiI00/main/assets/header.svg" alt="Ankit Raj — Full-Stack Engineer" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=500&size=22&duration=2600&pause=800&color=D9663F&center=true&vCenter=true&width=520&height=45&lines=Full-Stack+Developer;AI+Builder;Competitive+Programmer;Systems+Thinker;Frontend+Engineer" alt="Full-Stack Developer · AI Builder · Competitive Programmer" />
</p>

<p align="center">
  <a href="https://neokit.app"><img src="https://img.shields.io/badge/Portfolio-neokit.app-D9663F?style=for-the-badge&logoColor=ECE6DA&labelColor=0B0A09" alt="Portfolio" /></a>
  <a href="https://neokit.app/Ankit-Resume.pdf"><img src="https://img.shields.io/badge/Résumé-PDF-ECE6DA?style=for-the-badge&logo=readdotcv&logoColor=ECE6DA&labelColor=0B0A09" alt="Résumé" /></a>
  <a href="https://www.linkedin.com/in/ankit-raj-8043a32ba"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0B0A09" alt="LinkedIn" /></a>
  <a href="mailto:ankitpswd@gmail.com"><img src="https://img.shields.io/badge/Email-Reach%20out-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0B0A09" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=WhoamiI00&style=flat-square&color=D9663F&label=Profile+views" alt="Profile views" />
  <img src="https://img.shields.io/badge/Open%20to-Full--time%20·%20Freelance-3FCF8E?style=flat-square&labelColor=0B0A09" alt="Open to work" />
</p>

---

## 👋 About

> *A builder who likes the messy bit between the database and the user.*

I write code because I like the moment something I built actually works for someone else. **PawGle** started as a hackathon entry — ArcFace + a real workflow felt more interesting than another grade, so I kept shipping it after the weekend. A dozen projects later, the side stuff taught me the parts of full-stack you can only learn by doing them badly first; the production work is where it gets to matter.

- 🇯🇵 **Full Stack Engineer Intern @ [NeuralPort](https://neuralport.io)** — remote from India, building **ZEN EYE Pro**
- 🎓 **B.Tech CSE @ IIIT Jabalpur** (2023 – 2027)
- 🧩 **Codeforces Specialist** · **LeetCode Knight** · **CodeChef 4★** — 1000+ problems, 30+ contests
- 🌍 Jabalpur, India · `23.18° N / 79.98° E`
- 💬 Ask me about **computer vision**, **Scala/Play backends**, or **shipping under a 24h hackathon clock**

---

## 🔭 Currently Building

**ZEN EYE Pro** — a VR + eye-tracking cognitive-fatigue platform for athlete training.

I own the analytics dashboards in **Vue + TypeScript** and the data-ingest APIs in **Scala / Play Framework** backed by **PostgreSQL**.

<table>
  <tr>
    <td align="center"><b>200+</b><br/><sub>users</sub></td>
    <td align="center"><b>1,800+</b><br/><sub>sessions recorded</sub></td>
    <td align="center"><b>10K+</b><br/><sub>eye-tracking points / session</sub></td>
    <td align="center"><b>−50%</b><br/><sub>query downtime</sub></td>
    <td align="center"><b>−40%</b><br/><sub>coach review time</sub></td>
  </tr>
</table>

---

## 🚀 Featured Work

### 🏛️ Fusion-VMS — *Visitor Management for a production ERP*

A full Visitor Management module landed on **[Fusion](http://fusion.iiitdmj.ac.in/)**, IIIT Jabalpur's live ERP. **10K+ lines** across Django and React: 34 REST endpoints, 6-tier RBAC, QR pass issuance, escort assignment, blacklist + VIP flows, PDF reporting. I **led a 3-person team** and authored both PRs end-to-end.

`Django` `DRF` `PostgreSQL` `React` `Celery` `RBAC`
&nbsp;·&nbsp; [Backend PR ↗](https://github.com/FusionIIIT/Fusion/pull/1896) &nbsp;·&nbsp; [Frontend PR ↗](https://github.com/FusionIIIT/Fusion-client/pull/226) &nbsp;·&nbsp; [Live ERP ↗](http://fusion.iiitdmj.ac.in/)

### 🐾 PawGle — *Face recognition for pets*

Find a lost animal by uploading a photo. Fine-tuned **ResNet-50 with ArcFace loss** producing 128-dim embeddings, matched by cosine similarity at a 0.9 threshold. Trained on ~10K cat/dog images over 20 epochs → **94% validation accuracy**. Shipped as a Django + Next.js app with a secure email-relay Lost & Found flow.

`ResNet-50` `ArcFace` `TensorFlow` `Django` `Next.js` `HuggingFace` `Docker`
&nbsp;·&nbsp; [Live ↗](https://pawgle.neokit.app) &nbsp;·&nbsp; [Case study ↗](https://neokit.app/work/pawgle) &nbsp;·&nbsp; [Frontend ↗](https://github.com/WhoamiI00/PawGleFrontend) &nbsp;·&nbsp; [Backend ↗](https://github.com/WhoamiI00/PawGleBackend)

### 🛣️ VISTA-R1 — *Pixel-level pavement crack detection*

**Attention U-Net** trained on 3,500 high-res pavement images for semantic segmentation. **Dice 63.67%** on a brutally imbalanced dataset (cracks ≈ 2% of pixels), precision 64.24% / recall 63.12% across 3.15M test pixels. Early-stopped at epoch 72/80 after ~6.5h on an RTX 3080.

`PyTorch` `Attention U-Net` `Dice Loss` `CUDA`
&nbsp;·&nbsp; [Case study ↗](https://neokit.app/work/vista) &nbsp;·&nbsp; [Code ↗](https://github.com/WhoamiI00/VISTA)

### 🎥 NeoCast — *Video platform with AI transcripts*

Screen-recording and sharing platform supporting 100+ concurrent users. AI-generated transcripts across 500+ videos lifted keyword discoverability **+40%**. Token auth validated across 500+ sessions; Arcjet bot protection stress-tested at 60 req/min with 100% uptime.

`Next.js` `TypeScript` `Bunny.net` `Xata` `Drizzle ORM` `Arcjet`
&nbsp;·&nbsp; [Live ↗](https://cast.neokit.app) &nbsp;·&nbsp; [Code ↗](https://github.com/WhoamiI00/NeoCast)

<details>
<summary><b>📦 More projects</b> — mobile, tooling, and web</summary>

<br/>

| Project | What it is | Stack | Links |
|---|---|---|---|
| **NeoVids** | Cross-platform video app — cut buffering **−40%** via adaptive bitrate streaming, **−20%** server requests | React Native · Expo · Appwrite · FFmpeg | [Code](https://github.com/WhoamiI00/NeoVids) |
| **Imaginify** | AI image generation and transformation platform | Next.js · TypeScript · AI APIs | [Live](https://imaginify-beta-tawny.vercel.app) · [Code](https://github.com/WhoamiI00/Imaginify) |
| **FigLite** | Lightweight collaborative design canvas, multiplayer-ready | TypeScript · React · Canvas API | [Live](https://fig.neokit.app) · [Code](https://github.com/WhoamiI00/FigLite) |
| **NeoPrep** | AI-driven interview prep with structured drills + feedback loops | Next.js · TypeScript | [Live](https://neo-prep.vercel.app) · [Code](https://github.com/WhoamiI00/NeoPrep) |
| **neo-pins** | Pinterest-style visual discovery board | TypeScript · Next.js | [Live](https://pins.neokit.app) · [Code](https://github.com/WhoamiI00/neo-pins) |
| **neuro-track** | Vue app exploring neuro-style tracking flows | Vue.js · TypeScript | [Live](https://neuro-track.vercel.app) · [Code](https://github.com/WhoamiI00/neuro-track) |
| **Fizzy** | Modern collaborative web app on Prismic CMS | TypeScript · Next.js · Prismic | [Live](https://fizzy-theta.vercel.app) · [Code](https://github.com/WhoamiI00/Fizzy) |
| **NeoChat** | Clean realtime chat experience | TypeScript · Next.js | [Live](https://neo-chat-indol.vercel.app) · [Code](https://github.com/WhoamiI00/NeoChat) |
| **SportyIndia** | Sports platform for the Indian market, realtime updates | Next.js · React · Tailwind | [Live](https://sporty-india-521t.vercel.app) · [Code](https://github.com/WhoamiI00/SportyIndia) |

</details>

---

## 🛠️ Tech Stack

**Languages**

[![Languages](https://skillicons.dev/icons?i=py,java,cpp,c,js,ts,scala,php,bash&theme=dark)](https://skillicons.dev)

**Frontend**

[![Frontend](https://skillicons.dev/icons?i=react,nextjs,vue,redux,threejs,tailwind,html,css&theme=dark)](https://skillicons.dev)

**Backend & Databases**

[![Backend](https://skillicons.dev/icons?i=nodejs,express,django,flask,postgres,mysql,mongodb,sqlite,supabase,appwrite&theme=dark)](https://skillicons.dev)

**AI/ML, Infra & Tooling**

[![Infra](https://skillicons.dev/icons?i=tensorflow,pytorch,docker,gcp,azure,cloudflare,vercel,git,github&theme=dark)](https://skillicons.dev)

<sub>Also: Play Framework (Scala) · Drizzle ORM · Xata · Bunny.net · FFmpeg · ABR streaming · Arcjet · HuggingFace · Resend</sub>

---

## ⚔️ Competitive Programming

<p>
  <a href="https://codeforces.com/profile/kurumi_0_0"><img src="https://img.shields.io/badge/Codeforces-Specialist%20·%201450%20max-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white&labelColor=0B0A09" alt="Codeforces" /></a>
  <a href="https://leetcode.com/kurumi_0_0"><img src="https://img.shields.io/badge/LeetCode-Knight%20·%201900-FFA116?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=0B0A09" alt="LeetCode" /></a>
  <a href="https://codechef.com/users/nexus_neon"><img src="https://img.shields.io/badge/CodeChef-4★%20·%201800-5B4638?style=for-the-badge&logo=codechef&logoColor=white&labelColor=0B0A09" alt="CodeChef" /></a>
</p>

**1000+ problems solved · 30+ rated contests** — 400 on Codeforces, 300 on CodeChef, 600 on LeetCode (180 easy / 320 medium / 100 hard).

---

## 🌱 Open Source & Certifications

- ✅ **[Appwrite Console #2677](https://github.com/appwrite/console/pull/2677) — merged** · `fix(migrations): redirect 404 on self-hosted instances`
- 🔧 Contributor across **Appwrite**, **Supabase**, **Zulip**, and **Wagtail**
- ☁️ **[Google Cloud Skills Boost Specialist](https://www.cloudskillsboost.google/public_profiles/4c07885e-d3a2-4b07-9143-c9cadf7a4b09)** — 57 skill badges, 74,000+ XP
- 🤖 **[NVIDIA DLI](https://learn.nvidia.com/certificates?id=SU3ZxWRbTAWMM_VRjFKazg)** — Building LLM Applications with Prompt Engineering

---

## 🐍 Contribution Graph

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/WhoamiI00/WhoamiI00/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/WhoamiI00/WhoamiI00/output/github-contribution-grid-snake.svg" />
    <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/WhoamiI00/WhoamiI00/output/github-contribution-grid-snake-dark.svg" />
  </picture>
</p>

---

## 📫 Let's Build Something

I'm looking for a **full-time full-stack seat at an early-stage startup** — somewhere I can ship end-to-end alongside engineers I'll learn from. Open to freelance and contract work too.

<p>
  <a href="https://neokit.app"><img src="https://img.shields.io/badge/neokit.app-D9663F?style=flat-square&logo=safari&logoColor=white&labelColor=0B0A09" alt="Portfolio" /></a>
  <a href="mailto:ankitpswd@gmail.com"><img src="https://img.shields.io/badge/ankitpswd@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white&labelColor=0B0A09" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/ankit-raj-8043a32ba"><img src="https://img.shields.io/badge/ankit--raj-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0B0A09" alt="LinkedIn" /></a>
  <a href="https://github.com/WhoamiI00"><img src="https://img.shields.io/badge/@WhoamiI00-181717?style=flat-square&logo=github&logoColor=white&labelColor=0B0A09" alt="GitHub" /></a>
</p>

<br/>

<p align="center">
  <sub><i>Open-source contributor · Performance optimization enthusiast · Always learning</i></sub>
</p>
