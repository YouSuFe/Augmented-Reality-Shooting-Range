### The Example Use ###
https://drive.google.com/file/d/1QZisUPy6C_VBxjLgBr8rFdCPYdkOliKv/view?usp=sharing

# 📡 AR Shooting Range  
_An augmented reality simulation for response/aim measurement using device camera and world-space targets._

---

## 🧩 Overview & Purpose

AR Shooting Range is **not a game**, but a **simulation / testing tool**.  
It allows you to define a real-world area by selecting three physical points, and then projects virtual shooting targets within that polygon. The user “shoots” those targets (via taps, raycasts, or input), and the system calculates **response time** and **aim accuracy**.

Use cases include:
- Measuring user reaction times  
- Evaluating aiming precision in AR training  
- Simulating shooting/target tasks in AR for research or UX testing  

---

## ✨ Key Features & Highlights

- 🎯 **AR Polygon Targeting**: User defines a real-world polygon (3 points) to confine the target area.  
- 🔍 **Dynamic Target Spawning**: Targets appear within the defined polygon, in various positions.  
- ⏱️ **Response Time Tracking**: Measures how quickly the user hits each target.  
- 🎯 **Accuracy & Hit Metrics**: Records hit vs miss, hit offset (distance from target center).  
- 📱 **Cross-Device AR Support**: Works on AR-capable mobile devices (ARKit / ARCore).  
- 💡 **Modular Design**: Components for AR anchoring, target management, input & UI.  

---

## 🧰 Tech Stack & Dependencies

- **Engine**: Unity 2021/2022/2023 LTS (with AR Foundation)  
- **AR**: AR Foundation / ARKit / ARCore  
- **Core Systems**: C#, Unity Input System, Raycasting  
- **UI**: Unity UI / TextMeshPro  

---
