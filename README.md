## Noisyloop

Engineer, full-stack developer, creator. 20+ years writing code across the full stack, from product interfaces down to the systems layer where most people stop looking.

Two tracks: audiovisual / generative creative coding and security and system tooling.

AI is part of my development workflow for research, learning, documentation, and code generation where appropriate. All architectural decisions, validation, testing, and final implementations are my responsibility. I treat AI as an assistant, not an authority.

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
