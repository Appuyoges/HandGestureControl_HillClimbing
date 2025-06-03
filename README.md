# HandGestureControl_HillClimbing
<h1 align="center">🖐️ Hand Gesture Keyboard Controller</h1>
<p align="center">
  <b>Control your keyboard with hand gestures using AI-powered computer vision!</b><br/>
  🚗 Play games • 🎮 Control apps • ⚡ Experience hands-free interaction
</p>

<p align="center">
  <img src="https://media.giphy.com/media/26tn33aiTi1jkl6H6/giphy.gif" width="60%" alt="Demo GIF">
</p>

---

## 🚀 Why This Project?

Tired of traditional controls? Here's a futuristic twist — use your **bare hands** as a **virtual controller** to trigger keyboard actions using real-time **hand pose detection**. It's fast, smooth, and surprisingly accurate.

✨ **No sensors. No gloves. Just your webcam and your fingers.**

---

## ⚙️ Tech Stack

| Tool        | Role                            |
|-------------|---------------------------------|
| `OpenCV`    | Capture video from webcam       |
| `MediaPipe` | Detect hand landmarks (21 points) |
| `Pynput`    | Simulate keyboard key presses   |

---

## ✋ Gesture Controls

| Hand Gesture | Meaning         | Action Triggered      |
|--------------|-----------------|------------------------|
| ✊ Fist       | All fingers closed | `← Brake (Left Key)`   |
| 🖐️ Open Palm  | All fingers open   | `→ Gas (Right Key)`    |
| ❌ No hand    | Outside frame     | Release all keys       |

---

## 🔧 Installation

Make sure you have **Python 3.7+** installed.

### 🔹 Install via `pip`:

```bash
pip install opencv-python mediapipe pynput
