**AI Music Doctor**






<img width="1408" height="768" alt="AIMD LOGO Web" src="https://github.com/user-attachments/assets/17cfb309-deb1-48bf-880b-06c5217b3aba" />








**Overview**

AI Music Doctor is a professional-grade standalone desktop audio processing application designed to clean up and enhance AI-generated music tracks. It uses advanced psychoacoustic algorithms inspired by Fletcher-Munson curves and the Bark Scale to dynamically reduce problematic frequencies such as boomy, boxy, muddy, honky, harsh, and sizzle sounds, making your audio smoother and more pleasant to listen to.

Examples:

**Udio Original RAW**
[Udio Original RAW.mp3](https://github.com/user-attachments/files/26454461/Udio.Original.RAW.mp3)

**Processed**
[Processed.mp3](https://github.com/user-attachments/files/26454465/Processed.mp3)

**Key Features**

Psychoacoustic Denoiser: A one-knob solution with six frequency bands (Boom, Box, Mudd, Honk, Harsh, Sizzle) that dynamically minimizes problematic frequencies with zero latency.

Mastering Knobs: Nine gentle, professional mastering controls with ±3dB max adjustments for Air, Body, Focus, Push (saturation/compression), Width (M/S stereo), Volume, Transients, Analog warmth, and Bass Punch.

Graphical EQ: A precise 9-band EQ with ±2.4dB max gain/cut, designed for surgical, artifact-free adjustments.

Real-Time Audio Monitoring: Hear all changes instantly as you adjust knobs or switch presets.

A/B Comparison: Toggle between original and processed audio during playback.

Oversampling: Options for 2x, 4x, and 8x oversampling to reduce aliasing and improve audio quality.

Undo/Redo: Robust state management with up to 50 levels of undo/redo.

Spectrum Analyzer: LED-style 24-band spectrum visualization with smooth, natural movement.

Stable and Efficient: Lock-free audio processing callback, optimized vectorized DSP algorithms, and a 2048-sample buffer for smooth playback without lag or freezing.

19 Expert-Designed Presets: Tailored for AI music services (Suno, Udio, Tunee), genres, and common audio problems.


<img width="1313" height="962" alt="GUI AIMD" src="https://github.com/user-attachments/assets/ec5befe3-f177-4053-b2fe-2c91e962f2cd" />


**Installation Instructions**

Prerequisites

Python 3.12 or later (Note: The app was tested and updated for Python 3.12+ compatibility)
pip package manager

Steps

Download the Project Clone or download the AI Music Doctor project from GitHub.
Install Dependencies Open a terminal or command prompt in the project directory and run:

pip install -r requirements.txt

This installs all necessary Python packages, including numpy, scipy, sounddevice, PyQt5, and others.
Run the Application Launch the app by running:

run_app.bat

This opens the GUI where you can load your AI-generated audio files, apply processing, and listen in real-time.
Build Windows Installer (Optional) To create a standalone Windows executable installer:
Run the build script:

python installer/build_installer.py

Use Inno Setup (on Windows) to compile the installer script located at:
installer/ai_music_doctor_installer.iss

After everything is correctly installed you can execute the app by running the .bat file. 
This will generate a professional Windows installer with shortcuts and bundled dependencies.

**Notes**
The app currently requires running via Python. For users unfamiliar with Python, this may be a barrier.
If you know how to create a proper standalone .exe installer that bundles Python and all dependencies seamlessly, please share your expertise! This would make the app more accessible to users who are not comfortable with Python environments. Contact me!

2026
_Denoise The Future™_
