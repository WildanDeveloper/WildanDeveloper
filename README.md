<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=FFD700&center=true&vCenter=true&width=720&lines=Systems+Programmer;Security+Researcher;Game+Server+Engineer;Building+Tools+That+Actually+Run" alt="Typing SVG" />

[![Profile views](https://komarev.com/ghpvc/?username=WildanDeveloper&label=Views&color=FFD700&style=for-the-badge)](https://github.com/WildanDeveloper)
[![Followers](https://img.shields.io/github/followers/WildanDeveloper?color=FFD700&style=for-the-badge&label=Followers)](https://github.com/WildanDeveloper?tab=followers)
[![Since](https://img.shields.io/badge/since-Jun%202025-FFD700?style=for-the-badge)](https://github.com/WildanDeveloper)

</div>

---

## What I build

I write software that has to survive contact with production: compilers and
runtimes, network daemons, game servers, and the offensive tooling that breaks
them.

The common thread is **systems work** — I care about what actually happens at
the byte level, how a workload behaves under load, and where the trust boundary
really sits.

- **Systems programming** — languages, runtimes, and daemons in Rust and C++
- **Infrastructure** — self-hosted hosting stacks, container orchestration, node agents
- **Security research** — scanners, OSINT tooling, AI-assisted penetration testing
- **Game servers** — Growtopia private servers, protocol-compatible implementations

---

## Featured work

<table>
<tr>
<td width="50%" valign="top">

### 🦀 wlel

**An arena-first systems programming language.**

Compiles to native code. Zero leaks by construction — every allocation inside
an `arena` block is an O(1) pointer bump reclaimed at block exit.

```wl
arena(1 << 20) {
    // no free() needed, ever
}
```

`Rust` · has CI, fuzz targets, and a test suite

[Repository →](https://github.com/WildanDeveloper/wlel)

</td>
<td width="50%" valign="top">

### 🦅 roost

**A drop-in replacement for the Pterodactyl Wings daemon, rewritten in Rust.**

Any Pterodactyl-compatible panel manages containers on this node exactly as it
would with the official daemon — no panel modifications required.

`Rust` + tokio · MIT · 38/38 Wings API conformance tests passing

[Repository →](https://github.com/WildanDeveloper/roost)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 WEngine

**A blazing-fast CPU-first AI inference engine.**

`Rust` core with `C++` / AVX-512 acceleration.

[Repository →](https://github.com/WildanDeveloper/WEngine)

</td>
<td width="50%" valign="top">

### 🎮 GTPS

**A Growtopia private server in a single C++ binary.**

ENet game server, HTTPS login service, and web account management in one
process, backed by MariaDB. Login flow for modern clients (protocol 226,
web-token based) with pending-auth resume bound to client IP.

`C++` · `ENet` · `MariaDB`

[Repository →](https://github.com/WildanDeveloper/GTPS)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔭 argus

**A modular, concurrent, evidence-first OSINT framework.**

Every finding is traceable back to its source — evidence-first, not
guess-first.

`Go`

[Repository →](https://github.com/WildanDeveloper/argus)

</td>
<td width="50%" valign="top">

### 🤖 penai

**AI-assisted penetration testing.**

A TypeScript core paired with a Go Bubble Text interface for interactive runs.

`TypeScript` · `Go`

[Repository →](https://github.com/WildanDeveloper/penai)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 webstats

**Open-source web analytics that respects the 5kb budget.**

A sub-5kb vanilla JS tracker, SPA-aware down to `hashchange`. Go (Fiber +
PostgreSQL) backend, Next.js dashboard, realtime over SSE. Privacy-first:
salted IP hashing, retention windows, visitor opt-out.

`Go` · `PostgreSQL` · `Next.js`

[Repository →](https://github.com/WildanDeveloper/webstats)

</td>
<td width="50%" valign="top">

### 📱 WhatsApp-Number-Checker

**A Telegram bot that validates numbers against WhatsApp.**

Baileys-based, with pairing codes instead of QR scanning, bulk `.txt` upload,
and per-user isolated sessions.

`JavaScript` · `Baileys` · `PM2`

[Repository →](https://github.com/WildanDeveloper/WhatsApp-Number-Checker)

</td>
</tr>
</table>

---

## Tooling

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=rust,cpp,c,go,typescript,javascript,python,php,bash,sql&perline=10" />

<br>

**Backend & Systems**

<img src="https://skillicons.dev/icons?i=go,rust,nodejs,laravel,fastapi,express,nginx,docker,kubernetes&perline=9" />

<br>

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,typescript,javascript,astro&perline=6" />

<br>

**Data**

<img src="https://skillicons.dev/icons?i=postgres,mysql,mariadb,redis,sqlite,clickhouse&perline=6" />

<br>

**Security & Tooling**

<img src="https://skillicons.dev/icons?i=linux,kalilinux,burpsuite,metasploit,nmap,wireshark,git,githubactions&perline=8" />

</div>

---

## Security work

- **CVE-2026-58231** — detection and precondition-verification tooling
  ([repo](https://github.com/WildanDeveloper/CVE-2026-58231))
- **sxel** — high-performance web vulnerability scanner, 40+ attack modules with
  a YAML rule DSL (contributed to an existing fork)
- **riak** — experimental custom RIAK cryptography research prototype

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