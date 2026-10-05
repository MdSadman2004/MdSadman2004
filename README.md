# Md. Sadman Bin Masud

EECE student at **MIST, Dhaka**. I build AI-agent tools, Android applications, embedded-system projects and interactive worlds.

![Sadman's public project directory](docs/portfolio/overview.png)

*Repository navigation, not a benchmark or a claim that every project is production-ready.*

**[Portfolio](https://mdsadman2004.github.io/)** · **[Selected work](#selected-work)** · **[Games](#games)** · **[Project directory](#project-directory)**

## Selected work

### [Atlas](https://github.com/MdSadman2004/Atlas)
An Android agent with phone tools, memory, skills and scheduled goals. The orchestration lives on Android; inference uses an external API.

**Kotlin · Jetpack Compose · AccessibilityService · WorkManager**

[Source and architecture](https://github.com/MdSadman2004/Atlas) · [Releases](https://github.com/MdSadman2004/Atlas/releases)

![Atlas with an enabled Battery watchdog goal](docs/portfolio/atlas-goals.png)

*Existing app capture: a configured scheduled goal, with zero recorded runs in this frame. Not a fresh autonomy test.*

### [Hermes Mobile](https://github.com/MdSadman2004/hermes-mobile)
An Android companion for desktop Hermes sessions, files, operations and terminal access. The desktop retains execution; the phone connects through REST and WebSocket.

**Kotlin · Compose · Python · WebSocket**

### [Hybrid Solar–Grid](https://github.com/MdSadman2004/hybrid-solar-grid)
A local dashboard, telemetry simulator, command service and electronics-design references for a solar-grid project.

**React · TypeScript · Node.js · Arduino / ESP32 references**

![Hybrid Solar–Grid source guide](docs/portfolio/hybrid-solar-grid-guide.png)

*Software and design-reference navigation. Generated telemetry is simulation, not a measured physical microgrid.*

### [Socratic Engine](https://github.com/MdSadman2004/socratic-engine)
A Next.js thinking workspace with LangGraph routing, streamed replies and a concept dictionary. Requires configured external API access.

**Next.js · TypeScript · LangGraph · Cerebras**

## Games

### [Sadman's Parable](https://github.com/MdSadman2004/sadmans-parable)
A first-person psychological fable: a building has approved your life before you have lived it. Explore branching routes, an unreliable narrator and moments of wonder.

**[Play in browser](https://mdsadman2004.github.io/sadmans-parable/)** · **[Download](https://github.com/MdSadman2004/sadmans-parable/releases/latest)** · **[Source](https://github.com/MdSadman2004/sadmans-parable)**

![A garden scene from Sadman's Parable](docs/portfolio/parable-garden.jpg)

*Existing WebGL gameplay capture. A self-contained desktop-browser game; no fresh gameplay verification is implied by this profile update.*

*Unaffiliated homage: not affiliated with, endorsed by or sponsored by the creators or publishers of The Stanley Parable.*

### [Grid Protocol](https://github.com/MdSadman2004/tron-ares)
A film-inspired Three.js grid-combat prototype with transforming vehicles and an Android WebView wrapper. The repository slug remains `tron-ares`; this is not an official Tron product.

**JavaScript · Three.js · Vite · Android WebView**

![Grid Protocol implementation entry points](docs/portfolio/tron-ares-guide.png)

*Source guide, not a gameplay screenshot or a certified release.*

## Project directory

Every public repository is included below. Each project README identifies its setup path, source entry points and limitations.

### Agents & tooling

| Repository | What is actually published |
| :-- | :-- |
| [Atlas](https://github.com/MdSadman2004/Atlas) | An Android agent with local tools, persistent memory, scheduled goals and API-backed inference. |
| [Hermes Mobile](https://github.com/MdSadman2004/hermes-mobile) | An Android control companion for desktop Hermes sessions, files, operations and terminal access. |
| [Socratic Engine](https://github.com/MdSadman2004/socratic-engine) | A Next.js thinking workspace with LangGraph routing, streamed replies and a concept dictionary. |
| [Hermes CLI Orchestrator](https://github.com/MdSadman2004/hermes-orchestrator) | Python integration scripts for dispatching external agent CLIs, checking artifact postconditions, sharing file-based memory, exporting MCP settings, and inspecting cron state. |
| [AgentForge Artifact Utilities](https://github.com/MdSadman2004/AgentForge) | Standard-library Python utilities for file hashing, artifact metadata, lightweight contract validation, and persistent change checks, with historical automation demo notes. |
| [Hermes Remote Evidence Archive](https://github.com/MdSadman2004/hermes-remote) | Archive of selected Hermes mobile and PC integration source text in source-evidence.json, with historical UI captures and protocol findings. Not a standalone backend or Android build. |
| [Hermes Projects](https://github.com/MdSadman2004/hermes-projects) | A historical umbrella snapshot containing an Android Hermes companion project. |

### Hardware

| Repository | What is actually published |
| :-- | :-- |
| [Hybrid Solar–Grid](https://github.com/MdSadman2004/hybrid-solar-grid) | A local microgrid dashboard, telemetry simulator, command service and electronics references. |
| [ZeroADC and CDM Research Artifacts](https://github.com/MdSadman2004/ZeroADC) | Research kernels and recorded artifacts for Zero-ADC event gating and Collatz deterministic recovery, including modeled energy comparisons, fixed-window AVR/Renode firmware, logs, and a validation dossier. |
| [Project Farcry ESP32 Car Prototype](https://github.com/MdSadman2004/ProjectFarcry) | ESP32 car-control sketch and Python/OpenCV face-following prototype using an Android IP Webcam stream, with separate Flask media/location receiver experiments. Bench prototype, not a validated rescue system. |
| [Hardware Visualizations](https://github.com/MdSadman2004/hardware-visualizations) | Browser-readable circuit drawings and an early load-shedding alert design proposal. |
| [Ultrasonic Distance Estimator](https://github.com/MdSadman2004/EECE-106) | A React coursework presentation for an Arduino ultrasonic-distance project. |

### Research & analysis

| Repository | What is actually published |
| :-- | :-- |
| [ILCI TinyML Initialization Research](https://github.com/MdSadman2004/ILCI) | Exploratory ATmega328P study of Collatz-derived neural-network initialization, with Arduino benchmark source, recorded CSV, plotting scripts, and a manuscript. Results need methodological review, not assumed reproduction. |
| [TerraTrace Deed Chain Demo](https://github.com/MdSadman2004/TerraTrace) | LangGraph and Pydantic deed-history demo with labeled text parsing, adjacent-owner checks, keyword covenant flags, and cosine ranking over three mock precedent records. Not legal advice. |
| [LexisClear Contract Review Demo](https://github.com/MdSadman2004/LexisClear) | LangGraph contract-review demo that parses sample text sections, applies hardcoded playbook phrase rules, and exports an HTML report with predefined replacement clauses. Not legal advice. |
| [Vanguard Emissions Report Demo](https://github.com/MdSadman2004/Vanguard) | LangGraph demo for reading a sample activity ledger, applying keyword scope labels and hardcoded emission factors, and exporting an HTML report. Not validated ESG compliance or carbon accounting. |
| [BP Local Monitor](https://github.com/MdSadman2004/bp-local-monitor) | Local Python blood-pressure logger with validated CSV readings, explicit classification rules, summary statistics, HTML dashboard generation, and agent JSON context. Not a medical device. |

### Creative web

| Repository | What is actually published |
| :-- | :-- |
| [Generative 3D Portfolio](https://github.com/MdSadman2004/portfolio-3d) | A React portfolio with a Three.js field, seeded canvas artwork and a Collatz explorer. |
| [Graphein](https://github.com/MdSadman2004/graphein) | A React studio landing page with motion, an ROI calculator and section-based navigation. |
| [Glade](https://github.com/MdSadman2004/Glade) | A multi-page studio website with Express routing and illustrative agent simulators. |
| [CNN Filter Atlas](https://github.com/MdSadman2004/frontend-designs) | A self-contained HTML visual guide to convolution filters and their mechanisms. |
| [Website Studies](https://github.com/MdSadman2004/WebsitesCollection) | Standalone HTML experiments spanning portfolios, landing pages and a small canvas game. |
| [AI Prompt Collection](https://github.com/MdSadman2004/ai-prompt-collection) | A small, browsable archive of image, cinematography and Arduino project prompts. |
| [Projects — Frontend Scaffold](https://github.com/MdSadman2004/Projects) | A partial Vite / React coursework scaffold whose referenced application source is missing. |

### Games

| Repository | What is actually published |
| :-- | :-- |
| [Sadman's Parable](https://github.com/MdSadman2004/sadmans-parable) | An offline first-person psychological fable with an unreliable narrator and branching endings. |
| [Grid Protocol](https://github.com/MdSadman2004/tron-ares) | A Three.js grid-combat prototype with transforming vehicles and an Android WebView wrapper. |

### Profile & directory

| Repository | What is actually published |
| :-- | :-- |
| [Md. Sadman Bin Masud](https://github.com/MdSadman2004/MdSadman2004) | AI-agent tools, Android applications, embedded-system projects and interactive worlds. |
| [Portfolio Hub](https://github.com/MdSadman2004/MdSadman2004.github.io) | A visual directory of public projects, organized into agents, hardware, research, web and games. |

## How I approach engineering

- **Rigor over hype.** Source, results and limitations should agree.
- **Keep the boundary visible.** A simulator is not a hardware test; a prototype is not a production service.
- **Make the work inspectable.** Document the real entry points, not an imagined architecture.

## Contact

For project discussions, open an issue in the relevant repository. This public page deliberately avoids publishing private contact details or device-pairing credentials.

## Scope & limitations

This profile is a directory, not independent certification of every project. Source-guide images are explanatory drawings. App and game captures are pre-existing project evidence; experimental outcomes should be read with their original conditions and baselines. Each repository documents its own license or absence of a repository-wide license grant.
