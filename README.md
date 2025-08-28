ColorSphere — Neon Music Visualizer
<img width="988" height="739" alt="ColorSphere Music Visualizer001" src="https://github.com/user-attachments/assets/f361e410-3ad9-49c4-80f8-b61e8ff56b5c" />
<img width="976" height="728" alt="ColorSphere Music Visualizer002" src="https://github.com/user-attachments/assets/dfcdb922-0eff-4c96-b080-9e6a03f3969b" />

Live Demo:https://meganlovlatte.github.io/colorsphere-music-visualizer/
A vibrant, multi-model music visualizer that transforms audio into explosive spherical art. Upload any audio file and watch as frequency bands create stunning visual patterns with 6 different color modes.

✨ Features

🎵 Real Audio Analysis - Upload MP3, WAV, OGG, M4A files
🌈 6 Neon Color Modes - From citrus explosions to cyber punk aesthetics
⚡ Live Web Audio API - True frequency band analysis (low/mid/high)
🎨 Interactive Controls - Adjust sensitivity, thresholds, and visual complexity
🔥 Vibrant Visuals - Inspired by explosive neon art and psychedelic patterns

🎨 Color Modes
ModeDescriptionBest ForNeon Citrus ExplosionElectric lime greens with hot magenta burstsElectronic, EDMElectric BurstHot pink and electric blue radiating patternsRock, PopPsychedelic Multi-MixChaotic multi-layered oscillating colorsExperimental, JazzCyber PunkClassic neon magenta/cyan aestheticsSynthwave, TechnoPlasma StormAurora-like flowing organic patternsAmbient, ChillRainbow FractalMathematical fractal patternsClassical, Orchestral
🚀 Quick Start

Visit the live demo (link above)
Upload an audio file or use the "Take Five" jazz preset
Choose a color mode that matches your music style
Adjust sensitivity to boost quiet tracks
Click "Analyze & Render" and enjoy the show!

🛠️ How It Works
The visualizer uses the Web Audio API to:

Decode uploaded audio files in real-time
Perform FFT analysis to extract frequency data
Split audio into three frequency bands:

Low (20-250 Hz) → Red channel
Mid (250-2000 Hz) → Green channel
High (2000+ Hz) → Blue channel


Map frequency energies to concentric rings (time slices)
Apply complex color algorithms with multi-layered mixing

🎯 Technical Features

Zero Dependencies - Pure vanilla HTML5/CSS3/JavaScript
Real-time FFT - Custom frequency analysis implementation
Cross-browser Compatible - Works in modern browsers with Web Audio API
Responsive Design - Adapts to different screen sizes
Performance Optimized - Efficient canvas rendering

🔧 Customization
The code is highly customizable! You can:

Add new color modes by extending the getColorForEnergies() function
Modify frequency band ranges in analyzeAudioFrequencies()
Adjust visual effects like jitter and background glow
Create new preset audio patterns

📱 Browser Support

✅ Chrome 66+
✅ Firefox 60+
✅ Safari 14+
✅ Edge 79+

Requires Web Audio API support
🤝 Contributing
Want to add new color modes or features?

Fork this repository
Create a feature branch (git checkout -b amazing-feature)
Commit your changes (git commit -m 'Add amazing feature')
Push to the branch (git push origin amazing-feature)
Open a Pull Request

📄 License
This project is open source and available under the MIT License.
