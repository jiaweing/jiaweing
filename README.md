<!-- Intro  -->
<div align="center">
<pre>
    ___  ___  ________          ___       __   _______   ___          ________   ________     
   |\  \|\  \|\   __  \        |\  \     |\  \|\  ___ \ |\  \        |\   ___  \|\   ____\    
   \ \  \ \  \ \  \|\  \       \ \  \    \ \  \ \   __/|\ \  \       \ \  \\ \  \ \  \___|    
 __ \ \  \ \  \ \   __  \       \ \  \  __\ \  \ \  \_|/_\ \  \       \ \  \\ \  \ \  \  ___  
|\  \\_\  \ \  \ \  \ \  \       \ \  \|\__\_\  \ \  \_|\ \ \  \       \ \  \\ \  \ \  \|\  \ 
\ \________\ \__\ \__\ \__\       \ \____________\ \_______\ \__\       \ \__\\ \__\ \_______\
 \|________|\|__|\|__|\|__|        \|____________|\|_______|\|__|        \|__| \|__|\|_______|
</pre>
</div>

<div align="center">

<p>
  <a href="https://jiaweing.com"><img src="https://shieldcn.dev/badge/website-jiaweing.com-black.png?logo=googlechrome" alt="Website" /></a>
  <a href="mailto:hey@jiaweing.com"><img src="https://shieldcn.dev/badge/email-hey@jiaweing.com-blue.png?logo=gmail" alt="Email" /></a>
  <a href="https://github.com/jiaweing"><img src="https://shieldcn.dev/github/followers/jiaweing.png?logo=github" alt="GitHub Followers" /></a>
  <img src="https://shieldcn.dev/badge/made%20in-Singapore-red.png" alt="Made in Singapore" />
</p>

</div>

<details>
<summary>Source Code</summary>

```python
from typing import List, Dict, Tuple


class jiaweing:
    """
    software engineer · designer · founder
    creating unique and original digital experiences
    """

    def __init__(self):
        self.name      = "Jia Wei Ng"
        self.alias     = "Jay"
        self.age       = 26
        self.location  = "Singapore"
        self.website   = "https://jiaweing.com"
        self.education = "BSc Computing Science · SIT + University of Glasgow"
        self.stack     = ["TypeScript", "Rust", "Python", ".NET", "Next.js", "Tauri", "React Native", "Postgres", "SQLite"]

    @property
    def bio(self) -> str:
        return (
            "just an ordinary guy building software.\n"
            "a designer and software engineer crafting unique, and original digital experiences.\n"
            "drawn to psychology, space, quantum mechanics, and the strange phenomena that shape the universe."
        )

    @property
    def achievements(self) -> List[str]:
        return [
            "Google APAC Solution Challenge 2025 — Top 10",
            "Dell InnovateFest 2025 — Finalist",
            "Dell Cloud Native Awards — 1st Place (x2)",
            "built titan.tf at 15 — 460k+ players, 20k+ Steam members",
            "founded 18 startups, shipped 17 apps",
            "top 25% Unsplash contributor — 460k+ views, 4.3k+ downloads",
            "87+ blog posts published",
        ]

    @property
    def setup(self) -> Dict[str, object]:
        return {
            "workstation": {
                "processor": "i7-14700KF",
                "gpu"      : "RTX 4070 Ti SUPER",
                "ram"      : "32GB DDR5",
            },
            "laptop"     : "MacBook Air M2 Midnight",
            "peripherals": [
                "Yunzii AL75 Keyboard",
                "AULA F75 Pro",
                "Shure SM7B + Focusrite Scarlett 2i2",
                "Fujifilm X-T50 + Sigma 18-50mm f2.8",
            ],
        }

    @property
    def contact(self) -> Tuple[str, str, str, str, str]:
        github   = "github.com/jiaweing"
        linkedin = "linkedin.com/in/jiaweing"
        twitter  = "x.com/jiaweihq"
        youtube  = "youtube.com/@jiaweihq"
        email    = "hey@jiaweing.com"

        return github, linkedin, twitter, youtube, email


jay = jiaweing()
```

</details>

## Current Projects

### AI & Memory

