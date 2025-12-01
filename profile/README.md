# Beat Boxing - Interactive Mixed-Reality Boxing Game 🥊

**Beat Boxing** is an immersive rhythm game that blends physical exercise with digital gaming. Inspired by the mechanics of *Beat Saber*, players must punch real-world targets projected onto a physical punching bag to the beat of the music.

## 🎯 The Core Concept
Unlike Virtual Reality (VR) games where users punch thin air, **Beat Boxing** provides real **haptic feedback** because the player is striking a physical object. The projection mapping ensures the digital game adapts to the physical reality of the gym equipment, creating a tangible mixed-reality fitness experience.

## 🎮 How It Works

The system creates a seamless feedback loop between the physical and digital worlds:

### 1. The Projection (Visuals)
Projectors map dynamic visual targets, such as glowing orbs or directional arrows, directly onto the curved surface of a real heavy bag.

### 2. The Action (Physical Input)
The player wears distinctively colored boxing gloves. To score points, they must physically punch the specific targets on the bag.

### 3. The Tracking (Computer Vision)
A specialized stereoscopic camera rig is mounted above the player, looking down at the bag. Using two cameras to mimic human depth perception, the system tracks the exact 3D coordinates (X, Y, Depth) of the player's glove in real-time.

### 4. The Hit Detection (Game Logic)
The game engine continuously compares the **projected** location of the digital target with the **tracked** physical location of the glove.