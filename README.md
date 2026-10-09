<div align="center">

# WildanDeveloper

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=1000&color=FFD700&center=true&vCenter=true&width=760&lines=Systems+Programmer+%7C+Rust+%26+C%2B%2B;Infrastructure+Engineer+%7C+Docker+%26+K8s;Security+Researcher+%7C+Offensive+Tooling;Game+Server+Engineer+%7C+ENet+%26+MariaDB" alt="Typing SVG" />

[![Profile views](https://komarev.com/ghpvc/?username=WildanDeveloper&label=Views&color=FFD700&style=for-the-badge)](https://github.com/WildanDeveloper)
[![Followers](https://img.shields.io/github/followers/WildanDeveloper?color=FFD700&style=for-the-badge&label=Followers)](https://github.com/WildanDeveloper?tab=followers)
[![Repos](https://img.shields.io/github/repos/WildanDeveloper?color=FFD700&style=for-the-badge&label=Repos)](https://github.com/WildanDeveloper?tab=repositories)
[![Since](https://img.shields.io/badge/since-Jun%202025-FFD700?style=for-the-badge)](https://github.com/WildanDeveloper)

</div>

---

## About

I build software that has to survive contact with production — **compilers and
runtimes, network daemons, game servers, and the offensive tooling that breaks
them.**

The common thread is systems work. I care about what actually happens at the
byte level, how a workload behaves under load, and where the trust boundary
really sits.

- **Systems programming** — languages, runtimes, and daemons in Rust and C++
- **Infrastructure** — self-hosted hosting stacks, node agents, container orchestration
- **Security research** — scanners, OSINT tooling, AI-assisted penetration testing
- **Game servers** — Growtopia private servers, protocol-compatible implementations

Most of my projects start as *"does this need to exist?"* and end as a
single binary with no runtime dependencies.

---

## Featured work

<a href="https://github.com/WildanDeveloper/wlel"><img src="https://github-readme-stats.vercel.app/api/pin/?username=WildanDeveloper&repo=wlel&theme=github_dark&show_owner=false&hide_border=true&border_color=FFD700" width="49%" alt="wlel"></a>
<a href="https://github.com/WildanDeveloper/roost"><img src="https://github-readme-stats.vercel.app/api/pin/?username=WildanDeveloper&repo=roost&theme=github_dark&show_owner=false&hide_border=true&border_color=FFD700" width="49%" alt="roost"></a>
<br>
<a href="https://github.com/WildanDeveloper/WEngine"><img src="https://github-readme-stats.vercel.app/api/pin/?username=WildanDeveloper&repo=WEngine&theme=github_dark&show_owner=false&hide_border=true&border_color=FFD700" width="49%" alt="WEngine"></a>
<a href="https://github.com/WildanDeveloper/GTPS"><img src="https://github-readme-stats.vercel.app/api/pin/?username=WildanDeveloper&repo=GTPS&theme=github_dark&show_owner=false&hide_border=true&border_color=FFD700" width="49%" alt="GTPS"></a>
<br>
<a href="https://github.com/WildanDeveloper/argus"><img src="https://github-readme-stats.vercel.app/api/pin/?username=WildanDeveloper&repo=argus&theme=github_dark&show_owner=false&hide_border=true&border_color=FFD700" width="49%" alt="argus"></a>
<a href="https://github.com/WildanDeveloper/webstats"><img src="https://github-readme-stats.vercel.app/api/pin/?username=WildanDeveloper&repo=webstats&theme=github_dark&show_owner=false&hide_border=true&border_color=FFD700" width="49%" alt="webstats"></a>

<br>

### 🦀 wlel

**An arena-first systems programming language.** Compiles to native code.
Zero leaks by construction — every allocation inside an `arena` block is an
O(1) pointer bump, reclaimed when the block exits.

```wl
arena(1 << 20) {
    // no free() needed, ever
}
```

`Rust` · CI, fuzz targets, and a test suite

### 🦅 roost

**A drop-in replacement for the Pterodactyl Wings daemon, rewritten in Rust.**
Any Pterodactyl-compatible panel manages containers on this node exactly as it
would with the official daemon — no panel modifications required.

`Rust` + tokio · MIT · 38/38 Wings API conformance tests passing

### 🧠 WEngine

**A blazing-fast CPU-first AI inference engine.** Rust core with C++ / AVX-512
acceleration.

### 🎮 GTPS

**A Growtopia private server in a single C++ binary.** ENet game server, HTTPS
login service, and web account management in one process, backed by MariaDB.
Login flow for modern clients (protocol 226, web-token based) with pending-auth
resume bound to client IP.

`C++` · `ENet` · `MariaDB`

### 🔭 argus

**A modular, concurrent, evidence-first OSINT framework.** Every finding stays
traceable back to its source — evidence-first, not guess-first. `Go`

### 📊 webstats

**Open-source web analytics that respects the 5kb budget.** A sub-5kb vanilla JS
tracker, SPA-aware down to `hashchange`. Go (Fiber + PostgreSQL) backend, Next.js
dashboard, realtime over SSE. Privacy-first: salted IP hashing, retention
windows, visitor opt-out. `Go` · `PostgreSQL` · `Next.js`

### Other work

| Project | What it is | Stack |
|---|---|---|
| [penai](https://github.com/WildanDeveloper/penai) | AI-assisted penetration testing | `TypeScript` · `Go` |
| [WhatsApp-Number-Checker](https://github.com/WildanDeveloper/WhatsApp-Number-Checker) | Telegram bot validating numbers via WhatsApp | `JavaScript` · `Baileys` |
| [sxel](https://github.com/WildanDeveloper/sxel) | Web vulnerability scanner, 40+ modules, YAML rule DSL | `Go` |
| [CVE-2026-58231](https://github.com/WildanDeveloper/CVE-2026-58231) | Detection & precondition verification for the CVE | `Python` |
| [riak](https://github.com/WildanDeveloper/riak) | Experimental custom RIAK cryptography prototype | `Rust` |

---

## Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=rust,cpp,c,go,typescript,javascript,python,php,bash,sql&perline=10" />

<br>

**Backend & Systems**

<img src="https://skillicons.dev/icons?i=go,rust,nodejs,laravel,fastapi,nginx,docker,kubernetes,postman&perline=9" />

<br>

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,typescript,javascript&perline=5" />

<br>

**Data**

<img src="https://skillicons.dev/icons?i=postgres,mysql,mariadb,redis,sqlite&perline=5" />

<br>

**Security & Tooling**

<img src="https://skillicons.dev/icons?i=linux,kalilinux,burpsuite,metasploit,nmap,wireshark,git,githubactions&perline=8" />

</div>

---

## Stats

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=WildanDeveloper&theme=github_dark" alt="Profile details" />

<br><br>

<img height="175em" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=WildanDeveloper&theme=github_dark&count_private=true" alt="GitHub stats" />
<img height="175em" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=WildanDeveloper&theme=github_dark" alt="Top languages" />

<br><br>

<img src="https://streak-stats.demolab.com/?user=WildanDeveloper&theme=github_dark&hide_border=true" alt="Contribution streak" />

</div>

---

## Get in touch

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-WildanDeveloper-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/WildanDeveloper)
[![Email](https://img.shields.io/badge/Email-wildandeveloper%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:wildandeveloper@gmail.com)

</div>

---

<div align="center">
<sub>Built with too much coffee and a C++ compiler.</sub>
</div>