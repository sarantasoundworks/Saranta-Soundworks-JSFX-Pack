# Lozengrad JSFX Plugin Series

A collection of audio DSP plugins developed by **Saranta Soundworks** — the mix & mastering studio of **Saranta**.

Download the latest version for free at [sarantasoundworks.com](https://sarantasoundworks.com) or grab them from the [GitHub releases](https://github.com/sarantasoundworks/lozengrad-jsfx/releases).

## Plugins

| Plugin | Type | Description |
|--------|------|-------------|
| **Lozengrad Amfi** | Guitar Amp Sim | Gate, input gain, drive, 3-band EQ, 3 cabinet IR models, Mid Spice, bus compressor, master volume |
| **Lozengrad Balans EQ** | Parametric EQ | 8-band EQ with HPF, LPF, Low Shelf, High Shelf, Bell per band. Built-in FFT spectrum analyzer with EQ curve overlay |
| **Lozengrad EQuinox** | Tone EQ | Simple bass/treble control with Low and High frequency adjustments, FFT display |
| **Lozengrad Feeltre** | Multi-Mode Filter | LPF, HPF, BPF, APF, Tilt EQ, Low Shelf, High Shelf, Tilt Shelf with gain control and spectrum analyzer |
| **Lozengrad Kompresor** | Compressor/Limiter | VCA-style compressor with threshold, ratio, attack/release, knee (hard/medium/soft), detector thrust, feedforward/feedback modes, headroom control, make-up gain, parallel mix, GR meter |
| **Lozengrad MB Saturasyon** | Multiband Saturation | 3-band (Low/Mid/High) saturation with Linkwitz-Riley crossover, 4 saturation modes (Soft Clip/Tube/Tape/Hard Clip), auto gain per band, oversampling (2x/4x), solo listen, dry/wet mix |
| **Lozengrad Pedal** | Multi-Pedal Distortion | 7 pedal modes (Vintage Clip, Turbo Clip, Orange Drive, Green Drive, Slam Boost, Modern Drive, Grind Distortion), per-pedal circuit-modeled tone shaping, gain/tone/level controls, 3-band Post-EQ (Low/Mid/High), oversampling (4x/8x), integrated stereo processing |
| **Lozengrad RetroSpec** | FFT Visualizer | Retro-styled spectrum analyzer with 10 visual styles (Terminal, Blocks, Matrix, Retro, Mask:Smile, Mask:Crescent, Mask:Skull, Radar, Hanzi, Wormhole, HexDump) and 13 color themes |
| **Lozengrad Spyke** | Transient Shaper | Attack and Sustain controls with output level. Enhances or softens transients independently |

## Installation

### In REAPER (native)

1. **Download** the plugin files (`.jsfx` or extensionless JSFX files) from this repository.
2. **Copy** them into your REAPER `Effects` folder:
   - **Windows:** `%APPDATA%\REAPER\Effects\`
   - **macOS:** `~/Library/Application Support/REAPER/Effects/`
   - **Linux:** `~/.config/REAPER/Effects/`
3. **Refresh** the FX browser in REAPER (right-click -> "Refresh list" or press `F5`).
4. The plugins will appear under the Saranta Soundworks or Lozengrad category.

### In other DAWs (via ReaJS / ReaPlugs)

JSFX is REAPER's native plugin format and won't load directly in other DAWs. However, you can use them anywhere with **ReaJS**, a free VST/VST3/AU/AAX wrapper:

1. Download and install [ReaPlugs](https://www.reaper.fm/reaplugs/) (free, no REAPER license required).
2. Open **ReaJS VST** (or VST3 / AU) as a plugin in your DAW.
3. In the ReaJS window, click **"Load..."** and navigate to the downloaded JSFX file.
4. The plugin loads and works exactly as it would inside REAPER.

**Supported DAWs via ReaJS:** Ableton Live, FL Studio, Logic Pro, Cubase, Studio One, Pro Tools, Bitwig Studio, and any VST/AU/AAX-compatible host.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

Built by [Saranta Soundworks](https://sarantasoundworks.com) — Professional mixing & mastering.
