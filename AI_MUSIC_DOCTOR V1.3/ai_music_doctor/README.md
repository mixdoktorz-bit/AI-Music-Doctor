<uploaded_files github_repo=mixdoktorz-bit/AI-Music-Doctor>
<file=AI_MUSIC_DOCTOR V1.3/ai_music_doctor/README.md>
# AI Music Doctor

**Professional Mastering Suite for AI-Generated Music**

A hardware-style audio processing application with mastering-grade controls, psychoacoustic denoising, and artifact-free EQ.

## What's New in v4.0

### 🎛️ Professional Mastering Knobs (±3dB max)
- **Air** - High frequency sparkle (8-16kHz shelf)
- **Body** - Low-mid warmth (100-300Hz)
- **Focus** - Mid presence/clarity (1-4kHz)
- **Push** - Gentle saturation/compression
- **Width** - Stereo width using M/S processing
- **Volume** - Output level (LAST in chain)
- **Transients** - Attack/sustain shaping
- **Analog** - Warm even-harmonic saturation
- **Bass Punch** - Low-end impact (60-120Hz)

### 🔮 Psychoacoustic DENOISER
Based on Fletcher-Munson curves and Bark Scale critical bands:
- One main **SENSITIVITY** knob (0-100%)
- **6 Glowing Orbit Buttons** around the knob:
  - **Boomy** (100-250Hz) - Excessive low resonance
  - **Boxy** (150-250Hz) - Hollow/resonant sound
  - **Muddy** (200-500Hz) - Lack of clarity
  - **Honky** (500Hz-1.5kHz) - Nasal midrange
  - **Harsh** (2-6kHz) - Piercing high-mids
  - **Sizzle** (8-12kHz) - Excessive high-frequency

Each orbit button:
- Glows based on detected problem level
- Click to toggle on/off
- Zero-latency processing

### 🎚️ Artifact-Free EQ
- 9-band graphical EQ with draggable points
- Maximum ±2.4dB per band
- Proper biquad filter design with coefficient smoothing
- NO zipper noise or sweeping artifacts

### ✅ Working BYPASS
- Properly bypasses all processing
- Audio passes through unprocessed when engaged

## Signal Chain
```
Input → Denoiser → EQ → Air/Body/Focus/Push/Transients/Analog/Bass Punch → Width → Volume (OUTPUT)
```

## 19 Professional Presets
- **AI Service**: Suno, Udio, Tunee
- **Genre**: Pop/Modern, EDM/Electronic, Hip-Hop/Trap, Rock/Alternative, Acoustic/Folk, Classical/Orchestral
- **Problem-Solving**: De-Harsh, De-Muddy, De-Thin, Vocal Clarity, Bass Restoration, Open Up Highs
- **Intensity**: Light Touch, Moderate Polish, Full Mastering

## Features Retained
- ✅ Real-time audio monitoring
- ✅ Play/Pause/Stop controls
- ✅ A/B comparison
- ✅ Oversampling (2x, 4x, 8x)
- ✅ Undo/Redo (50 levels)
- ✅ Spectrum analyzer
- ✅ Processing modes (Spectral, Time-Domain, Hybrid)
- ✅ Dithering options (TPDF, POWr1/2/3)
- ✅ Help documentation
- ✅ Windows installer config
- ✅ Orange/copper hardware GUI style

## Removed (Not Working)
- ❌ Hiss removal feature
- ❌ Artifact removal feature
- ❌ VU meter

## Quick Start

1. **Load Audio**: Click "Load Audio" to open a file
2. **Play**: Click "Play" to start real-time monitoring
3. **Adjust**: Turn knobs and see/hear changes in real-time
4. **Denoiser**: Increase sensitivity, watch orbit buttons glow
5. **Export**: Click "Export" to save processed audio

## Requirements

- Python 3.10+
- PyQt5
- NumPy, SciPy
- soundfile
- sounddevice (for real-time playback)

## Installation

```bash
pip install -r requirements.txt
python run_app.py
```

## Build Windows Executable

```bash
python installer/build_installer.py
```

---

**Denoise The Future Inc.** | AI Music Doctor v4.0.0 | Professional Mastering for AI-Generated Music

</file>

</uploaded_files>
