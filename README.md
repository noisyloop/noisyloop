## Noisyloop

Engineer, full-stack developer, creator. 20+ years writing code across the full stack, from product interfaces down to the systems layer where most people stop looking.

Two tracks: security and systems tooling, and audiovisual / generative creative coding.

AI is part of my development workflow for research, learning, documentation, and code generation where appropriate. All architectural decisions, validation, testing, and final implementations are my responsibility. I treat AI as an assistant, not an authority.

---

## Security Tooling

**[Encoding Station](https://github.com/noisyloop/encoding-station)**
Client-side multi-transform encoder/decoder for CTF work and security research.
Parallel mode runs all transforms simultaneously. Pipeline mode chains them in drag-reorderable steps. Base64, Hex, URL, HTML entities, ROT13/47, Binary, XOR — all processed locally, no server, no build step.
`JavaScript` · `React` · `CTF` · `Security Research`

---

**[pretty-good-encryption](https://github.com/noisyloop/pretty-good-encryption)**
Client-side encryption tooling built on the Web Crypto API.
`JavaScript` · `Web Crypto API` · `Cryptography` · `Security Research`

---

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

**[driftnet](https://github.com/noisyloop/driftnet)**
Browser-based privacy self-audit and VPN leak detector. Repurposes WebRTC ICE enumeration, an image-load timing side-channel, and canvas/WebGL fingerprinting to profile your own device's network identity across sessions — flagging unexpected public IPs, IPv6 leaking past a tunnel, and reachable remote-admin ports. No install, no server, no elevated privileges.
`TypeScript` · `WebRTC` · `Browser Side-Channels` · `Privacy`

---

**[Milly](https://github.com/noisyloop/Milly)**
Local LLM with a built-in security layer. HMAC-signed memory, TF-IDF RAG, Guardian injection detection, and a tamper-evident audit trail. Zero egress by design. 157 passing tests covering memory integrity, injection resistance, and audit logging.
`Python` · `Ollama` · `AI Security`

---

**[passive-intel](https://github.com/noisyloop/passive-intel)**
Passive threat-intel console for defenders. CISA KEV, URLhaus, and Feodo Tracker in one UI — actively exploited CVEs, live malware URLs, and botnet C2 IPs. No API keys. No cost. Includes a blocklist endpoint you can feed directly into nginx, ufw, or Cloudflare.
`JavaScript` · `OSINT` · `Threat Intel`

---

**[Durpie](https://github.com/noisyloop/durpie)**
Modular web security testing toolkit built on mitmproxy.
`Python` · `mitmproxy` · `Web Security`

---

**[reflection-recon](https://github.com/noisyloop/reflection-recon)**
Research toolkit for two imaging-forensics problems. PRNU sensor-fingerprinting for source-camera identification (wavelet-MMSE residual, FFT-PCE detection), and corneal-reflection recovery — reconstructing what an eye or glasses reflected on a video call, via Fourier–Mellin registration and catchlight-driven Richardson–Lucy deconvolution. Ships as a reproducible Python bench and a zero-install web demo. Deliberately honest about its limits: a teaching instrument, not a courtroom pipeline. *(in active testing)*
`Python` · `Digital Forensics` · `Image Analysis` · `PRNU`

---

**[EverythingOS](https://github.com/noisyloop/everythingos)**
Security-first multi-agent framework for autonomous systems.
ModelGuard input/output validation. DecisionLedger audit trail. NIST AI RMF aligned. 81/81 tests passing, zero TypeScript errors. Built under the Robots For Peace framework.
`TypeScript` · `Autonomous Agents` · `AI Governance`

---

## Creative Coding

**[soundgineer](https://github.com/noisyloop/soundgineer)**
Browser-based Vital-style wavetable synthesizer. 16-voice engine running sample-accurate DSP inside an AudioWorklet — three wavetable oscillators with FFT spectral morphing, dual analog-modeled filters, 6 DAHDSR envelopes, 8 drawable LFOs, a 32-slot modulation matrix, and a reorderable FX rack. Zero runtime dependencies, hand-rolled Canvas/WebGL2 UI, MIDI-capable. *(work in progress)*
`TypeScript` · `Web Audio` · `AudioWorklet` · `DSP`

---

**[mastering](https://github.com/noisyloop/mastering)**
Browser-based audio mastering studio. Full chain — parametric + mid/side EQ, 4-band multiband compression, transient shaping, 4×-oversampled true-peak limiting — with automatic LUFS targeting (ITU-R BS.1770-4) for Spotify / Apple / YouTube, reference-track EQ matching, and live spectrum / goniometer / LUFS metering. All DSP client-side; your audio never leaves the machine.
`JavaScript` · `Web Audio` · `DSP` · `Loudness`

---

**[photoshlopper](https://github.com/noisyloop/photoshlopper)**
Browser-based raster editor — an honest Photoshop clone for stickers and generative art. 16 GLSL blend modes shared verbatim between the live compositor and the exporter, non-destructive effect layers, layer masks, Photoshop-parity shortcuts. Exports past pixels: die-cut 3D sticker meshes (GLB/OBJ), compile-checked fragment shaders (raw WebGL2 / Shadertoy / ISF), and PSD.
`TypeScript` · `WebGL2` · `three.js` · `Creative Coding`

---

**[prism-video-synth](https://github.com/noisyloop/prism-video-synth)**
Mobile-optimized video synthesizer in React; export visuals as images at multiple size formats.
`React` · `Creative Coding`

---

**[pulse-drum-machine](https://github.com/noisyloop/pulse-drum-machine)**
MIDI-capable drum machine for desktop and mobile.
`JavaScript` · `Web Audio` · `MIDI`

---

**[retro-os](https://github.com/noisyloop/retro-os)**
Working retro OS with games, running entirely in the browser.
`JavaScript` · `Systems`

---

**[UAP-51](https://github.com/noisyloop/uap-51)**
Autonomous flight simulator in React / Three.js.
`React` · `Three.js` · `Simulation`

---

## Stack

`Rust` · `Python` · `TypeScript` · `JavaScript` · `React` · `Three.js` · `eBPF` · `mitmproxy` · `Ollama` · `Web Audio` · `AudioWorklet` · `WebGL2` · `GLSL`

Kernel-level tooling · Detection engineering · AI security · Autonomous systems · Creative coding · Audiovisual / DSP · Generative art

---

> *The purpose is not just to build tools — but to fully understand how they work and why. Running them is not enough.*
