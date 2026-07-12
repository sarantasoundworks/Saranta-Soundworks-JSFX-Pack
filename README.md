# Lozengrad JSFX Plugin Series

A collection of 23 audio DSP plugins developed by **Saranta Soundworks**.

Download the latest version for free at [sarantasoundworks.com](https://sarantasoundworks.com).

## Plugins

| Plugin | Type | Description |
|--------|------|-------------|
| **Lozengrad Amfi** | Guitar Amp Sim | Gate, input gain, drive, 3-band EQ, 3 cabinet IR models, Mid Spice, bus compressor, master volume |
| **Lozengrad Amfi V2** | Guitar Amp Sim | Dual-mode preamp: Classic (cascaded tube gain stages, cold clipper, tone stack, presence, sag, resonance) and Hard (4-stage cascaded hard-clipper + auto gain). Gate, transient enhancer, harmonic exciter, 3 cab IRs |
| **Lozengrad Bas Amfi v1.2** | Bass Amp Sim (Current) | Multi-stage preamp (6-stage), power amp with transformer saturation, Speaker Coloration Engine (10-stage cab sim), frequency-dependent drive, auto oversampling, Character macro with 14 parameters and 5 breakpoints |
| **Lozengrad Bas Amfi Legacy** | Bass Amp Sim (Legacy) | Original single-stage bass amp sim — simpler 3-stage hard clip, basic cab sim. Maintained for sessions requiring the v1.0 sound |
| **Lozengrad Balans EQ** | Parametric EQ | 8-band EQ with HPF, LPF, Low Shelf, High Shelf, Bell per band. Built-in FFT spectrum analyzer with EQ curve overlay |
| **Lozengrad EQuinox** | Tone EQ | 2-band tone EQ with asymmetric filter pairing for smile curve shaping |
| **Lozengrad Feeltre** | Multi-Mode Filter | LPF, HPF, BPF, APF, Tilt EQ, Low Shelf, High Shelf, Tilt Shelf with gain control and spectrum analyzer |
| **Lozengrad Kompresor V2** | Compressor/Limiter | VCA compressor with dynamic saturation, punch compensation, dual-stage release, auto makeup, feedforward/feedback, detector blend, headroom staging, scrolling waveform + GR visualizer |
| **Lozengrad Kompresor** | Compressor/Limiter | VCA-style compressor with threshold, ratio, attack/release, knee, detector thrust, feedforward/feedback, parallel mix, GR meter |
| **Lozengrad MB Saturasyon V2** | Multiband Saturation | 3-band saturation with real oversampling (2x/4x/AUTO), LR4 crossovers, 4 modes per band (Tape/Tube/Soft/Hard), Character macro, 4 output stage models, solo listen, delta mode |
| **Lozengrad MB Saturasyon** | Multiband Saturation | 3-band saturation with LR4 crossover, 4 modes (Soft Clip/Tube/Tape/Hard Clip), auto gain, oversampling (2x/4x), solo listen |
| **Lozengrad Klip** | Clipper/Limiter | 4 clipping modes (Hard/Soft/Tube/Tape), oversampling (1x/2x/4x), Harmonic Tilt, Frequency Weight, scrolling waveform + clip indicator |
| **Lozengrad MicroDelay** | Stereo Width/Depth | M/S stereo width modulator using Mackey-Glass chaotic DDE, hybrid Lagrange/Thiran interpolation |
| **Lozengrad Pedal** | Multi-Pedal Distortion | 7 pedal modes, per-pedal circuit-modeled tone shaping, gain/tone/level, 3-band Post-EQ, oversampling (4x/8x) |
| **Lozengrad RetroSpec** | FFT Visualizer | 11 visual styles (Terminal, Blocks, Matrix, Retro, Mask:Smile, Mask:Crescent, Mask:Skull, Radar, Hanzi, Wormhole, HexDump) and 13 color themes |
| **Lozengrad Spektra** | Spectral Density Controller | FFT-based intelligent spectral compressor with EMA profile, local contrast analysis, psychoacoustic weighting, interactive spectrum display |
| **Lozengrad Spyke** | Transient Shaper | 3-envelope detection (fast/slow/sustain), level-normalized gain modulation, attack and sustain controls |
| **Lozengrad Trafo** | Transformer Saturation | Dual-path saturator with ADAA: Nickel asymmetric + Iron symmetric with hysteresis, transient-driven morph crossfade |
| **Lozengrad Hudut** | True Peak Limiter | Polyphase oversampling (1x/2x/4x/8x), harmonic inflator, dynamic dual-window release, lookahead, sidechain HPF |
| **Lozengrad Guitarbus One** | Adaptive Guitar Bus | Single-knob analysis of chug density, palm mute ratio, pick attack; drives mud suppression, bus compressor, mid saturation, precision EQ, 4-band multiband comp, harshness control |
| **Lozengrad Drumbus One** | Adaptive Drum Bus | Single-knob analysis of low/mid/presence/air bands, crest factor, transient density; drives cleanup EQ, transient shaper, compressor, saturation, tone EQ, clipper, limiter |
| **Lozengrad Masterbus One** | Adaptive Mastering Bus | Tape saturation, passive tube EQ, soft clipper, bus compressor, precision mastering EQ (static + dynamic bands), true peak limiter |
| **Lozengrad Synthbus One** | Adaptive Synth Bus | Sub anchor, resonance tamer, glue compressor, ensemble widener, harmonic warmth, precision EQ, 4-band multiband comp |
| **Lozengrad Bassbus One** | Adaptive Bass Bus | Dual-zone intensity (0-50 clean, 50-100 grit+slam), mud suppression, feedback bass comp, sub weight enhancer, harmonic saturation, string noise control, parallel slam comp |

## Installation

### In REAPER (native)

1. **Download** the plugin files from this repository.
2. **Copy** them into your REAPER `Effects` folder:
   - **Windows:** `%APPDATA%\REAPER\Effects\`
   - **macOS:** `~/Library/Application Support/REAPER/Effects/`
   - **Linux:** `~/.config/REAPER/Effects/`
3. **Refresh** the FX browser in REAPER (right-click -> "Refresh list" or press `F5`).

### In other DAWs (via ReaJS)

JSFX is REAPER's native format. Use with **ReaJS** (free VST/VST3/AU/AAX wrapper):
1. Download [ReaPlugs](https://www.reaper.fm/reaplugs/) (free, no REAPER license required)
2. Open **ReaJS VST** in your DAW
3. Click **"Load..."** and navigate to the JSFX file

Supported in: Ableton Live, FL Studio, Logic Pro, Cubase, Studio One, Pro Tools, Bitwig Studio.

## License

Licensed under the **Saranta Soundworks Free License (SSFL) v1.0**. See the [LICENSE](LICENSE) file for full terms.

Commercial music use is fully permitted. The plugins may not be sold or bundled in paid products. See [sarantasoundworks.com/legal](https://sarantasoundworks.com/legal.html) for details.

---

Built by [Saranta Soundworks](https://sarantasoundworks.com)
