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

| Product | Company Size / Valuation / Revenue | Starting Tier Pricing | Free Tier / Trial Limits | Description |
|---------|------------------------------------|-----------------------|--------------------------|-------------|
| **[AWS Cloud9](https://aws.amazon.com/cloud9/)** | Market Cap: ~$2.1T+ / Annual Revenue: $600B+ (Amazon / AWS segment ~$105B+ ARR) | Pay-as-you-go based on underlying EC2 compute (starting at ~$0.0104/hr for t4g.nano or ~$2.00/month for minimal usage; Cloud9 IDE service itself has no additional fee) | **Free forever via AWS Free Tier**: 750 hours/month of t2.micro or t3.micro EC2 compute + 30 GB EBS storage for first 12 months; IDE environment itself has no per-seat charge | Browser-based IDE with built-in terminal, debugger, and real-time collaboration. Share your development environment with teammates for pair programming. Pay only for the underlying EC2 resources; the IDE itself is free. |
| **[Visual Studio Live Share](https://visualstudio.microsoft.com/services/live-share/)** | Market Cap: ~$3.1T+ / Annual Revenue: $245B+ (Microsoft) | $0 (included free with Visual Studio and VS Code; Visual Studio Professional starts at $45/user/month for commercial IDE licensing) | **Free forever**: Full collaborative session and debugging features available at no cost for all VS Code and Visual Studio users (requires Microsoft or GitHub account login) | Microsoft's real-time collaborative coding and debugging tool. Host shares their entire project (code, terminal, localhost web app) without guests needing to install dependencies. Supports shared debugging sessions, voice calls, and read-only mode. In maintenance mode with existing capabilities retained. |
| **[JetBrains (Code With Me)](https://www.jetbrains.com/code-with-me/)** | Valuation: ~$5B–$9B (est.) / Annual Revenue: ~$650M+ (JetBrains) | $10/user/month (annual: $100/user/year; also included in JetBrains All Products Pack subscriptions) | **Free tier available**: Unlimited sessions capped at 30 minutes maximum per session and up to 3 guest collaborators per session; paid plans unlock unlimited session duration and up to 50 guests | JetBrains' collaborative coding and pair-programming service for IntelliJ-based IDEs. Invite others into your IDE project for real-time editing and debugging. Guests can join via browser or lightweight client without a local IDE installation. |
| **[Replit](https://replit.com/)** | Valuation: $9.0B (Series D, 2026) / Annual Revenue: ~$300M–$500M+ run-rate | Replit Core: $20/month ($204/year billed annually); Replit Pro: $100/month | **Free Starter plan forever**: Includes basic real-time multiplayer editing, daily AI Agent trial prompts, public Repls, and 10 compute units/month (no credit card required) | Browser-based IDE with real-time multiplayer editing (Google Docs-style). Invite teammates directly into your code environment with zero setup. Supports 50+ languages and instant live deployment. |
| **[CodeSandbox](https://codesandbox.io/)** | Valuation: ~$50M–$100M (Acquired by Together AI) / Annual Revenue: ~$1.5M–$1.9M ARR | Pro Plan: $12/user/month ($144/user/year billed annually) | **Free Build plan forever**: Up to 5 team members per workspace, unlimited public sandboxes, up to 10 concurrent microVMs, and standard baseline microVM compute (1 vCPU, 1 GB RAM) | Cloud development platform with live collaboration, microVMs, and AI assistant (Boxy). Teams can code together in a shared browser environment with instant preview and deployment. |
| **[Tuple](https://tuple.app/)** | Valuation: ~$20M–$40M (est. bootstrapped) / Annual Revenue: ~$4M–$8M ARR | $30/user/month ($300/user/year billed annually) | **14-day free trial**: Full access to all pairing features, multi-cursor support, low-latency screen control, and unlimited session duration (free sponsored licenses available for qualifying OSS maintainers) | Purpose-built remote pair programming tool for macOS and Windows. Low-latency screen sharing optimized for coding, remote control, and crystal-clear text rendering. Only host requires a paid seat; guests can join for free. |
| **[Tandem](https://tandem.chat/)** | Valuation: ~$20M–$35M (est.) / Annual Revenue: ~$1.9M ARR ($8.8M VC raised) | Small Teams Plan: $49/month (or $499/year billed annually for teams up to 10 members) | **Free tier forever**: Up to 4 team members with unlimited drop-in audio huddles, screen sharing with live multi-cursors, and shared application controls | Virtual office for remote teams with instant screen sharing, shared cursors, remote control, and drop-in audio/video rooms. Positioned as a persistent virtual workspace for spontaneous pair programming and debugging. |

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
