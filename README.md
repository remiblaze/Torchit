# Torchit — Saturation & Drive

![Torchit Interface](https://raw.githubusercontent.com/RemiBlaze/Torchit/main/torchit-ui-screenshot.png)

**Boutique saturation with house & techno sound DNA.**

Torchit is a free, high-fidelity saturation and drive plugin built for electronic music production — from subtle mix-bus warmth to full-blown sonic destruction. Designed by a producer, for producers.

Fully **signed and notarized** for macOS as **AU, VST3, and Standalone**.

---

## 🚀 Download & Install

Torchit ships as a clean, notarized macOS installer — no zip, no manual file routing.

1. Go to the [latest release](https://github.com/RemiBlaze/Torchit/releases/latest).
2. Download **`Torchit_Installer.pkg`**.
3. Double-click it and follow the installer. Because it's **signed & notarized by Apple**, it installs cleanly — no security warnings, no right-click, no "Open Anyway."
4. Restart your DAW and rescan plug-ins. Torchit appears under **Remi Blaze**.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 🎛️ Features

### Saturation Engine
- **Four saturation modes** — **Warm** (smooth tanh), **Grit** (asymmetric rational clip), **Tube** (triode character), **Tape** (magnetic compression).
- **Knee selector** — **Hard / Medium / Soft**, controlling the bend radius at the clipping threshold.
- **Drive** — from gentle enhancement to heavy distortion.
- **Oversampling** — **Draft (4×)** for low CPU while tracking, **HQ (8×)** for pristine anti-aliased mixdowns.
- **Auto-Gain (AG)** — inverse drive→output link that keeps loudness stable as you push the drive.

### Tone & Filtering
- **Three tone modes** — **BAL** (volume-stable tilt EQ), **GLW** (precision shelf for air/weight), **FX** (morph filter for creative sweeps).
- **Anti-mud HP filter** — 20–500 Hz low-cut with three slopes: **Smooth** (12 dB/oct), **Standard** (24 dB/oct), **Hard** (48 dB/oct).

### Monitoring & Workflow
- **Delta monitor** — solo exactly what the plugin adds, via phase-aligned forensic subtraction.
- **Live transfer curve** — real-time visual of the saturation shape.
- **21 factory presets**, plus user preset save/load and one-click randomize.
- **Input / Tone / Mix / Output** controls, instant bypass A/B, resizable UI.

---

## 🔬 Under the Hood

- **Static latency reporting** — a fixed latency to the host regardless of Draft/HQ, so switching oversampling never causes playback hiccups.
- **Phase-aligned delta** — separate oversampler instances give a forensic-grade null with zero dry-signal bleed.
- **DC blocker** — a 5 Hz high-pass that removes DC offset from asymmetric saturation, preserving headroom.
- **0 dBFS soft-clip ceiling** — a tanh soft clip at the end of the chain catches overs at the output.
- **Universal binary** — native on Apple Silicon (M1–M4) and Intel.

---

## 💻 System Requirements

- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- Any AU or VST3 host (your DAW of choice)

---

## 🎚️ Factory Presets (21)

| Preset | Mode | Best for |
| :--- | :--- | :--- |
| Init | Warm | Clean starting point |
| Subtle Warmth | Warm | Gentle bus saturation |
| Tape Heat | Tape | Lo-fi tape character |
| Vocal Glow | Tube | Vocal presence and air |
| Dirty Bass | Grit | Bass distortion |
| Acid Line Heat | Grit | acid bass lines |
| Kick Crunch | Grit | Drum transient bite |
| Hi-Hat Sizzle | Warm | High-frequency sparkle |
| Bus Glue | Tape | Mix bus cohesion |
| Vocal Grit | Grit | Aggressive vocal edge |
| Full Send | Grit | Maximum destruction |
| Remi Blaze Heat | Grit | Signature aggressive tone |
| Tube Warmth | Tube | Vintage tube character |
| Tape Compress | Tape | Tape-style compression |
| Bass Heat | Warm | Low-end enhancement |
| Master Soft Clip | Tape | Transparent master limiting |
| Kick Thump | Tape | Kick drum body and weight |
| Drum Bus Glow | Tube | Drum bus air and polish |
| Vocal Polish | Warm | Clean vocal enhancement |
| Synth Morpher | Grit | Synth grit and movement |
| Tape Lo-Fi | Tape | Lo-fi tape degradation |

---

## 🐛 Bugs & Issues

Found a UI glitch, resize bug, or DAW-specific quirk (especially AU window behaviour)? Please open an issue:

1. **[Issues](https://github.com/RemiBlaze/Torchit/issues)** tab → **New Issue**.
2. Include your macOS version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits

- **Developer:** designed and programmed by [Remi Blaze](https://remiblaze.com).
- **Framework:** built with [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.
