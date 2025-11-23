# 🌲 TreeBoy: Alon Bar Koter Edition

**TreeBoy** is a retro-styled, browser-based puzzle game where the goal is to pack complex polygon shapes (Christmas trees) into the smallest possible area.

This project explores the mathematical beauty of **Shape Packing**, wrapped in a nostalgic GameBoy-inspired interface using pure HTML, CSS, and JavaScript.

---

## 🧩 What is Shape Packing?

The **Packing Problem** is a class of optimization problems in mathematics that involves attempting to pack objects together into containers. The goal is to either minimize the size of the container needed for a specific set of objects (as done in this game) or maximize the number of objects that fit into a fixed container.

### Why is this important?
While it looks like a game, shape packing is a critical problem in computer science and real-world industries:

1.  **Logistics & Shipping:** Determining the most efficient way to pack boxes into trucks or shipping containers to save fuel and space.
2.  **Manufacturing:** In industries like metalworking, woodworking, or fashion, irregular shapes must be cut from raw sheets of material. Optimal packing (Nesting) reduces waste and saves millions of dollars.
3.  **Technology:** It is used in texture atlas generation for 3D graphics and even in designing the layout of transistors on silicon chips.

---

## 🏆 The Inspiration: Kaggle Santa 2025

This game was directly inspired by the **Kaggle Santa 2025 Optimization Competition**. Every year, Kaggle hosts a holiday-themed contest that challenges data scientists to solve complex optimization problems.

The 2025 challenge focused on minimizing the area of bounding boxes for various polygons—essentially, the exact core mechanic of *TreeBoy*.

👉 **[Check out the Kaggle Competition here](https://www.kaggle.com/competitions/santa-2025/overview)**

---

## 🎮 Game Features

*   **Retro Aesthetic:** A fully CSS-styled interface mimicking a handheld console, complete with a dot-matrix style LCD screen.
*   **SVG Graphics:** Trees are rendered as scalable vector graphics for crisp visuals at any zoom level.
*   **10 Progressive Levels:** Each level adds another tree to the cluster. The difficulty scales non-linearly.
*   **Precision Controls:**
    *   **D-Pad:** Nudge the active tree for pixel-perfect placement.
    *   **Analog Dial:** Rotate trees to find the perfect locking angle.
*   **Strict Goals:** To advance, you must beat specific area targets calculated based on world-record optimal packing densities.
*   **Analytics Integration:** The game anonymously tracks user behavior (platform, input method, time per level) via a serverless Google Forms integration to analyze player difficulty curves.

---

## 🕹️ How to Play

1.  **Objective:** Arrange all the trees on the screen so that they take up the smallest possible square area.
2.  **Controls:**
    *   Click/Tap a tree to select it.
    *   Use the **Arrow Keys** (D-Pad) to nudge the position.
    *   Use the **Rotary Dial** to rotate the tree.
    *   **Green Button:** Add the next tree (only works if you beat the current level's goal).
    *   **Red Button:** Reset the current level.
3.  **Winning:** Keep the `AREA` score below the `GOAL` threshold. When you succeed, the screen will flash, and you can proceed to the next level.

---

## 🎵 Credits

*   **Concept & Development:** Alon Bar Koter
*   **Music:** "Return to the 8-bit past" - An upbeat chiptune track perfect for puzzle solving.
    *   Source: [Pixabay - Return to the 8-bit past](https://pixabay.com/music/video-games-return-to-the-8-bit-past-301282/)

---

## 🚀 Installation

1.  Clone the repository.
2.  Ensure `index.html` and `theme.mp3` are in the same folder.
3.  Open `index.html` in any modern web browser.
4.  Click anywhere on the page to start the audio engine.
