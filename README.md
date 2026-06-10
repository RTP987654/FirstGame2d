# Knight's Journey

> [!WARNING]
> **Learning Project Disclaimer**
> This is a learning project based on a tutorial by another creator. The project is created solely for educational and self-learning purposes.
> If you want to learn, you can watch the original YouTube tutorial:
> * **Title:** [How to make a Video Game - Godot Beginner Tutorial](https://www.youtube.com/watch?v=LOhfqjmasi0&t=4499s)
>
> This reference is not a promotion. If you are doing the same tutorial, you can use the resources in this repository or access the source creator's original project links in their video description.

> [!NOTE]
> **Project Specifications**
> - **Game Engine:** Godot Engine
> - **Version:** `Godot_v4.6.3-stable_win64`

---

## Table of Contents
1. [Introduction: About this Project](#1-introduction-about-this-project)
2. [Things That I Did](#2-things-that-i-did)
3. [Problems Faced & Solutions](#3-problems-faced--solutions)
4. [Differences from the Source Tutorial](#4-differences-from-the-source-tutorial)
5. [Extra Things](#5-extra-things)
6. [How to Play & Controls](#6-how-to-play--controls)

---

## 1. Introduction: About this Project
**Knight's Journey** is a classic 2D pixel-art game. In this game, the player controls a brave knight who explores a vibrant world while collecting coins. 
- **Characters:** The game features a single playable character—the Knight.
- **Key Features:**
  - Background music playing in a continuous loop.
  - Interactive coin collection system.
  - Patrolling green and purple slimes that guard specific areas.

---

## 2. Things That I Did
By following the tutorial step-by-step, I successfully implemented almost all the activities and mechanics shown in the video. The creator's detailed explanations and attention to small details made it very smooth to follow along and recreate the game structure, nodes, and scripts.

I created nodes, scenes, game background and playing space, added coins, enemy, some note for reading, implemented codes, added more platforms, used sound and some minor activities.

---

## 3. Problems Faced & Solutions

### 3.1. Tilemap (22:50)
So the creator is using tilemap but the current version shows error in it. For now you can continue doing the same as the creator is doing as the error won't affect the work. But in later time you have to change to `TileMapLayer`.

![Tilemap Deprecation](tilemap_deprecated.png)

This is for future problem currently there is no problem following the creator's way.

---

## 4. Differences from the Source Tutorial
Currently, this project matches the tutorial video's assets, logic, and level design. No custom features or structural differences have been added compared to the source tutorial.

---

## 5. Extra Things
### 5.1. Screen not loading after re-open
If your screen doesnot load properly after re-opening godot.
![Image](screen_5.1.1.png)
Then, In top left click on `Scene` then `Reload saved scene`.
![Image](screen_5.1.2.png)
After that you scene will load properly.
![Image](screen_5.1.3.png)

---

## 6. How to Play & Controls
You can move and jump using the following key bindings:

| Action | Primary Keys | Alternative Keys |
| :--- | :--- | :--- |
| **Move Left** | `A` / `Left-Arrow` | Left Arrow |
| **Move Right** | `D` / `Right-Arrow` | Right Arrow |
| **Jump** | `W` / `Space` / `Up-Arrow` | Up Arrow |
