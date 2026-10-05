To secure a win at SEAD 2026 at New World International School, your project needs a high technical ceiling, clear STEM/educational alignment, and an immediate visual impact during a live pitch.
Here are the 12 highly competitive projects selected from the master library, filtered specifically to impress a panel of school organizers, teachers, and student mentors:

---

# 🔬 Scientific & Simulation Engines

High-level math and physics formulas running in real time score maximum points for academic application.

## 🌌 1. OrbitSim: The Gravity & Keplerian N-Body Simulator

- The Concept: An interactive space physics sandbox where users click to spawn planets, stars, and black holes to observe real-time gravitational interactions and orbital collapses.
- How it Works: It uses a high-performance requestAnimationFrame loop. Each object has variables for mass, position vectors (x, y), and velocity vectors (vx, vy). On every tick, it runs an N-Body Newton’s Law of Universal Gravitation calculation loop ($F = G \frac{m_1 m_2}{r^2}$) to dynamically alter velocities and draw smooth orbital trajectories.
- Why it Wins: It showcases elite-level STEM application, which directly fulfills SEAD's core event objectives. It looks mesmerizing during a live demo when planets dynamically spiral into stars.

## 📐 2. VectorStorm: High-Velocity Orbital Physics Vector Shooter

- The Concept: A 60fps real-time space reflex game where you pilot a ship trapped inside the gravity well of a collapsing star while dodging asteroid debris fields.
- How it Works: Rather than using a rigid grid, objects move freely across the screen using a customized JavaScript Euler Physics Integration Loop. Your ship and the obstacles possess actual velocity vector variables (vx, vy), inertia, and acceleration parameters, utilizing bounding-circle mathematical collision detection formulas.
- Why it Wins: Building smooth, real-time physics and vector mathematics inside a standard browser loop without third-party frameworks instantly establishes you as a top-tier technical developer.

## 🧫 3. BioSphere: Cellular Automata & Evolutionary Species Simulator

- The Concept: An interactive evolutionary sandbox inspired by Conway’s Game of Life where different species of micro-organisms compete for resources, mutate, and adapt over generations.
- How it Works: Built on a strict CSS Grid canvas. Each cell contains a state object representing an organism with traits (e.g., speed, energy, diet). Every game tick, the engine runs a Cellular Automata evaluation loop over the grid matrix, calculating neighbor states to determine reproduction, feeding, or death.
- Why it Wins: It is a phenomenal demonstration of pure algorithmic logic and computational biology. Judges love simulation models because they showcase deep data architecture working smoothly with front-end rendering.

## 🧱 4. Cascade: Fluid-Dynamics Sand & Liquid Simulation Puzzle

- The Concept: A physics-based puzzle arcade game where you clear screens by directing falling streams of sand, water, and acid elements into matching elemental containment bins.
- How it Works: The game board runs on a continuous interval tracking a high-resolution grid matrix. Every frame, a cellular automation loop evaluates every single pixel cell: if a water particle has an empty cell below it, it moves down; if it hits sand, it cascades laterally to the left or right based on simulated fluid weight.
- Why it Wins: Fluid simulation is notoriously difficult to code efficiently. Executing this smoothly using raw array iteration demonstrates highly optimized, low-overhead JavaScript logic.

---

# 🧠 Complex Logic & Strategy Games

These projects feature deep computer science fundamentals (graphs, state machines, and queues) that will stand out to advanced student mentors.

## 🌐 5. NetBreaker: Cyberpunk Network Hacking Puzzler

- The Concept: A terminal-based network breaking game inspired by command-line hacking titles like Hacknet or Uplink.
- How it Works: The player sees a visual graph network of interconnected servers (Nodes). To hack a secure core server, they must navigate the nodes, run pseudo-terminal commands (e.g., scan, bypass, overload), manage their computer's memory/RAM allocation, and disconnect before an "AI System Admin" traces their IP address back.
- Why it Wins: Software engineering evaluators love explicit data structures. This game maps a true Graph Data Structure (Nodes and Edges) onto an interactive terminal string parser block, creating an authentic engineering project.

## 🃏 6. Slay the Code: Roguelike Deckbuilder Card Game

- The Concept: A turn-based strategy card game inspired by indie deckbuilders like Slay the Spire.
- How it Works: The player has a hand of cards (e.g., Strike: Deal 6 dmg, Defend: Gain 5 shield, Poison: Deal 2 dmg per turn). You play cards using your limited energy to defeat an enemy that has its own predictable intent system (the player can see what the enemy will do next turn).
- Why it Wins: It is a pure software architecture project. It showcases a rock-solid Finite State Machine (FSM) managing complex rules (Draw Pile, Hand, Discard Pile, Status Effects) entirely through rigorous object-oriented data structures.

