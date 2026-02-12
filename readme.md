# 🌌 Nebula Visualizer

A **Milkdrop-style audio visualizer** for your browser. Reacts to **microphone** or **tab audio** in real-time with neon particles, waveforms, and pulsating beats.  

---

## Features

- 🎤 Microphone input  
- 🖥 Tab audio capture (Chrome/Edge only)  
- ✨ Particle system + frequency bars + waveform + center pulse  
- ⚡ Smooth, optimized animations  
- 🖤 Dark, neon-inspired UI  

---

## Quick Start

1. Open `index.html` in **Chrome** or **Edge**  
2. Click **Microphone** or **Tab Audio**  
3. Watch the visualizer react to sound  
4. Press **Stop** to reset  

> ⚠️ System audio capture is **not available** in browsers. Tab audio works only in Chromium-based browsers.  

---

## Controls

| Button | Action |
|--------|--------|
| **Microphone** | Start microphone visualization |
| **Tab Audio** | Capture tab audio (Chrome/Edge) |
| **Stop** | Stop visualization & reset canvas |
| **Mode Indicator** | Shows current audio source |

---

## Customization

- `PARTICLE_COUNT` – number of particles  
- `FFT_SIZE`, `SMOOTHING` – audio analysis settings  
- Colors – modify `hsla()` values in script  

---

## Browser Support

| Browser | Microphone | Tab Audio |
|---------|:----------:|:---------:|
| Chrome  | ✅ | ✅ |
| Edge    | ✅ | ✅ |
| Firefox | ✅ | ❌ |
| Safari  | ✅ | ❌ |

---

## License

MIT License – free to use and modify.  
