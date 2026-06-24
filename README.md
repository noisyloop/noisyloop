## Noisyloop

Engineer, full-stack developer, creator. 20+ years writing code across the full stack, from product interfaces down to the systems layer where most people stop looking.

AI is part of my development workflow for research, learning, documentation, and code generation where appropriate. All architectural decisions, validation, testing, and final implementations are my responsibility. I treat AI as an assistant, not an authority. 

---

## Security Tooling

**[Glasswally](https://github.com/noisyloop/glasswally)**
Real-time LLM distillation attack detection via eBPF kernel uprobes.
Hooks into inference processes at the kernel boundary. Fingerprints query patterns. Alerts before a model theft completes. MITRE ATT&CK mapped.
`Rust` · `eBPF` · `Detection Engineering` · `AI Security`

---

**[ghostwire](https://github.com/noisyloop/ghostwire)**
Passive USB device fingerprinting and anomaly detection daemon.
Detects BadUSB implants, HID injection devices, and hardware anomalies at the enumeration layer — before the OS finishes booting the driver. Silent. Rust. No kernel module required.
`Rust` · `Linux` · `Endpoint Security` · `Hardware Fingerprinting`

---

**[Milly](https://github.com/noisyloop/milly)**
The first local LLM with a built-in security layer.
HMAC-signed memory. TF-IDF RAG. Air-gapped by design. Zero egress. 136 passing tests covering memory integrity, injection resistance, and audit logging.
`Python` · `Ollama` · `AI Security`

---

**[passive-intel](https://github.com/noisyloop/passive-intel)**
Passive threat-intel console for defenders. CISA KEV, URLhaus, and Feodo Tracker in one UI — actively exploited CVEs, live malware URLs, and botnet C2 IPs. No API keys. No cost. Includes a blocklist endpoint you can feed directly into nginx, ufw, or Cloudflare.
`JavaScript` · `OSINT` · `Threat Intel`

---

**[EverythingOS](https://github.com/noisyloop/everythingos)**
Security-first multi-agent framework for autonomous systems.
ModelGuard input/output validation. DecisionLedger audit trail. NIST AI RMF aligned. 81/81 tests passing, zero TypeScript errors. Built under the Robots For Peace framework.
`TypeScript` · `Autonomous Agents` · `AI Governance`

---

## Other Work

| Project | Description |
|--------|-------------|
| [Durpie](https://github.com/noisyloop/durpie) | Modular web security testing toolkit built on mitmproxy |
| [UAP-51](https://github.com/noisyloop/uap-51) | Autonomous flight simulator in React / Three.js |
| [retro-os](https://github.com/noisyloop/retro-os) | Working retro OS with games, runs in the browser |
| [prism-video-synth](https://github.com/noisyloop/prism-video-synth) | Mobile-optimized video synthesizer in React |
| [pulse-drum-machine](https://github.com/noisyloop/pulse-drum-machine) | MIDI-capable drum machine for desktop and mobile |

---

## Stack

`Rust` · `Python` · `TypeScript` · `JavaScript` · `React` · `Three.js` · `eBPF` · `mitmproxy` · `Ollama`
Kernel-level tooling · Detection engineering · AI security · Autonomous systems · Creative coding

---

> *The purpose is not just to build tools — but to fully understand how they work and why. Running them is not enough.*
