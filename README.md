<h1 align="center">
  <br>Yuanshen<br>
</h1>

<h4 align="center">A rule-based tunnel in Go.</h4>

<p align="center">
  <a href="https://github.com/Sud0x67/yuanshen/actions">
    <img src="https://img.shields.io/github/workflow/status/Sud0x67/yuanshen/Go?style=flat-square" alt="Github Actions">
  </a>
  <a href="https://goreportcard.com/report/github.com/Sud0x67/yuanshen">
    <img src="https://goreportcard.com/badge/github.com/Sud0x67/yuanshen?style=flat-square">
  </a>
  <img src="https://img.shields.io/github/go-mod/go-version/Sud0x67/yuanshen?style=flat-square">
  <a href="https://github.com/Sud0x67/yuanshen/releases">
    <img src="https://img.shields.io/github/release/Sud0x67/yuanshen/all.svg?style=flat-square">
  </a>
  <a href="https://github.com/Sud0x67/yuanshen/releases/tag/premium">
    <img src="https://img.shields.io/badge/release-Premium-00b4f0?style=flat-square">
  </a>
</p>

## Features

- Local HTTP/HTTPS/SOCKS server with authentication support
- Shadowsocks(R), VMess, Trojan, Snell, SOCKS5, HTTP(S) outbound support
- Built-in [fake-ip](https://www.rfc-editor.org/rfc/rfc3089) DNS server that aims to minimize DNS pollution attack impact. DoH/DoT upstream supported.
- Rules based off domains, GEOIP, IP-CIDR or process names to route packets to different destinations
- Proxy groups allow users to implement powerful rules. Supports automatic fallback, load balancing or auto select proxy based off latency
- Remote providers, allowing users to get proxy lists remotely instead of hardcoding in config
- Transparent proxy: Redirect TCP and TProxy TCP/UDP with automatic route table/rule management
- Hot-reload via the comprehensive HTTP RESTful API controller

## Getting Started
Documentations are available at [GitHub Wiki](https://github.com/Sud0x67/yuanshen/wiki).

## Development
If you want to build a Go application that uses Clash as a library, check out the [GitHub Wiki](https://github.com/Sud0x67/yuanshen/wiki/Using-Clash-in-your-Golang-program).

## Credits

* [riobard/go-shadowsocks2](https://github.com/riobard/go-shadowsocks2)
* [v2ray/v2ray-core](https://github.com/v2ray/v2ray-core)
* [WireGuard/wireguard-go](https://github.com/WireGuard/wireguard-go)

## License

This software is released under the GPL-3.0 license.

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FDreamacro%2Fclash.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FDreamacro%2Fclash?ref=badge_large)
