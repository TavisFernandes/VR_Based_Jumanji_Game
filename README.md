# VaultQuest

**A 4-Scene Jumanji-Style Adventure Game**

VaultQuest is an immersive 3D adventure experience built in Unity, where players step into the shoes of Arjun, a 14-year-old boy who discovers a mysterious ancient box hidden among the Egyptian sand dunes. Inspired by the classic *Jumanji* board game mechanics, VaultQuest pulls players into dangerous parallel worlds where stealth, quick thinking, and resourcefulness are the only keys to survival.

---

## 🎮 Game Overview

### The Story
While exploring the ruins of a forgotten house, Arjun finds an ancient wooden box. Inside lie a set of glowing dice. Each roll of the dice triggers a magical "scene jump," transporting Arjun to a perilous new reality. To return home, Arjun must find the single coordinate coin hidden in each world.

### 🗺️ Parallel Worlds
1. **Egypt Dunes Hub**: The central starting point and sanctuary where all paths begin.
2. **Zombie City**: Danger World 1. Navigate a post-apocalyptic urban grid patrolled by the undead.
3. **Dinosaur Jungle**: Danger World 2. A lush prehistoric forest where carnivores track your every move by sound and footprints.
4. **Medieval Kingdom**: Danger World 3. Sneak through a sprawling stone castle town and its dark dungeons to find the final coin.

### 🕹️ Core Mechanics
- **Jumanji Core Loop**: Dice Roll -> Scene Jump -> Collect Coin -> Return to Hub.
- **Stealth-Survival**: No combat! Arjun must crouch, sprint, and hide to avoid enemies.
- **Eagle Sense**: Use Arjun's special ability to highlight coins and distant threats.
- **Penalties**: Getting caught doesn't mean Game Over—it triggers a "forced chain," sending you deeper into the next dangerous world without your coin.

---

## 🛠️ Technical Stack
- **Engine**: Unity 2022 LTS / Unity 6
- **Graphics**: Universal Render Pipeline (URP) with high-fidelity post-processing.
- **AI**: NavMesh-based state machines for complex enemy behavior (Patrol/Alert/Chase).
- **Architecture**: Singleton pattern for global state management and persistent data.

---

## 📥 Getting Started (Installation)

This repository uses **Git LFS** to store high-resolution assets and project archives. Due to GitHub's file size limits, the project source is stored as a split archive. 

### 1. Clone the Repository
```bash
git clone https://github.com/TavisFernandes/VR_Based_Jumanji_Game.git
cd VR_Based_Jumanji_Game
```

### 2. Reconstruct the Project Source
To extract the full `unity-project.zip`, run the appropriate command for your operating system:

#### **Windows (Command Prompt / PowerShell)**
```cmd
copy /b unity-project.zip.part* unity-project.zip
```

#### **Linux / macOS**
```bash
cat unity-project.zip.part* > unity-project.zip
```

### 3. Open in Unity
1. Unzip the reconstructed `unity-project.zip`.
2. Open the resulting folder in **Unity Hub**.
3. Ensure you are using **Unity 2022.3 LTS** or later.

---

## 🥽 VR Setup (Meta Quest 3)

To run VaultQuest on a VR headset like the Meta Quest 3, you need to install the following three setup files found within the `setup.zip` archive in the root directory:

1.  **VaultQuest Setup (`Setup.exe`)**: The main installer for the game build.
2.  **SideQuest (`SideQuest-Setup-0.10.42-x64-win.exe`)**: Required for managing your Quest headset and sideloading.
3.  **Meta XR Simulator (`meta_xr_simulator.msi`)**: Needed to simulate the VR environment for a seamless Meta Quest Link connection.

**Basic Steps:**
- Reconstruct and unzip `setup.zip` (if using the archived version).
- Install all three components listed above.
- Connect your Quest 3 via **Meta Quest Link** or **Air Link** and launch the application.

---

## 📄 Documentation
Refer to `GamePlan.pdf` in the root directory for the complete game design bible, including:
- Detailed scene breakdowns.
- Enemy AI behavior specifications.
- C# implementation logic.
- Visual and audio asset guides.

---
Developed by **Tavis Fernandes**, **Atharv Amit Deshpande**, **Aayesha Patel**, **Advika Wankhede** | 2026
