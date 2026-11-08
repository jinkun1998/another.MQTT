# another.MQTT

Modern, cross-platform MQTT 5.0 desktop client for macOS, Windows, and Linux.

[![Website](https://img.shields.io/badge/Website-another.MQTT-00e599?style=flat&logo=googlechrome&logoColor=white)](https://jinkun1998.github.io/another.MQTT/)
[![Latest Release](https://img.shields.io/github/v/release/jinkun1998/another.MQTT?color=2997ff)](https://github.com/jinkun1998/another.MQTT/releases/latest)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Website: **[https://jinkun1998.github.io/another.MQTT/](https://jinkun1998.github.io/another.MQTT/)**

---

## Key Features

- **Topic-Scoped Isolation**: Click any active subscription topic to filter out noise and view only matched request/response pairs in real time.
- **Dynamic Action Resolution**: Subscribe to wildcards (`device/#`) and publish with relative subtopics (`reqcfg`, `/status`, `${base}/req_${timestamp}`).
- **Payload Collection Management**: Save reusable message presets with `Ctrl+S` / `Cmd+S`, preconfigured with custom actions and payload formats.
- **Complete MQTT 5.0 & 3.1.1 Specs**: User Properties, Correlation Data, Response Topic, Subscription Identifiers, Reason Codes, and Flow Control.
- **Multi-Format Data Viewer**: Real-time rendering for JSON, Plaintext, Hex, Base64, and CBOR with syntax tree highlighting and quick copying.
- **Cross-Platform Native Binaries**: Native macOS (Apple Silicon M-series & Intel), Windows (Installer & Portable), and Linux (AppImage, deb, rpm, snap).

## Download & Installation

Visit the [Website](https://jinkun1998.github.io/another.MQTT/) or download directly from the [Releases](https://github.com/jinkun1998/another.MQTT/releases/latest) page:

- **macOS (Apple Silicon)**: `another.MQTT-1.1.0-arm64.dmg`
- **macOS (Intel)**: `another.MQTT-1.1.0-x64.dmg`
  *(If blocked by macOS Gatekeeper on first open: run `xattr -cr /Applications/another.MQTT.app`)*
- **Windows**: `another.MQTT-Setup-1.1.0.exe` or portable `another.MQTT-1.1.0-x64-win.zip`
- **Linux**: `another.MQTT-1.1.0-x86_64.AppImage`, `.deb`, `.rpm`, or `.snap`

## Issues & Feature Requests

Found a bug or have a suggestion? Open an issue on [GitHub Issues](https://github.com/jinkun1998/another.MQTT/issues).

## License

Derivative work based on [MQTTX](https://github.com/emqx/MQTTX) under the Apache License 2.0.
