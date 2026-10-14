<div align="center">

<img src="assets/header.svg" width="100%" alt="Quargelk — Turning ideas into working software. Linux, networking and embedded systems.">

<p>
I write software for Linux-based routers and the networks behind them.<br>
My main project is <a href="https://github.com/quargelk/easy-vless"><b>Easy VLESS</b></a>, a VLESS and Trojan client for OpenWrt.<br>
Interested in Linux, networking and embedded systems.
</p>

</div>

## Featured project

<a href="https://github.com/quargelk/easy-vless">
  <img src="assets/easy-vless.svg" width="100%" alt="Easy VLESS diagram: devices on the LAN and the router itself are intercepted by nftables with TPROXY, passed to sing-box, and routing rules send each connection either directly or through a VLESS or Trojan server.">
</a>

### [Easy VLESS](https://github.com/quargelk/easy-vless)

[![Latest release](https://img.shields.io/github/v/release/quargelk/easy-vless?style=flat-square&label=release&labelColor=161B33&color=8B5CF6)](https://github.com/quargelk/easy-vless/releases/latest)
[![Build](https://img.shields.io/github/actions/workflow/status/quargelk/easy-vless/build.yml?branch=main&style=flat-square&label=build&labelColor=161B33)](https://github.com/quargelk/easy-vless/actions/workflows/build.yml)
[![OpenWrt 24.10](https://img.shields.io/badge/OpenWrt-24.10-3B82F6?style=flat-square&logo=openwrt&logoColor=white&labelColor=161B33)](https://openwrt.org/)
[![License: GPL-3.0](https://img.shields.io/github/license/quargelk/easy-vless?style=flat-square&labelColor=161B33&color=6366F1)](https://github.com/quargelk/easy-vless/blob/main/LICENSE)

Easy VLESS puts a whole home network behind your own VLESS or Trojan server, and rules decide which traffic goes through it and which goes direct. You install it once on an OpenWrt router instead of configuring every phone, laptop and TV, then manage everything from the router's LuCI web interface, which can also explain *why* a particular site takes the route it does.

- **Protocols:** VLESS and Trojan over TCP, WebSocket, gRPC and HTTPUpgrade, with TLS, Reality and uTLS
- **Transparent proxying:** for LAN devices and the router itself through nftables (TPROXY or REDIRECT), powered by [sing-box](https://sing-box.sagernet.org/)
- **Rule-based routing:** by domain, IP, port, protocol and source, with ready-made rule sets and a separate target for each rule
- **Subscriptions:** link lists and Clash YAML, with automatic updates
- **Diagnostics:** Route Explain plus connection, DNS and forwarding checks that give a reason for every result
- **Maintenance:** a setup wizard that rolls back on failure, backup and restore, and in-place updates verified against the release's `SHA256SUMS`
- **Interface:** Russian and English

CI tests six OpenWrt 24.10 images covering x86-64, ARMv8, ARMv7 and MIPS. The project has also been tested on a Cudy TR3000 v1 router.
Requires OpenWrt 24.10.x with `opkg`. IPv6 TProxy and sing-box JSON subscriptions are experimental.

**[Repository](https://github.com/quargelk/easy-vless)** · **[Install](https://github.com/quargelk/easy-vless#%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0)** · **[Releases](https://github.com/quargelk/easy-vless/releases)** · **[Technical docs](https://github.com/quargelk/easy-vless/blob/main/docs/technical.md)** · **[Issues](https://github.com/quargelk/easy-vless/issues)**

<sub>The documentation is written in Russian. Parts of the runtime are derived from <a href="https://github.com/Openwrt-Passwall/openwrt-passwall2">PassWall2</a>.</sub>

## Tech I work with

<img src="https://skillicons.dev/icons?i=lua,bash,js,py,linux,docker,githubactions&theme=dark" alt="Lua, Shell, JavaScript, Python, Linux, Docker, GitHub Actions">

| Area | In practice |
| --- | --- |
| **Languages** | Lua and Shell for the router runtime, JavaScript for the LuCI interface, Python for tests and build tooling |
| **Platform** | OpenWrt, LuCI, UCI, rpcd/ubus, opkg packages |
| **Networking** | sing-box, nftables, TPROXY, dnsmasq |
| **Delivery** | GitHub Actions, with a Docker and QEMU test matrix across OpenWrt architectures |

## GitHub activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=quargelk&show_icons=true&hide_rank=true&hide_border=true&card_width=495&bg_color=0D1021&title_color=A78BFA&icon_color=60A5FA&text_color=C9CFEA" width="49%" alt="GitHub statistics for quargelk">
  <img src="https://streak-stats.demolab.com?user=quargelk&hide_border=true&background=0D1021&stroke=2E3560&ring=8B5CF6&fire=60A5FA&currStreakNum=F4F5FF&sideNums=F4F5FF&currStreakLabel=A78BFA&sideLabels=A78BFA&dates=7D86A8" width="49%" alt="GitHub contribution streak for quargelk">
</div>

## Contact

GitHub is the best place to reach me. For Easy VLESS bugs and questions, please [open an issue](https://github.com/quargelk/easy-vless/issues).

[![GitHub: quargelk](https://img.shields.io/badge/GitHub-quargelk-8B5CF6?style=flat-square&logo=github&logoColor=white&labelColor=161B33)](https://github.com/quargelk)
[![Easy VLESS issues](https://img.shields.io/badge/Easy_VLESS-issues-3B82F6?style=flat-square&logo=github&logoColor=white&labelColor=161B33)](https://github.com/quargelk/easy-vless/issues)
