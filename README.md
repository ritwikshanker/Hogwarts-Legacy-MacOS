<p align="center">
  <img src="https://img.shields.io/badge/Hogwarts%20Legacy-macOS%20Guide-6A5ACD?style=for-the-badge&logo=apple&logoColor=white" alt="Banner" />
</p>

<h1 align="center">🏰 Hogwarts Legacy on macOS (Heroic Games Launcher Guide)</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-macOS-black?style=flat-square&logo=apple" />
  <img src="https://img.shields.io/badge/Apple%20Silicon-Supported-green?style=flat-square&logo=apple" />
  <img src="https://img.shields.io/badge/Game-Hogwarts%20Legacy-7F00FF?style=flat-square" />
  <img src="https://img.shields.io/badge/Launcher-Heroic-4B9CD3?style=flat-square&logo=epicgames" />

</p>

<p align=\"center\">
  Unofficial guide to running <strong>Hogwarts Legacy</strong> at 60 FPS on macOS using Heroic Games Launcher.
</p>

---
# Play Hogwarts Legacy on macOS (Unofficial Guide)

This guide walks you through running **Hogwarts Legacy** on a Mac using **Heroic Games Launcher**.

> **Note:** Performance varies by Mac model. Apple Silicon machines with plenty of RAM work best.

---

## 🚀 Steps

### **1. Install Heroic Games Launcher**

Download and install Heroic from the official website:

* [https://heroicgameslauncher.com/](https://heroicgameslauncher.com/)

### **2. Log in to Epic Games**

Open Heroic and sign in with your **Epic Games** account.

### **3. Download Hogwarts Legacy**

Search for **Hogwarts Legacy** in your library and start the download.

* **Download size:** ~88GB

### **4. Open Game Settings**

In Heroic, go to your Library → select **Hogwarts Legacy** → **Settings**.

### **5. Switch to Wine Settings**

Scroll to the **Wine** section.

### **6. Open WineTricks**

Click **WineTricks** to view missing dependencies.

### **7. Fix Missing Components**

Heroic will display errors/missing components in the Wine log/console.

* Install everything marked as missing.

### **8. Install vcrun2022**

Inside WineTricks:

* Search for **`vcrun2022`**
* Install it

### **9. Launch the Game**

Return to Heroic and click **Play**. The game should launch normally.

---

## 📸 Screenshots

Paste your three images here once uploaded:

**Gameplay (60 FPS Ultra) — Image 1**
![HL Gameplay 1](images/gameplay.png)

**Gameplay (60 FPS Ultra) — Image 2**
![HL Gameplay 2](images/title_screen.png)

**Ultra Settings Screenshot**
![HL Settings](images/settings.png)

---

## 🔧 Tips

* If performance stutters, try lowering graphics settings.
* Make sure Heroic is using a recent Wine/Proton version.
* Keep macOS updated.

---

## 🐞 Known Issues & Fixes

### **Shader Compilation Doesn’t Start on First Launch**

* On your first run, shaders may **not** build.
* Simply close the game and **launch it again**.
* On the second launch, shader compilation should start normally.

### **AMD Driver Outdated Warning**

* You may see a popup saying your **AMD GPU driver is outdated**.
* This is expected when running via Wine.
* **Safe to ignore** — it has no impact on gameplay.

---

## ❗ Disclaimer

This is an unofficial workaround. Hogwarts Legacy does **not** have native macOS support, so issues may happen.

---

Enjoy your adventure! 🪄✨
