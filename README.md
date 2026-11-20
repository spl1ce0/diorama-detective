# Diorama Detective: AR Spot the Difference

Interactive 3D AR "spot the difference" puzzle built with **Unity 6** and **Vuforia Engine**. Scan the image target to project two side-by-side miniature dioramas on a table, walk around to inspect them from different angles, and tap the 5 visual differences to solve the puzzle.

**Authors:** Margarida Caetano, Marcelo Moreira

## Requirements
- **Unity:** `6000.3.24f1` (with iOS / Android Build Support)
- **Vuforia Engine:** `11.4.4`

## Setup
1. Clone this repository.
2. Download the **Vuforia Engine 11.4.4** Unity package (`.tgz`) from the [Vuforia Developer Portal](https://developer.vuforia.com/downloads/sdk) and place `com.ptc.vuforia.engine-11.4.4.tgz` inside the `Packages/` folder *(excluded from Git due to GitHub's 100 MB file size limit)*.
3. Open the project in Unity Hub (`6000.3.24f1`).
4. Open `Assets/Resources/VuforiaConfiguration.asset` and ensure a valid Vuforia Basic License Key is configured.
5. Open `Assets/Scenes/AR_DioramaDetective.unity` to test in Editor or build for iOS/Android.
