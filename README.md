# Hi, I'm Pinta365 👋

I build **libraries**, **developer tools**, **Linux desktop utilities**, and **World of Warcraft addons** — in **TypeScript**, **Rust**, **Go**, and **Lua**.

Website: [pinta.land](https://pinta.land/) · 🦆 [Sponsor my work](https://github.com/sponsors/Pinta365)

## Spotlight

### [offgrid](https://github.com/Pinta365/offgrid)
A native library that adds local, offline AI to an application: chat, tool calling, structured JSON output, embeddings, and image and audio input. Link the library, ship a GGUF model next to your app, and that's it — no daemon, no Docker, no cloud, and no network access at runtime. Runs on any GPU through Vulkan with CPU fallback, and exposes a C ABI for use from C/C++, Python, Go, and C#.  
Available on [crates.io](https://crates.io/crates/offgrid) and [JSR](https://jsr.io/@pinta365/offgrid), with an OpenAI-compatible server included.

### [vsce-offgrid](https://github.com/Pinta365/vsce-offgrid)
A VS Code extension for local code completion and chat, powered by offgrid. No account, no API key, no cloud — the model runs on your own machine.

### [WebPulse](https://webpulseanalytics.com/)
Open-source, privacy-friendly web analytics — a self-hostable alternative to Google Analytics, built on Deno. Tracks page views, clicks, scrolls, and unique visitors, with country lookup and bot classification at ingest so dashboards show real people. Use it free at [webpulseanalytics.com](https://webpulseanalytics.com/) or self-host it.  
Code: [WebPulseBackend](https://github.com/Pinta365/WebPulseBackend) (tracking server) · [WebPulseAnalytics](https://github.com/Pinta365/WebPulseAnalytics) (dashboard) · [docs](https://developer.webpulseanalytics.com/)

### [oura_api](https://github.com/Pinta365/oura_api)
TypeScript client for v2 of the Oura Ring API.

### [blizzard_api](https://github.com/Pinta365/blizzard_api)
A TypeScript library for the Blizzard Battle.net APIs: World of Warcraft, WoW Classic, StarCraft II, Diablo III, and Hearthstone.

### [deno-discord](https://github.com/Pinta365/deno-discord)
A modern Discord library for Deno covering gateway bots, HTTP interactions, and REST — with sharding, per-route rate limiting, typed events, and a typed command framework for slash commands, context menus, and components.

### [tryck](https://github.com/Pinta365/tryck)
A single-binary static site generator for technical documentation, written in Go. Markdown plus `:::` directives, link and anchor checking, search, and a live-reload dev server — no Node or Python required.

## Linux desktop / Omarchy

Tools and widgets for Linux, built for [Omarchy](https://omarchy.org/) and Hyprland:

- [thermon](https://github.com/Pinta365/thermon) — low-overhead hardware and system monitor (daemon, CLI, and GUI) with sensor alerts and history
- [omarchy-thermon](https://github.com/Pinta365/omarchy-thermon) — Thermon in the Omarchy bar: temperatures, load, and top processes
- [omarchy-nothing-control](https://github.com/Pinta365/omarchy-nothing-control) — Nothing and CMF earbuds in the Omarchy bar: battery, noise control, and EQ, straight over Bluetooth
- [omarchy-ovpn](https://github.com/Pinta365/omarchy-ovpn) — unofficial OVPN bar widget and panel with WireGuard, multihop, and auto-connect
- [keychk](https://github.com/Pinta365/keychk) — keyboard diagnostic that finds switch chatter and dead keys, reading events straight from the kernel

## World of Warcraft addons

Available on [CurseForge](https://www.curseforge.com/members/pinta365/projects) and [Wago](https://addons.wago.io/):

- [Trailblazer](https://github.com/Pinta365/wow-trailblazer) — counts your footsteps and how far you travel by every other means (WoW Forever)
- [Group Finder](https://github.com/Pinta365/group-finder) — filtering and quick-apply improvements for the Group Finder UI
- [LFGForever](https://github.com/Pinta365/LFGForever) — puts group members, roles, and levels directly on the Looking For Group list
- [Ready Check](https://github.com/Pinta365/pinta-ready-check) — shows who is missing flask, food, rune, enchants, or gems during a ready check
- [BreakSync](https://github.com/Pinta365/breaksync) — break timer bar that works without DBM or BigWigs, and syncs with both
- [World Quests](https://github.com/Pinta365/pinta-world-quests) — world quest tracking with rewards, timers, and map overlays
- [Broker_TinyFriends](https://github.com/Pinta365/Broker_TinyFriends) / [Broker_TinyGuild](https://github.com/Pinta365/Broker_TinyGuild) — compact friends and guild lists for your data broker display
- [DispelFailedAlert](https://github.com/Pinta365/DispelFailedAlert) — plays a warning when your dispel removes nothing
- [ToggleNamesResurrected](https://github.com/Pinta365/ToggleNamesResurrected) — context-based guild and title visibility, updated for Midnight
- [Keystone Roulette](https://github.com/Pinta365/keystone-roulette) — randomly picks a keystone from your party for Mythic+

Addon tooling: [wow-version-bumper](https://github.com/Pinta365/wow-version-bumper) · [blp](https://github.com/Pinta365/blp) · [blp-toolkit](https://github.com/Pinta365/blp-toolkit) · [vsce-blp-viewer](https://github.com/Pinta365/vsce-blp-viewer)

## Libraries and tools

- [qr](https://github.com/Pinta365/qr) — dependency-free QR code encoder, renderer (SVG, PNG, canvas, terminal), and decoder for Deno, implementing ISO/IEC 18004
- [BucketFS](https://github.com/Pinta365/BucketFS) / [BucketRAID](https://github.com/Pinta365/BucketRAID) — one API across S3, R2, GCS, DO Spaces, and Dropbox, plus RAID-style XOR parity across buckets
- [openapi-typegen](https://github.com/Pinta365/openapi-typegen) — generate TypeScript types from OpenAPI 2 and 3.x specs
- [strava](https://github.com/Pinta365/strava) — cross-runtime TypeScript client for the Strava API v3
- [coros](https://github.com/Pinta365/coros) — unofficial TypeScript wrapper for the COROS Training Hub API
- [weather-mcp](https://github.com/Pinta365/weather-mcp) / [places-mcp](https://github.com/Pinta365/places-mcp) — MCP servers for worldwide weather and nearby places (campsites, motorhome stops, hotels, EV chargers)
- [arpeggio](https://github.com/Pinta365/arpeggio) — GPIO for Deno on Raspberry Pi using Linux GPIO chardev v2

## cross-org

I co-maintain cross-runtime libraries at [cross-org](https://github.com/cross-org), including [jwt](https://github.com/cross-org/jwt), [boxframe](https://github.com/cross-org/boxframe) (a WebAssembly-powered DataFrame library), [env](https://github.com/cross-org/env), [fs](https://github.com/cross-org/fs), and [image](https://github.com/cross-org/image).

## More projects

- [TunaTuner](https://github.com/Pinta365/TunaTuner) — browser instrument tuner starring Finley the tuna, who reacts live to your pitch
- [peekerino](https://github.com/Pinta365/peekerino) — Windows tray utility for peeking selected items in File Explorer
- [steganography](https://github.com/Pinta365/steganography) / [UnderByte](https://github.com/Pinta365/UnderByte) — steganography library and web tool for hiding messages and files in images
- [DNSLookup](https://github.com/Pinta365/DNSLookup) — look up DNS records over HTTPS, with shareable URLs and a JSON API
- [type-detective](https://github.com/Pinta365/type-detective) · [taskatron](https://github.com/Pinta365/taskatron)

## Tech

**Languages:** TypeScript, Rust, Go, Lua, QML, C#  
**Platforms / runtimes:** Deno, Node.js, Bun, browser, Linux desktop, VS Code, World of Warcraft  
**Interests:** local AI, APIs, dev tooling, storage systems, system monitoring, game addons

---

If my work is useful to you, consider [sponsoring me on GitHub](https://github.com/sponsors/Pinta365).
