## noisyloop

Low-level software, security tooling, audio and games. Mostly Rust, C++ and Go, built to run locally on your own machine. 

### Systems and Tech

| Project | Stack | What it is |
| --- | --- | --- |
| [btw](https://github.com/noisyloop/btw) | Swift, C, Shell, QML | A custom Arch-based Linux desktop with a fractal theme. Boots in a VM from a native macOS launcher on Apple silicon, one command on Windows (WSL), or installs on Arch and Omarchy. |
| [Fleet-51](https://github.com/noisyloop/Fleet-51) | Rust | Run a fleet of private AI bots entirely on your computer. Local models through Ollama, Hugging Face GGUF downloads, multi-bot teams, automations, and a bootable ISO for VM isolation. |

### Security

| Project | Stack | What it is |
| --- | --- | --- |
| [Glasswally](https://github.com/noisyloop/Glasswally) | Rust, tokio, eBPF | Detects LLM distillation campaigns. Fuses 16 behavioral and infrastructure signals (TLS fingerprints, velocity, account clustering) into per-account risk decisions, with optional eBPF TLS capture. |
| [talking-tube](https://github.com/noisyloop/talking-tube) | Rust | An end-to-end encrypted Discord alternative. Signal protocol DMs (X3DH + Double Ratchet), sender-key group channels with key rotation, device-held identity, and relays that only ever see ciphertext. |
| [reverse-magic](https://github.com/noisyloop/reverse-magic) | Go (WASM), JavaScript | Teardown, a local static file analyzer. Parses PE, ELF, Mach-O, PDF, archives and more, disassembles six architectures, and flags indicators and entropy. Files are never uploaded or executed. |

### Audio

| Project | Stack | What it is |
| --- | --- | --- |
| [AudioZero](https://github.com/noisyloop/AudioZero) | Rust, C++, JUCE | A native digital audio workstation, written mostly in Rust, for macOS, Windows and Linux. Arrangement view, piano roll, mixer, VST3 hosting, and Operator, a built-in 4-operator FM synth. |
| [GrainBrain](https://github.com/noisyloop/grainbrain) | C++, JUCE | A granular sample synthesizer as AU, VST3 and standalone. MIDI-triggered grain clouds of up to 256 overlapping grains, sample loading and modulation. |

### Games

| Project | Stack | What it is |
| --- | --- | --- |
| [TRIPPY](https://github.com/noisyloop/TRIPPY) | C++, SDL2 | A psychedelic top-down room explorer. All music is synthesized in code and reacts to how you move, and the visuals pulse on its beat. |
| [RetroOS](https://github.com/noisyloop/retro-os) | C++, SDL2, React | A Windows 95-style desktop with Snake, Minesweeper, Tetris, Memory, Pong and Paint. Runs in the browser, or as a native C++ rewrite in one small binary. |

---

Each project above has been through bug checks and a security review. Notes live in each repo.
