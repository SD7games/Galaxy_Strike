# 🌌 Galaxy Strike  
A cinematic gameplay prototype made in Unity, built around Timeline-driven sequences, scripted motion tracks and animated encounters.  
The project focuses on cutscene-style gameplay, character interactions, camera work and environmental presentation.

---

## 🎮 Gameplay Overview  
Galaxy Strike uses **Unity Timeline** as the core gameplay system.  
All player movement, enemy flight paths, encounters and transitions are driven by Timeline tracks, signals and recorded animation curves.

The project demonstrates:

- **Scripted player motion**
- **Scripted enemy flight paths** created through custom Timeline animation tracks  
- **Dialogue moments with animated portraits**
- **Cinematic camera transitions**
- **Cutscene-based event flow**
- **Environmental presentation**

---

## ⭐ Key Features  

### 🎬 Timeline as the Core System  
- Recorded movement tracks for player and enemies  
- Multiple Timelines controlling gameplay sequences  
- Custom **Timeline Signals** triggering:  
  - UI messages  
  - sound effects  
  - camera cuts  
  - particle effects  
- Smooth transitions between narrative and action segments  

### 🚀 Scripted Enemy Encounters  
- Enemies do **not** use AI  
- All movement is **hand-crafted and animated** through Timeline  
- Flight paths built from animation curves to simulate cinematic attacks  
- Coordinated enemy entrances, passes and exits  

### 🎥 Cinematic Camera Work  
- Multiple virtual cameras synced with Timeline  
- Cutscene-style switching  
- Tracking shots, zooms and dramatic angles  
- Character portraits animated during dialogue events  

### 🌌 Environment & Visuals  
- Custom **Terrain** (PC-only, not WebGL compatible)  
- Trees, fog, atmosphere lighting  
- VFX: explosions, thrusters, sparks  
- SFX: engine, impacts, UI audio  
- Post-processing: bloom, color grading, depth-of-field  

### 🖥 UI & Presentation  
- Simple UI for early prototype  
- Dialogue portraits animated through Timeline  
- Signal-triggered UI prompts and overlays  

---

## 🧠 Tech & Architecture  
- Unity  
- C#  
- **Unity Timeline** (core system)  
- Timeline Signals  
- Cinemachine  
- Scripted motion tracks  
- Custom VFX/SFX  
- Terrain tools  
- Basic UI  
- Post-processing stack  

---

## 📂 Project Structure
```
/Assets
    /Animations
    /Audio
    /Cameras
    /Prefabs
    /Scenes
    /Scripts
        /Timeline
        /Player
        /Enemies
        /UI
    /Terrain
    /Materials
    /VFX
```

---

📸 Screenshots
🌌 Intro Flight Through the Canyon
<p align="center"> <img src="Start Level.png" width="640"/> </p>
🔧 Loading Screen
<p align="center"> <img src="Loading Scene.png" width="640"/> </p>
🚀 First Encounter With Enemy Fighters
<p align="center"> <img src="First Enemies.png" width="640"/> </p>
🛰 AI Companion Dialogue (Animated Portrait)
<p align="center"> <img src="AI Helper.png" width="640"/> </p>
🏆 Final Scene — Mission Complete
<p align="center"> <img src="Game Completed.png" width="640"/> </p>

---

## 👨‍💻 Developer  
**Oleksandr Tokarev** — Unity & C# Game Developer based in Finland.  
A cinematic prototype created to practice Timeline-driven gameplay, scripted movement tracks, cameras and environmental presentation.