* 🌐 **[layer0](https://github.com/amajorai/layer0)** - self-hosted AI memory and RAG layer with local LLM support, vector embeddings, knowledge graph, and hybrid search

### Desktop

* 🎭 **[backstage](https://github.com/amajorai/backstage)** - open-source YouTube thumbnail studio with AI background removal and Gemini image generation
* ⛩️ **[torii](https://github.com/amajorai/torii)** - production-ready Tauri v2 + React 19 desktop app shell with licensing, analytics, auto-updates, and secure storage baked in

### Claude Code Skills

* 📦 **[ship.md](https://github.com/amajorai/ship.md)** - end-to-end skill for shipping features without gaps, running up to 10 quality-gated phases
* 🪅 **[vibe.md](https://github.com/amajorai/vibe.md)** - end-to-end skill for spinning up a production-ready full-stack dev and deploy environment
* ⚡ **[skills](https://github.com/amajorai/skills)** - simple, minimal skills for the things developers overlook when shipping apps

### Web & UI

* 📥 **[dropdrawer](https://github.com/jiaweing/DropDrawer)** (201 stars) - responsive shadcn/ui dropdown-to-drawer component
* 📂 **[portfolio-dex](https://github.com/jiaweing/portfolio-dex)** (5 stars) - personal portfolio site
* 🪟 **[ui](https://github.com/jiaweing/ui)** - beautifully designed components inspired by iOS 26 and macOS 26, built on shadcn/ui

### Browser Extensions & Tools

* 🔲 **[altq-qr-reader-extension](https://github.com/jiaweing/altq-qr-reader-extension)** (7 stars) - offline browser extension for reading QR codes directly from web pages
* 🖼️ **[Unsplash-Multiple-Download](https://github.com/jiaweing/Unsplash-Multiple-Download)** (12 stars) - instantly download all images on a page on Unsplash
* 🗑️ **[YouTube-Playlist-Delete-Video](https://github.com/jiaweing/YouTube-Playlist-Delete-Video)** - Stylus style that restores double-click to remove videos from YouTube playlists
* 🔍 **[center-google-search](https://github.com/jiaweing/center-google-search)** - Stylus style for centered Google search results

## Legacy Work

### AI & Agents

* 🌎 **[lemon8-travel-research-agent](https://github.com/jiaweing/lemon8-travel-research-agent)** (7 stars) - multi-agent system that scrapes Lemon8 and generates comprehensive travel guides
* 🤖 **[GeminiTelegramBot](https://github.com/jiaweing/GeminiTelegramBot)** (5 stars) - Telegram bot powered by Gemini 2.0 Flash for natural conversations and AI image generation
* 🛩️ **[copilot-chat-api](https://github.com/jiaweing/copilot-chat-api)** (6 stars) - OpenAI-compatible HTTP API interface for GitHub Copilot with native GitHub authentication
* 🌙 **[updatenight-agent](https://github.com/jiaweing/updatenight-agent)** - automated Update Night newsletter generation using crewAI agents
* 🏨 **[agoda-agent](https://github.com/jiaweing/agoda-agent)** - multi-agent system that analyzes Agoda hotel listings and generates accommodation guides
* 🔍 **[localRAG-api](https://github.com/jiaweing/localRAG-api)** (3 stars) - local RAG API, superseded by layer0
* 🤖 **[localLLM-api](https://github.com/jiaweing/localLLM-api)** - local LLM API, superseded by layer0
### APIs & Boilerplates

* 🔐 **[dotnet8-jwt-api-boilerplate](https://github.com/jiaweing/dotnet8-jwt-api-boilerplate)** - barebones .NET 8 API with JWT auth and MySQL, zero abstractions, full control
* ✅ **[verify.supply.tf](https://github.com/jiaweing/verify.supply.tf)** - blockchain-based verification system for product authenticity and ownership tracking

### Web & Projects

* 🏢 **[base7-landing](https://github.com/jiaweing/base7-landing)** - landing page for Base7
* ✏️ **[telequill](https://github.com/jiaweing/telequill)** - transform public Telegram channels into elegant blog-style websites

## Connect

<p>
  <a href="https://x.com/jiaweihq"><img src="https://shieldcn.dev/badge/X-jiaweihq-black.png?logo=x" alt="X" /></a>
  <a href="https://linkedin.com/in/jiaweing"><img src="https://shieldcn.dev/badge/LinkedIn-jiaweing-0A66C2.png?logo=linkedin" alt="LinkedIn" /></a>
  <a href="https://instagram.com/jiaweihq"><img src="https://shieldcn.dev/badge/Instagram-jiaweihq-E4405F.png?logo=instagram" alt="Instagram" /></a>
  <a href="https://threads.net/@jiaweihq"><img src="https://shieldcn.dev/badge/Threads-jiaweihq-black.png?logo=threads" alt="Threads" /></a>
  <a href="https://tiktok.com/@jiaweihq"><img src="https://shieldcn.dev/badge/TikTok-jiaweihq-black.png?logo=tiktok" alt="TikTok" /></a>
  <a href="https://youtube.com/@jiaweihq"><img src="https://shieldcn.dev/badge/YouTube-jiaweihq-FF0000.png?logo=youtube" alt="YouTube" /></a>
  <a href="https://twitch.tv/jiaweihq"><img src="https://shieldcn.dev/badge/Twitch-jiaweihq-9146FF.png?logo=twitch" alt="Twitch" /></a>
  <a href="https://kick.com/jiaweing"><img src="https://shieldcn.dev/badge/Kick-jiaweing-53FC18.png?logo=kick" alt="Kick" /></a>
</p>

## 🌙 Update Night

An AI-native media platform and catalog for builders. Newsletter, Telegram, Discord, podcast, and a curated catalog of AI and dev tools — covering what's shipping in the AI and developer ecosystem before it hits the headlines.

<p>
  <a href="https://updatenight.com"><img src="https://shieldcn.dev/badge/Update%20Night-subscribe-orange.png?variant=secondary&logo=substack" alt="Update Night" /></a>
  <a href="https://open.spotify.com/show/4ynkzghYMkJDlw9lMxEdfy"><img src="https://shieldcn.dev/badge/Podcast-listen-1DB954.png?logo=spotify" alt="Podcast" /></a>
</p>
