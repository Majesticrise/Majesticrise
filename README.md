# Majesticrise

Minecraft server tooling · Java / Rust / Python · Guangzhou

I build tools that make Minecraft server operation less opaque — scanners, proxies, plugins, and the occasional P2P rabbit hole.

---

## What I'm building

**[OpenCodeProxy](https://github.com/Majesticrise/OpenCodeProxy)** — A Rust reverse proxy that makes OpenCode Zen accessible through any OpenAI-compatible client.  
Handles identity compatibility, proxy-pool health management, streaming adaptation, and persistent metrics behind a single binary.

**[ServerFinder](https://github.com/Majesticrise/ServerFinder)** — Adaptive-concurrency Minecraft server discovery for authorized testing.  
SOCKS5 proxy fission, IP-based deduplication, and real-time concurrency tuning built for large-scale network hygiene work.

**[BookPrinter](https://github.com/Majesticrise/BookPrinter)** — Paper/Folia plugin that turns flat text into in-game books.  
Smart pagination, MiniMessage/RGB rendering, i18n, and a Vault soft-dependency for server economies.

**[MajesticChat](https://github.com/Majesticrise/MajesticChat)** — EasyTier-based mesh communication for small private groups.  
Encrypted chat over SQLite, Opus voice with adaptive jitter buffer, P2P file transfer, and LAN-over-P2P game tunneling.

---

## Currently digging into

- **Async Java** — non-blocking I/O patterns in Paper plugin architecture
- **Proxy/network tooling** — pool orchestration, protocol compatibility, failure cooldowns
- **Folia scheduling** — region-based multithreading for Minecraft server plugins

---

## Stack

`Java` `Rust` `Python` `C#`  
Paper / Folia · SQLite · TCP/UDP · SOCKS5 · HTTP proxies · async concurrency · CLI tooling

---

## Other repos

[CheckProxy](https://github.com/Majesticrise/CheckProxy) · [WifiRoam](https://github.com/Majesticrise/WifiRoam) · [Majesticrise.github.io](https://github.com/Majesticrise/Majesticrise.github.io)

---

## Notes on use

Scanner and proxy tools here are built for **authorized testing, research, and infrastructure you own or have permission to access**. Respect rate limits and service terms.

---

Bilibili ↗ [space.bilibili.com/3493114226411557](https://space.bilibili.com/3493114226411557)
