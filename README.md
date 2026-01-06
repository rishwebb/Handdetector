# Handdetector
Link: https://rishwebb.github.io/Handdetector/

# Neural Hand Tracker / Gesture Interface

A real-time hand tracking and gesture-controlled interaction system built using computer vision and web-based 3D rendering.

This project uses live webcam input to detect human hand landmarks and translates gestures into interactive actions such as building, rotating, grabbing, or triggering visual states in a virtual environment.

---

## Features

- Real-time hand tracking using webcam input
- Accurate detection of hand landmarks and gestures
- Gesture-based interactions (pinch, fist, open palm, dual-hand actions)
- Smooth landmark stabilization for reduced jitter
- Visual HUD and feedback overlays
- Designed for experimental UI, XR concepts, and human-computer interaction research

---

## Technology Stack

- MediaPipe Hands (for hand landmark detection)
- JavaScript (core logic)
- HTML5 Canvas (gesture visualization & HUD)
- Three.js (3D rendering and interaction)
- WebGL (GPU-accelerated graphics)

---

## How It Works

1. The webcam captures live video frames.
2. MediaPipe Hands detects 21 landmarks per hand in real time.
3. Landmark distances and relative positions are analyzed to identify gestures.
4. Gestures are mapped to system actions (build, erase, rotate, grab).
5. Visual feedback is rendered instantly to the screen.

This is **not** a simulation. All interactions are driven by real hand movement.

---

## Setup Instructions

1. Clone or download the project files.
2. Open the main HTML file in a modern browser (Chrome recommended).
3. Allow camera access when prompted.
4. Ensure good lighting for best hand detection accuracy.

No backend or server is required.

---

## Usage Notes

- Works best with clear lighting and a visible hand.
- Designed for desktop or laptop environments with a webcam.
- Mobile browser support may be limited.

---

## License

**MIT License**

Permission is hereby granted, free of charge, to any person obtaining a copy  
of this software and associated documentation files (the "Software"), to deal  
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all  
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE  
SOFTWARE.

---

## Copyright

© 2026 Rishav Biswas  
All rights reserved.

Original implementation, gesture logic, interaction design, and system architecture are authored by Rishav Biswas.

If you use this project or build upon it, attribution is appreciated.

---

## Disclaimer

This project is intended for educational, experimental, and research purposes.  
It is not designed for medical, safety-critical, or surveillance applications.

---

## Contact

For collaboration, feedback, or questions, reach out via your preferred platform.


