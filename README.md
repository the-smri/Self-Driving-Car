<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d5bac278-9b78-442e-9c36-8b2a9a74ca1b" />


# 🚗 Autonomous Car Path Following Simulation

This project simulates a **self-driving Tesla car** navigating a predefined track using **color-based detection and decision logic** — all in a simple 2D environment.
It’s not just a game — it’s an **educational demo** of real-world autonomous vehicle concepts!

---

## 🎮 Overview

The simulation:

* 🛣️ Creates a **track** with a **white path** on a **dark background**
* 🚘 Places a **Tesla car sprite** that **follows the path automatically**
* 🎨 Uses **color detection (RGB 255,255,255)** to detect and follow the white path
* ⚡ Includes **collision detection points** (up, down, right) to sense track boundaries
* 🔄 Executes **90° turns** automatically when detecting intersections
* 🟢 Displays a **green dot sensor**, representing the car’s “camera” or vision system

---

## 🧠 What Makes It Special?

This isn’t just a toy simulation — it’s inspired by **real autonomous vehicle engineering** concepts.

### ✅ Real-World Principles Simulated:

* **Sensor-Based Navigation** — mimics how real self-driving cars use cameras or LiDAR
* **Path Following Algorithms** — continuous feedback-based motion control
* **Decision Making** — handles intersections logically
* **Collision Avoidance** — prevents the car from leaving the track

### ❌ Game-Like Simplifications:

* Simple **2D environment**
* **Color-based detection** instead of real sensor input
* **Predefined track** with fixed paths

---

## 🎓 Educational Value

This project can be used for:

* 🧩 **Teaching** basic concepts of autonomous navigation
* 💡 **Prototyping** path-following and sensor algorithms
* 🤖 **Understanding** how sensors detect and react to environmental data
* 🌳 **Learning** decision-tree logic in robotics

---

## 🛠️ Technologies Used

* **Python** (e.g., with Pygame or OpenCV — depending on implementation)
* **2D Graphics & Sprite Handling**
* **Basic Computer Vision (Color Thresholding)**

---

## 🚀 How It Works

1. The track image provides a **white path** for the car to follow.
2. The car’s virtual “camera” (green dot) continuously reads color values ahead.
3. When the camera detects white (`RGB(255,255,255)`), it moves forward.
4. When a sensor detects a dark area or an intersection, the car makes a **90° turn**.
5. This feedback loop allows the car to autonomously navigate the entire track.

---

## 📘 Future Enhancements

* Add **dynamic obstacles** and real-time avoidance
* Use **PID control** for smoother path following
* Implement **neural networks** for adaptive navigation
* Introduce **multiple cars** to simulate traffic

---

## 📄 License

This project is released for **educational and research purposes**.
You are free to **use, modify, and share** it with proper credit.

