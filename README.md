# Lozengrad JSFX Plugin Series

A collection of audio DSP plugins developed by **Saranta Soundworks** — the mix & mastering studio of **Saranta**.

Download the latest version for free at [sarantasoundworks.com](https://sarantasoundworks.com) or grab them from the [GitHub releases](https://github.com/sarantasoundworks/lozengrad-jsfx/releases).

## Plugins

| Plugin | Type | Description |
|--------|------|-------------|
| **Lozengrad Amfi** | Guitar Amp Sim | Gate, input gain, drive, 3-band EQ, 3 cabinet IR models, Mid Spice, bus compressor, master volume |
| **Lozengrad Amfi V2** | Guitar Amp Sim | Dual-mode preamp: **Classic** (cascaded tube gain stages, cold clipper, tone stack, presence, sag, resonance) and **Hard** (4-stage cascaded hard-clipper + auto gain). Gate, input gain, drive, 3-band tone stack (bass/mid/treble), sag, presence, resonance depth, 3 cabinet IR models, bright cap (low/high), transient enhancer, harmonic exciter, master volume |
| **Lozengrad Drumbus One** | Adaptive Drum Bus | Multiband compression and adaptive dynamics tailored for drum bus processing. Single-knob intensity controls the entire chain — from compression and EQ to transient shaping — automatically adapting to the mix |
| **Lozengrad Bassbus One** | Adaptive Bass Bus | Single-knob bass bus processor with dual-zone intensity: 0-50 covers the full clean adaptive chain (mud suppression, feedback compression, sub weight, saturation, EQ, multiband), 50-100 adds grit + slam parallel compression for aggressive bus-slam character. Adapts to playing dynamics automatically |
| **Lozengrad Guitarbus One** | Adaptive Guitar Bus | Multiband compression, saturation, EQ, and dynamic control designed for guitar bus processing. Single-knob intensity blends compression, harmonic enhancement, and frequency shaping that adapts to playing dynamics |
| **Lozengrad Synthbus One** | Adaptive Synth Bus | Single-knob synth bus processor: sub anchor (mono weight low end), resonance tamer (filter-screech control), glue compressor, ensemble widener (unison/chorus thickening), harmonic warmth, precision EQ, 4-band multiband compressor, limiter. Analyzes sub energy, resonance, air, stereo width, and attack density — adapts to pads, plucks, and arps automatically |
| **Lozengrad Masterbus One** | Adaptive Mastering Bus | Single-knob mastering chain: tape saturation, passive tube EQ, soft clipper, bus compressor, precision mastering EQ (static + dynamic bands), true peak limiter. Adaptive decision engine analyzes spectral balance, crest factor, transient density — everything scales from transparent to full push with one intensity knob |
| **Lozengrad Bas Amfi v1.2** | Bass Amp Sim (Current) | Split-band bass amplifier simulator with separate low and high frequency processing. Low channel focuses bass fundamentals with saturation, high channel adds pre-emphasis and multi-stage clipping. Includes tilt EQ, cabinet simulation, character control, and dry/wet blend |
| **Lozengrad Bas Amfi Legacy** | Bass Amp Sim (Legacy) | Original bass amplifier simulator — preserved for sessions that require the v1.0 sound and workflow |
| **Lozengrad Balans EQ** | Parametric EQ | 8-band EQ with HPF, LPF, Low Shelf, High Shelf, Bell per band. Built-in FFT spectrum analyzer with EQ curve overlay |
| **Lozengrad EQuinox** | Tone EQ | Simple bass/treble control with Low and High frequency adjustments, FFT display |
| **Lozengrad Feeltre** | Multi-Mode Filter | LPF, HPF, BPF, APF, Tilt EQ, Low Shelf, High Shelf, Tilt Shelf with gain control and spectrum analyzer |
| **Lozengrad Kompresor V2** | Compressor/Limiter | V2 upgrade: Advanced VCA compressor with scrolling waveform + gain reduction visualizer, 3 knee modes (Hard/Medium/Soft), detector thrust HPF, feedforward/feedback tone, headroom staging, Input/Output Gain, Detector Blend (peak/RMS with crest factor normalization), Dynamic Saturation (GR-driven harmonic density), Punch Compensation (transient restoration via fast/slow envelope delta), Auto Makeup (instant-attack GR tracking), parallel mix |
| **Lozengrad Kompresor** | Compressor/Limiter | VCA-style compressor with threshold, ratio, attack/release, knee (hard/medium/soft), detector thrust, feedforward/feedback modes, headroom control, make-up gain, parallel mix, GR meter |
| **Lozengrad MB Saturasyon V2** | Multiband Saturation | V2 rewrite: 3-band (Low/Mid/High) saturation with real oversampling (2x/4x/AUTO), LR4 Linkwitz-Riley crossovers, per-band independent mode (Tape/Tube/Soft/Hard) and Character control (clean→aggressive), hybrid auto gain per band (RMS+peak blend), 4 output stage models (Transparent/Soft Clip/Transformer/Tape), solo listen, delta mode, Input Gain/Output Volume |
| **Lozengrad MB Saturasyon** | Multiband Saturation | 3-band (Low/Mid/High) saturation with Linkwitz-Riley crossover, 4 saturation modes (Soft Clip/Tube/Tape/Hard Clip), auto gain per band, oversampling (2x/4x), solo listen, dry/wet mix |
| **Lozengrad Klip** | Clipper/Limiter | 4 clipping modes (Hard Clip/Soft Clip/Tube Clip/Tape Clip), oversampling (1x/2x/4x), Harmonic Tilt (even-order harmonic shaping), Frequency Weight (pre-emphasis filter for transparent high-end), Input/Threshold/Output gain, dry/wet mix, scrolling waveform + clip indicator display |
| **Lozengrad MicroDelay** | Stereo Width/Depth | Procedural micro-delay modulation engine. M/S encode → Mackey-Glass chaotic modulation → hybrid Lagrange/Thiran interpolation → phase alignment. Replaces LFO-based chorus/delay with organic, non-repeating stereo expansion. 6 controls: Width, Base Delay (5-35ms), Mod Rate, Mod Depth, Live/HQ mode, Mix |
| **Lozengrad Pedal** | Multi-Pedal Distortion | 7 pedal modes (Vintage Clip, Turbo Clip, Orange Drive, Green Drive, Slam Boost, Modern Drive, Grind Distortion), per-pedal circuit-modeled tone shaping, gain/tone/level controls, 3-band Post-EQ (Low/Mid/High), oversampling (4x/8x), integrated stereo processing |
| **Lozengrad RetroSpec** | FFT Visualizer | Retro-styled spectrum analyzer with 10 visual styles (Terminal, Blocks, Matrix, Retro, Mask:Smile, Mask:Crescent, Mask:Skull, Radar, Hanzi, Wormhole, HexDump) and 13 color themes |
| **Lozengrad Spektra** | Spectral Density Controller | FFT-based intelligent spectral compressor. Builds a long-term EMA spectral profile, detects excess via local contrast analysis with psychoacoustic weighting, applies per-bin gain reduction with bidirectional frequency smoothing and per-bin attack/release. Interactive spectrum display with draggable HP/LP/Bell filters, wet/dry mix, auto makeup, output soft-clipper |
| **Lozengrad Spyke** | Transient Shaper | Attack and Sustain controls with output level. Enhances or softens transients independently |
| **Lozengrad Trafo** | Transformer Saturation | Dual-path saturator with ADAA anti-aliasing. Asymmetric "Nickel" path for transient attack, symmetric "Iron" path with hysteresis feedback for sustain. Transient-driven morph crossfade between paths. Real-time waveform scope with color-coded blend (cyan=Nickel, orange=Iron), output gain, clip, auto gain |
| **Lozengrad Hudut** | True Peak Limiter | Threshold/ceiling limiter with polyphase oversampling (1x/2x/4x/8x), harmonic inflate (Oxford-style), dual-window auto-release, peak hold, lookahead, sidechain HPF, and scrolling waveform/GR display |

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

This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License — see the [LICENSE](LICENSE) file for details.

---

Built by [Saranta Soundworks](https://sarantasoundworks.com) — Professional mixing & mastering.
