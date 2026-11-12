# Awesome-Collaborative-Debugging-Live-Sharing

## Top Collaborative Debugging & Live Sharing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Real-Time Code Sharing, Shared Debugging Sessions & Remote Pair Programming*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Collaborative Debugging & Live Sharing**. These tools enable developers to share their coding environment, terminal, and debugger with teammates in real time—eliminating the friction of screen sharing over video calls and enabling true hands-on collaboration across distributed teams.

**Examples** include Visual Studio Live Share, Tuple, Tandem, Code With Me (JetBrains), Replit, CodeSandbox, AWS Cloud9, and open-source alternatives like Tessera (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted collaborative coding, open-source shared terminals, and community-driven pair programming tools—ideal for developers, mentors, and teams seeking transparent, vendor-neutral collaboration without per-seat subscriptions.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Visual Studio Live Share](https://visualstudio.microsoft.com/services/live-share/)** | Microsoft's real-time collaborative coding and debugging tool. Host shares their entire project (code, terminal, localhost web app) without guests needing to install dependencies. Supports shared debugging sessions, voice calls, and read-only mode. **Now in maintenance mode** with no new features planned, but existing capabilities remain available [citation:2][citation:8]. | Free (included with Visual Studio/VS Code) | **Free forever**: full functionality available at no cost; requires Microsoft/GitHub account for sign-in [citation:2] |
| **[Tuple](https://tuple.app/)** | Purpose-built remote pair programming tool for macOS and Windows. Low-latency screen sharing optimized for coding, remote control, and crystal-clear text rendering. Only one user needs a paid license; guests join from browser for free [citation:3]. | $30/user/month (unlimited pairing sessions) [citation:3] | **14-day free trial**; free licenses available for qualifying open-source projects and startups [citation:9] |
| **[Tandem](https://tandem.chat/)** | Virtual office for remote teams with instant screen sharing, shared cursors, remote control, and drop-in audio/video rooms. Positioned as a persistent "office" rather than a meeting tool—teams wave at each other and start conversations without scheduling [citation:4]. | Quote-only (free tier available; paid plans via sales) | Free tier available with core features; paid plans add advanced collaboration controls |
| **[Code With Me (JetBrains)](https://www.jetbrains.com/code-with-me/)** | JetBrains' collaborative coding service for IntelliJ-based IDEs. Invite others into your IDE project for real-time editing and debugging. Guests don't need a JetBrains IDE installed—they can join via browser or lightweight client . | $10/user/month | Free tier available with limited session duration and features; paid plans unlock full collaboration |
| **[Replit](https://replit.com/)** | Browser-based IDE with real-time multiplayer editing (Google Docs-style). Invite teammates directly into your code environment with zero setup. Supports 50+ languages and instant live deployment . | Core: $20/month ($204/year annual); Pro: $100/month | **Starter (free)**: daily Agent allowance, limited cloud credits, basic collaboration; no time-limited trial for paid plans |
| **[CodeSandbox](https://codesandbox.io/)** | Cloud development platform with live collaboration, microVMs, and AI assistant (Boxy). Teams can code together in a shared browser environment with instant preview and deployment . | Pro: $12/month starting  | Free tier available with 400 monthly credits; paid plans add more compute and collaboration features |
| **[AWS Cloud9](https://aws.amazon.com/cloud9/)** | Browser-based IDE with built-in terminal, debugger, and real-time collaboration. Share your development environment with teammates for pair programming. Pay only for the underlying EC2 resources; the IDE itself is free . | Free IDE; pay for AWS resources (EC2, EBS) | **AWS Free Tier eligible**: new customers can use Cloud9 within Free Tier limits (e.g., t2.micro instance ~$2/month for 90 hours) |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Tessera](https://github.com/Kushaal-k/Tessera)** | [![Stars](https://img.shields.io/github/stars/Kushaal-k/Tessera?style=social&color=white)](https://github.com/Kushaal-k/Tessera/stargazers) | Open-source collaborative developer sandbox with Monaco editor, shared files, and interactive terminal. Real-time collaboration powered by Yjs and Socket.IO; code runs in Docker containers. Supports shared editing with live cursors, participant presence, and secure remote execution. Browser-based with no local setup [citation:11]. |
| **[Debugra](https://github.com/vijaypatil477/Debugra)** | [![Stars](https://img.shields.io/github/stars/vijaypatil477/Debugra?style=social&color=white)](https://github.com/vijaypatil477/Debugra/stargazers) | Open-source collaborative debugging platform with real-time code sharing via Firebase. Features AI-assisted debugging (Groq), multi-language code execution (Wandbox), room access controls, and a VS Code-style interface. Supports Python, JavaScript, Java, C++, Go, Rust, and more [citation:1]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Upterm](https://github.com/owenthereal/upterm)** | [![Stars](https://img.shields.io/github/stars/owenthereal/upterm?style=social&color=white)](https://github.com/owenthereal/upterm/stargazers) | Secure terminal sharing over SSH or WebSocket. Host a session and share the link; guests connect via standard SSH client. Self-hostable server (uptermd) with Docker/Traefik deployment options. Ideal for collaborative debugging in terminal-only environments [citation:6]. |
| **[Collagility](https://github.com/JhaSourav07/Collagility)** | [![Stars](https://img.shields.io/github/stars/JhaSourav07/Collagility?style=social&color=white)](https://github.com/JhaSourav07/Collagility/stargazers) | Open-source multiplayer terminal workspace for collaborative AI pair programming. Streams AI agent execution output token-by-token to all participants. Includes risk evaluation engine with manual/accept-edits/plan-only/auto security modes for AI command execution [citation:12]. |

**Frameworks for building custom systems**: Combine **Tessera** for browser-based collaborative coding with Docker execution, **Upterm** for secure terminal sharing, and **Collagility** for AI-assisted pair programming—creating a fully self-hosted collaborative debugging environment without per-seat SaaS subscriptions.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Collaborative debugging tools grant remote access to code and potentially production-like environments; enforce session authentication, read-only modes where appropriate, and audit guest access.
- Visual Studio Live Share is in maintenance mode—no new features are planned, though existing functionality remains [citation:2]. Open-source alternatives (Tessera, Upterm) are early-stage and may lack enterprise features like SSO, audit logging, and compliance certifications.

---

**Made for developers, engineering mentors, pair programmers, and teams building collaborative coding workflows.**  
Let's make collaborative debugging more open, accessible, and secure.
