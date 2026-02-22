# 🌌 Interactive 3D Gesture-Controlled Particle System

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-00B2FF?style=for-the-badge&logo=google&logoColor=white)

An immersive, real-time 3D web experience where art meets artificial intelligence. This project uses computer vision to track hand movements via a webcam, allowing users to physically interact with a cloud of 15,000+ morphing particles and spatial audio—without touching a mouse or keyboard.

🔗 **[Click Here for Live Demo]([YOUR-LIVE-LINK-HERE])** *(Note: Please allow camera access and interact with the screen to enable the audio experience).*

---

## ✨ Key Features

* ✋ **AI-Powered Hand Tracking:** Utilizes Google's MediaPipe for precise, real-time detection of 21 3D hand landmarks.
* 🎨 **WebGL Particle Engine:** Powered by Three.js to render and smoothly animate 15,000+ independent particles at 60FPS.
* 🧬 **Mathematical Morphing (Topologies):** Custom parametric equations transition the particle cloud through complex shapes seamlessly:
    * *Sphere $\rightarrow$ DNA Helix $\rightarrow$ 2D S-Curve $\rightarrow$ 3D Heart $\rightarrow$ Saturn with Rings.*
* 🔊 **Spatial Audio Control:** The distance between your hands dynamically maps to the master volume (Euclidean distance calculation).
* 💥 **Interactive Physics:** A pinch gesture triggers a custom-generated synthesizer "blast" sound and visually scatters the particles before reforming them.

---

## 🕹️ How to Use (Gesture Controls)

Once the application loads and your camera is active, step back slightly so your hands are visible:

1.  **Single Hand Tracking:** Move one hand around the frame to magically rotate the 3D particle object in real-time.
2.  **The "Pinch" (Change Shape):** Bring your thumb and index finger together (pinch) to trigger a blast effect and morph the particles into the next shape.
3.  **Two-Hand Zoom & Volume:** Bring both hands into the frame. 
    * *Move them apart:* Expands the particle system and increases the music volume to 100%.
    * *Bring them closer:* Shrinks the particle system and lowers the volume.

---

## 🛠️ Tech Stack

* **Frontend:** Vanilla JavaScript, HTML5, CSS3
* **3D Graphics:** Three.js (WebGL)
* **Computer Vision:** MediaPipe Hands API
* **Audio Synthesis:** Web Audio API

---

## 💻 Local Installation & Setup

If you want to run this project locally on your machine:

1. Clone this repository:
   ```bash
   git clone [https://github.com/YourUsername/YourRepositoryName.git](https://github.com/YourUsername/YourRepositoryName.git)
   ```

2.Navigate to the project directory:   
  ```bash
  cd YourRepositoryName
  ```

3. Important: Add an audio file named background.mp3 to the root directory

4. Run a local server to bypass browser CORS restrictions for webcam access. If you have Python installed, run:
   ```bash
   python -m http.server 8000
   ```

5. Open your browser and go to http://localhost:8000.

👨‍💻 Author
Rajeev Kumar

Software Engineer | Tech Enthusiast