## 🗼 7. ChronoTower: Time-Loop Real-Time Strategy (RTS)

- The Concept: A tower defense/RTS game where you deploy units to defend a base using active time-loop mechanics.
- How it Works: The level lasts exactly 60 seconds. Every time you fail, you restart the level—but your previous run's ghosts are replayed alongside you, copying your exact past movements and attacks.
- Why it Wins: It features an incredibly impressive "Record & Replay" system. Judges will be blown away seeing multiple versions of your past actions replaying simultaneously on screen.

## 🧭 8. Outpost: Grid-Based Automation & Supply-Chain Factorio

- The Concept: A real-time optimization strategy game where you construct an automated mining colony by placing extractors, conveyor belts, and refining smelters on an isometric grid.
- How it Works: Resources are mined at source coordinates and placed onto moving paths. A continuous global ticker loop updates the x/y matrix locations of every individual resource chunk on the screen, moving them along conveyor node paths toward processing facilities to automatically generate capital.
- Why it Wins: Supply-chain logistics games require flawless queue and matrix management. Keeping track of hundreds of independent inventory objects cleanly routing through conveyor pathways on an interactive board layout is a massive technical accomplishment for a short sprint.

---

## 🎒 EdTech & Developer Tooling

Building software for education or development fits the "Emerging Applications" theme of the event perfectly.

## 🎒 9. StudySphere: The Gamified Spatial Pomodoro Campus

- The Concept: A beautiful, isometric virtual study room where students can customize their desk space, invite virtual study "pets," and manage interactive productivity widgets.
- How it Works: Built using CSS Grid/Flexbox as a single-page application. Students configure custom study blocks. As the countdown timer ticks down, their avatar earns "Focus Credits" which can be spent in an in-game store to unlock items (e.g., custom lofi background tracks, desk plants, dark-mode themes) stored securely in localStorage.
- Why it Wins: It perfectly aligns with the SEAD Academic/EdTech theme. It is instantly relatable to high school judges, visually distinct, and functions as a full productivity suite entirely on the frontend.

## 📐 10. FormForge: Drag-and-Drop Low-Code UI Web Builder

- The Concept: A visual, low-code interface builder that allows users to drag UI elements (buttons, inputs, cards) onto a workspace canvas, customize their CSS properties via a sidebar panel, and export the raw HTML/CSS code.
- How it Works: It relies heavily on the native JavaScript HTML5 Drag and Drop API and Mouse Events (mousedown, mousemove). A master JSON tree tracks the position, styling variables, and content of every component on the canvas. An export module parses this JSON object tree into clean, copyable HTML and CSS strings in real time.
- Why it Wins: Building a software tool for developers is a classic power move in hackathons. It requires highly rigorous tree structure data management and advanced DOM manipulation.

## 📊 11. SortStream: Multi-Algorithm Parallel Processing Visualizer

- The Concept: A learning tool letting users pit classic sorting algorithms against each other in real-time races.
- How it Works: Side-by-side array element bars are sorted by Bubble, Quick, and Merge Sort scripts using synchronized clock loops.
- Why it Wins: It effectively demonstrates computer science foundations, visually proving the relative efficiency of algorithms to teachers and students alike.

---

# ⚙️ Core Data Utilities & Systems

A clean terminal interface with heavy algorithmic sorting logic shows off raw programming capabilities.

## 🕵️‍♂️ 12. EnigmaCode: Cyber-Warfare Decryption Terminal

- The Concept: A stylized command-line puzzle game where players act as military cypher-analysts intercepting, decoding, and counter-hacking foreign terminal nodes under a ticking clock.
- How it Works: The app displays a matrix of scrolling, encrypted "alien" strings. The user must parse the text by applying shifting algorithms (e.g., Caesar Cyphers, Vigenère Cyphers, and Base64 translations) using interactive UI levers, matching frequency graphs before their terminal firewall drops.
- Why it Wins: Cyber-puzzles are incredibly tense and engaging for audiences. It demonstrates clean string manipulation logic, cryptographic mathematics, and a beautifully polished terminal aesthetic using pure CSS neon themes.

---

Out of these 12 winning formulas, which one specific project has your absolute highest confidence?
Tell me your selection, and I will generate your custom HTML framework layout and core JavaScript architecture so you can bypass setup and hit the ground running!
