
# The Sanctuary 

[**🔴 PLAY LIVE DEMO**](https://thedarkiin.github.io/portfolio/)

An immersive 3D web experience featuring a procedural ocean, dynamic day/night cycles, and an interactive world. 

![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)

## 📖 The Origin Story

When i was learning java, i came across an exercice about creating a particle class its velocity and acceleration, and i wanted so bad to simulate it, i asked dear Chatgpt how can i do so? The answer :  **Three.js**
I was fascinated by the idea, then i forgot lol ( i had to study for the exam so bad).

I remembered and the spark finally came when I scrolled past a LinkedIn post about a **"Cozy Homes" Three.js competition**. It was inspiring and the results were so cool . I decided its time to build something.

Coming from a little boy who once loved **RPG games**, I understood the logic (Object-Oriented Programming, game loops, physics), but the syntax of WebGL felt like a barrier.

### The Experiment

I set a challenge for myself: **Could I vibe code a complete 3D engine ?**

This project is **100% Prompt Engineered**. Using my humble knowledge of OOP and game logic, i directed Gemini PRO 3 to build specific modules (Ocean, Sky, Physics, NPC AI). I guided the architecture, and refined the "feel," while Gemini handled the heavy lifting and rendering code.

## 🎮 Features

* **The Leviathan:** A massive, procedurally generated whale that breaches the surface. ( forgive the cheap geometry, i tried my best refining but it requires manual expertise :..) 
* **Dynamic Cycle:** A full Day/Night system with Rayleigh scattering sky gradients and fog.
* **Physics & Interaction:**
    * Sailable boat with momentum and drag.
    * Working cannon system with particle explosions.
    * Floating supply crates that react to the water.
* **The Keeper:** A floating NPC with a dialogue system.
* **Audio Engine:** Procedural pink-noise ocean sounds (no external mp3 files).


## 🛠️ How to Build Your Own (The Workflow)

If you want to build something similar, you don't need to memorize the entire Three.js documentation. You need **Logic** and **Iteration**.

1.  **Think in Modules (OOP):** Don't ask for "a game." Ask for classes. "Create a `Boat` class," "Create an `AudioEngine` class."
2.  **Start Simple:** I started with just a dragon not even a real one it was a triangle inside a ball floating haha.
3.  **Refine visually:** Use terms like "Low luminosity","Rayleigh scattering","Gradient colors" to get better visuals.
4.  **Iterate:** When a bug happens, paste the console error. When the physics feels wrong, explain *how* it feels wrong (e.g., "The boat slides too much, add friction").


## 💻 Local Installation

To run this locally on your machine:

1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/Thedarkiin/portfolio.git](https://github.com/Thedarkiin/portfolio.git)
    ```
2.  **Navigate to the folder:**
    ```bash
    cd portfolio
    ```
3.  **Run a local server (Required for textures/modules):**
    If you have Node.js installed:
    ```bash
    npx serve .
    ```
    *Or use the "Live Server" extension in VS Code.*



## 📬 Contact

* **Student** Yassin Asermouh you can type it on **linkedin** 
* **Status:** Student Engineer @ INSEA specializing in Data Science