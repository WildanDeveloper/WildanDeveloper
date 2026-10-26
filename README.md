<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:FFD700&height=180&section=header&text=Wildan&fontColor=FFD700&fontSize=64&fontAlignY=38&desc=Systems%20%C2%B7%20Infrastructure%20%C2%B7%20Security&descAlignY=60&descSize=18" alt="Header" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=1000&color=FFD700&center=true&vCenter=true&width=760&lines=Systems+Programmer+%7C+Rust+%26+C%2B%2B;Infrastructure+Engineer+%7C+Docker+%26+K8s;Security+Researcher+%7C+Offensive+Tooling;Game+Server+Engineer+%7C+ENet+%26+MariaDB" alt="Typing SVG" />

<br>

[![Views](https://komarev.com/ghpvc/?username=WildanDeveloper&label=Views&color=FFD700&style=flat-square)](https://github.com/WildanDeveloper)
[![Followers](https://img.shields.io/github/followers/WildanDeveloper?color=FFD700&style=flat-square&label=Followers)](https://github.com/WildanDeveloper?tab=followers)
[![Repos](https://img.shields.io/github/repos/WildanDeveloper?color=FFD700&style=flat-square&label=Repos)](https://github.com/WildanDeveloper?tab=repositories)
[![Since](https://img.shields.io/badge/since-Jun%202025-FFD700?style=flat-square)](https://github.com/WildanDeveloper)

</div>

<br>

## 👋 About

I build software that has to survive contact with production: **compilers and runtimes, network daemons, game servers, and the offensive tooling that breaks them.**

The common thread is systems work. I care about what really happens at the byte level, how a workload behaves under load, and where the trust boundary actually sits.

| | Focus | What that means |
|---|---|---|
| 🦀 | **Systems programming** | Languages, runtimes, and daemons in Rust and C++ |
| 🏗️ | **Infrastructure** | Self-hosted hosting stacks, node agents, container orchestration |
| 🔐 | **Security research** | Scanners, OSINT tooling, AI-assisted penetration testing |
| 🎮 | **Game servers** | Growtopia private servers, protocol-compatible implementations |

> Most of my projects start as *"does this need to exist?"* and end as a single binary with no runtime dependencies.

<br>

## 🚀 Featured work

| Project | What it is | Stack |
|---|---|---|
| 🦀 [**wlel**](https://github.com/WildanDeveloper/wlel) | An arena-first systems language that compiles to native code. Zero leaks by construction: every allocation in an `arena` block is an O(1) pointer bump, reclaimed when the block exits. | `Rust` |
| 🦅 [**roost**](https://github.com/WildanDeveloper/roost) | Drop-in Pterodactyl Wings daemon rewritten in Rust. Any Pterodactyl-compatible panel manages containers on the node with no panel changes. **38/38** Wings API conformance tests passing. | `Rust` `tokio` |
| 🧠 [**WEngine**](https://github.com/WildanDeveloper/WEngine) | Blazing-fast, CPU-first AI inference engine. Rust core with C++ / AVX-512 acceleration. | `Rust` `C++` |
| 🎮 [**GTPS**](https://github.com/WildanDeveloper/GTPS) | Growtopia private server in one C++ binary: ENet game server, HTTPS login, and web account management in a single process. Supports protocol 226 (web-token) with pending-auth resume bound to client IP. | `C++` `ENet` `MariaDB` |
| 🔭 [**argus**](https://github.com/WildanDeveloper/argus) | Modular, concurrent, evidence-first OSINT framework. Every finding stays traceable to its source. | `Go` |
| 📊 [**webstats**](https://github.com/WildanDeveloper/webstats) | Open-source web analytics within a 5kb budget. SPA-aware tracker (down to `hashchange`), realtime dashboard over SSE, privacy-first with salted IP hashing, retention windows, and visitor opt-out. | `Go` `PostgreSQL` `Next.js` |

<details>
<summary><b>Code peek: arena allocation in wlel</b></summary>

<br>

```wl
arena(1 << 20) {
    // no free() needed, ever
}
```

</details>

<details>
<summary><b>More projects</b></summary>

<br>

| Project | What it is | Stack |
|---|---|---|
| [penai](https://github.com/WildanDeveloper/penai) | AI-assisted penetration testing | `TypeScript` `Go` |
| [sxel](https://github.com/WildanDeveloper/sxel) | Web vulnerability scanner, 40+ modules, YAML rule DSL | `Go` |
| [CVE-2026-58231](https://github.com/WildanDeveloper/CVE-2026-58231) | Detection and precondition verification for the CVE | `Python` |
| [WhatsApp-Number-Checker](https://github.com/WildanDeveloper/WhatsApp-Number-Checker) | Telegram bot that validates numbers via WhatsApp | `JavaScript` `Baileys` |
| [riak](https://github.com/WildanDeveloper/riak) | Experimental custom RIAK cryptography prototype | `Rust` |

</details>

<br>

## 🛠️ Stack

<div align="center">

<table>
<tr>
<td align="right"><b>Languages</b></td>
<td><img src="https://skillicons.dev/icons?i=rust,cpp,c,go,typescript,javascript,python,php,bash,sql&perline=10" alt="Languages" /></td>
</tr>
<tr>
<td align="right"><b>Backend & Infra</b></td>
<td><img src="https://skillicons.dev/icons?i=nodejs,laravel,fastapi,nginx,docker,kubernetes,postman&perline=7" alt="Backend and infra" /></td>
</tr>
<tr>
<td align="right"><b>Frontend</b></td>
<td><img src="https://skillicons.dev/icons?i=react,nextjs,tailwind&perline=3" alt="Frontend" /></td>
</tr>
<tr>
<td align="right"><b>Data</b></td>
<td><img src="https://skillicons.dev/icons?i=postgres,mysql,mariadb,redis,sqlite&perline=5" alt="Data" /></td>
</tr>
<tr>
<td align="right"><b>Security & Tooling</b></td>
<td><img src="https://skillicons.dev/icons?i=linux,kalilinux,burpsuite,metasploit,nmap,wireshark,git,githubactions&perline=8" alt="Security and tooling" /></td>
</tr>
</table>

</div>

<br>

## 📈 Stats

<details>
<summary><b>Show GitHub stats</b></summary>

<br>

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=WildanDeveloper&theme=github_dark" alt="Profile details" />

<br><br>

<img height="175em" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=WildanDeveloper&theme=github_dark&count_private=true" alt="GitHub stats" />
<img height="175em" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=WildanDeveloper&theme=github_dark" alt="Top languages" />

<br><br>

<img src="https://streak-stats.demolab.com/?user=WildanDeveloper&theme=github_dark&hide_border=true" alt="Contribution streak" />

</div>

</details>

<br>

## 📬 Get in touch

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-WildanDeveloper-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/WildanDeveloper)
[![Email](https://img.shields.io/badge/Email-wildandeveloper%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:wildandeveloper@gmail.com)

<br>

<sub>Built with too much coffee and a C++ compiler.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:FFD700&height=100&section=footer" alt="Footer" width="100%" />

</div>
