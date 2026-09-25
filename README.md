# <div align="center">🎮🤖 AI-Powered Pac-Man Game</div>

<div align="center">

### *Where Classic Arcade Meets Artificial Intelligence & Prompt Engineering*

<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=24&duration=3000&color=00F7FF&center=true&vCenter=true&width=800&lines=A*+%7C+BFS+%7C+DFS+%7C+Greedy+%7C+Q-Learning;Real-Time+AI+Pathfinding+Visualization;Prompt-Driven+AI+Game+Analysis;Reinforcement+Learning+Inside+Pac-Man;Built+with+JavaScript+%26+Three.js" />

<br>

<img src="https://img.shields.io/badge/AI-Powered-00F7FF?style=for-the-badge&logo=OpenAI&logoColor=white"/>
<img src="https://img.shields.io/badge/Prompt-Engineering-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/Reinforcement-Learning-purple?style=for-the-badge"/>

</div>

---

# 🧩 Prompt Engineering Cards

> **Prompt Engineering Layer:** The project uses structured prompts to control how an AI assistant analyzes Pac-Man gameplay, explains algorithm decisions, evaluates ghost behavior, and recommends improvements.

### 🟦 Prompt Card 01 — AI Game Analyst

**Purpose:** Analyze the current game state and explain what the AI agents are doing.

```text
ROLE:
You are an AI Game Analyst specializing in pathfinding and
reinforcement learning.

TASK:
Analyze the current Pac-Man game state using the provided
game statistics.

INPUT:
- Player position
- Ghost positions
- Selected AI algorithm
- Path length
- Nodes explored
- Execution time
- Catch result
- Q-learning reward

INSTRUCTIONS:
1. Identify the decision made by the AI.
2. Explain why the selected path was chosen.
3. Evaluate the efficiency of the decision.
4. Identify possible weaknesses.
5. Suggest one improvement.

CONSTRAINT:
Keep the explanation concise and understandable to a student.

OUTPUT:
Decision → Reason → Performance → Weakness → Improvement
```

---

### 🟪 Prompt Card 02 — Algorithm Comparison

**Purpose:** Compare A*, BFS, DFS, and Greedy Search using actual gameplay metrics.

```text
ROLE:
You are an AI algorithm comparison assistant.

TASK:
Compare the performance of the following pathfinding algorithms:
A*, BFS, DFS, and Greedy Search.

METRICS:
- Path Length
- Nodes Explored
- Execution Time
- Path Efficiency
- Catch Success

RULES:
Do not assume that one algorithm is always better.
Base the comparison only on the provided metrics.

OUTPUT:
1. Performance summary
2. Key differences
3. Trade-offs
4. Situations where each algorithm is useful
```

---

### 🟩 Prompt Card 03 — Q-Learning Coach

**Purpose:** Explain how the reinforcement-learning ghost improves through rewards.

```text
ROLE:
You are a reinforcement learning coach.

TASK:
Analyze the Q-Learning agent's recent training experience.

INPUT:
- Current State
- Action
- Reward
- Next State
- Q-Value
- Exploration Rate
- Previous Q-Value

ANALYZE:
1. Was the action beneficial?
2. How did the reward affect learning?
3. Did the Q-value increase or decrease?
4. What behavior is the agent learning?
5. What should the agent try next?

OUTPUT:
Learning Event → Reward Meaning → Q-Value Change → Learned Behavior
```

---

### 🟨 Prompt Card 04 — Adaptive Difficulty

**Purpose:** Use gameplay performance to recommend dynamic difficulty changes.

```text
ROLE:
You are an adaptive game difficulty controller.

TASK:
Analyze the player's recent gameplay performance.

INPUT:
- Player Score
- Survival Time
- Ghost Catch Rate
- Average Distance From Ghosts
- Number of Lives
- Recent Win/Loss Results

RULES:
If the player consistently performs well, recommend increasing
difficulty gradually.

If the player repeatedly struggles, recommend reducing difficulty.

Avoid extreme changes.

OUTPUT:
Current Difficulty → Performance Analysis → Recommended Change → Reason
```

---

### 🟥 Prompt Card 05 — Ghost Strategy Generator

**Purpose:** Generate different strategic behaviors for AI ghosts.

```text
ROLE:
You are a Pac-Man ghost strategy designer.

TASK:
Determine the most appropriate strategy for the ghost based on
the current game state.

AVAILABLE STRATEGIES:
- Direct Chase
- Interception
- Defensive Positioning
- Random Exploration
- Player Prediction

INPUT:
- Player Position
- Player Direction
- Ghost Position
- Maze Layout
- Distance to Player
- Current Game State

CONSTRAINT:
Select a strategy based on the current state rather than using
the same strategy every time.

OUTPUT:
Selected Strategy → Reason → Target Position → Expected Behavior
```

---

### 🟧 Prompt Card 06 — AI Performance Explainer

**Purpose:** Convert technical analytics into understandable explanations.

```text
ROLE:
You are an AI performance educator.

TASK:
Explain the following AI performance metrics to a student.

METRICS:
- Nodes Explored
- Path Efficiency
- Execution Time
- Reward
- Q-Value
- Success Rate

RULES:
Use simple technical language.
Give one practical Pac-Man example for each metric.

OUTPUT:
Metric → Meaning → Pac-Man Example → Why It Matters
```

---

### ⚙️ Prompt Engineering Techniques Used

| Technique                   | Application                                            |
| --------------------------- | ------------------------------------------------------ |
| 🎭 Role Prompting           | Assigns the AI roles such as Game Analyst and RL Coach |
| 🎯 Clear Task Definition    | Defines exactly what the AI needs to perform           |
| 📥 Structured Input         | Game statistics are provided in a consistent format    |
| 📋 Output Formatting        | Forces predictable and readable responses              |
| 🚧 Constraints              | Prevents irrelevant or exaggerated responses           |
| 🔍 Few-Shot Style Structure | Demonstrates the expected reasoning/output pattern     |
| 🔄 Context Injection        | Current game state is supplied to the AI               |
| 📊 Data-Driven Prompting    | AI decisions are based on actual game metrics          |
| 🧠 Role Specialization      | Different prompts handle different AI tasks            |

---

# 🌐 Live Demo

🚀 **Play the Game Here:**
https://pacman-game-manav.netlify.app/

---

# 🧠 About The Project

This project transforms the classic Pac-Man game into an intelligent AI-driven environment where every ghost can use a different decision-making technique to chase the player in real time.

Instead of fixed enemy behavior, the game demonstrates how different Artificial Intelligence techniques make decisions, optimize paths, and learn from experience.

The project is enhanced with a **Prompt Engineering layer** that allows an AI assistant to interpret game-state information, explain algorithmic decisions, compare AI strategies, analyze reinforcement-learning behavior, and provide adaptive gameplay recommendations.

The system therefore combines:

**Game AI + Pathfinding + Reinforcement Learning + Prompt Engineering + Data Visualization**

---

# ✨ Features

✅ Multiple AI Algorithms
✅ A* Pathfinding
✅ BFS Pathfinding
✅ DFS Pathfinding
✅ Greedy Search
✅ Q-Learning Reinforcement Learning
✅ Prompt Engineering Layer
✅ AI Game Analysis
✅ Algorithm Comparison
✅ AI Performance Dashboard
✅ Real-Time Pathfinding Visualization
✅ Dynamic Ghost Behaviors
✅ Feature-Based Learning System
✅ Smooth Tile-Based Movement
✅ Interactive 3D Environment
✅ Cyberpunk UI

---

# 👾 AI Algorithms Used

| Algorithm           | Description                                                       |
| ------------------- | ----------------------------------------------------------------- |
| 🧠 **A***           | Uses path cost and heuristic distance to find an efficient path   |
| 🔍 **BFS**          | Explores nodes level-by-level and can guarantee the shortest path |
| 🌊 **DFS**          | Explores deeply before backtracking                               |
| ⚡ **Greedy Search** | Selects paths based primarily on heuristic distance               |
| 🎯 **Q-Learning**   | Learns action values using rewards and environmental feedback     |

---

# 🤖 Prompt Engineering Architecture

The Prompt Engineering layer sits above the game analytics system.

```text
                 ┌──────────────────────┐
                 │    Pac-Man Game      │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │    Game State        │
                 │ Position / Score     │
                 │ Ghosts / Rewards     │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │   AI Analytics       │
                 │ A* / BFS / DFS / RL  │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Prompt Engineering   │
                 │      Layer           │
                 └──────────┬───────────┘
                            │
          ┌─────────────────┼─────────────────┐
          ▼                 ▼                 ▼
    Game Analyst      RL Coach         Strategy Generator
          │                 │                 │
          └─────────────────┼─────────────────┘
                            ▼
                 ┌──────────────────────┐
                 │ AI Explanation /     │
                 │ Recommendation       │
                 └──────────────────────┘
```

---

# 📊 AI Analytics Dashboard

The project includes a real-time AI dashboard that visualizes:

📈 Path Efficiency
⚡ Execution Speed
🧩 Nodes Explored
🎮 Catch Performance
📉 Reward Progression
🧠 Q-Value Convergence

The analytics data can also be supplied to the Prompt Engineering layer to generate human-readable explanations.

---

# 🧠 Example AI Analysis

### Game State

```text
Algorithm: A*
Path Length: 12
Nodes Explored: 28
Execution Time: 3.4 ms
Catch Result: Successful
```

### Prompt

```text
Analyze this A* decision.

Path Length: 12
Nodes Explored: 28
Execution Time: 3.4 ms
Catch Result: Successful

Explain the efficiency of the decision and identify
one possible improvement.
```

### Expected AI Response

```text
The A* agent successfully caught Pac-Man using a 12-node path
while exploring 28 nodes.

The result indicates that the heuristic helped guide the search
toward the target instead of exploring the maze blindly.

A possible improvement would be dynamically adjusting the
heuristic based on Pac-Man's movement direction.
```

---

# 🔄 Prompt Engineering Workflow

```text
Game Event
    ↓
Collect Game State
    ↓
Generate Structured Input
    ↓
Select Prompt Card
    ↓
Inject Game Context
    ↓
AI Processing
    ↓
Validate Response
    ↓
Display Explanation / Recommendation
```

---

# 🧪 Learning Objectives

This project was created to explore:

* Artificial Intelligence in Games
* Pathfinding Algorithms
* Reinforcement Learning
* Q-Learning
* Prompt Engineering
* Role-Based Prompting
* Structured Prompt Design
* Context Injection
* Constraint-Based Prompting
* AI Decision Explanation
* Real-Time Decision Making
* AI Performance Visualization

---

# 📝 Prompt Engineering Concepts Demonstrated

### 1. Role Prompting

The AI is assigned specialized roles such as:

```text
"You are an AI Game Analyst..."
```

This establishes the expected perspective of the model.

### 2. Context Injection

Real-time game information is inserted into the prompt:

```text
Player Position
Ghost Position
Algorithm
Path Length
Reward
Q-Value
```

This allows the AI to analyze the current game situation rather than producing generic answers.

### 3. Output Constraints

The prompts specify exactly how the response should be structured.

```text
Decision → Reason → Performance → Weakness → Improvement
```

This produces more consistent responses.

### 4. Task Decomposition

Instead of using one large prompt for everything, different prompts handle different tasks:

```text
Game Analysis
      ↓
Algorithm Comparison
      ↓
RL Analysis
      ↓
Strategy Generation
      ↓
Difficulty Recommendation
```

### 5. Data-Driven Prompting

The AI is instructed to use actual gameplay metrics rather than making unsupported assumptions.

---

# 🚀 Future Improvements

🔹 Deep Q-Learning (DQN)
🔹 LLM-powered Ghost Agents
🔹 Natural Language Game Commands
🔹 Voice-Controlled AI Assistant
🔹 Procedural Maze Generation
🔹 Adaptive Difficulty System
🔹 AI-generated Strategy Reports
🔹 Player Behavior Analysis
🔹 Multi-Agent Ghost Coordination
🔹 RAG-based AI Game Knowledge Assistant
🔹 Agentic AI for Autonomous Ghost Strategy

---

# 💡 Proposed Agentic AI Enhancement

A future version can transform the Prompt Engineering layer into an **Agentic AI system**.

```text
                    AI Game Agent
                         │
             ┌───────────┼───────────┐
             ▼           ▼           ▼
        Game Analyst  Strategy AI  RL Coach
             │           │           │
             └───────────┼───────────┘
                         ▼
                  Decision Manager
                         │
                         ▼
                  Game Environment
                         │
                         ▼
                    New State
                         │
                         └──────► Repeat
```

The agent could:

1. Observe the game state.
2. Analyze player behavior.
3. Select an appropriate strategy.
4. Execute the strategy.
5. Observe the result.
6. Evaluate the outcome.
7. Change its strategy.

This would turn the project from a collection of AI algorithms into a more complete **AI-agent experimentation platform**.

---

# 🛠️ Tech Stack

## Frontend

* HTML5
* CSS3
* JavaScript

## Graphics & Visualization

* Three.js
* Chart.js

## AI Concepts

* A* Search
* BFS
* DFS
* Greedy Search
* Q-Learning
* Reinforcement Learning
* Heuristic Search

## Prompt Engineering

* Role Prompting
* Context Injection
* Structured Prompts
* Constraint-Based Prompting
* Task Decomposition
* Data-Driven Prompting
* AI Response Formatting

---

# 🎥 Project Preview

> Replace these placeholders with your own screenshots or gameplay GIFs.

## 🕹️ Gameplay

```md
![Gameplay GIF](your-gif-link-here)
```

## 📊 Dashboard

```md
![Dashboard Screenshot](your-image-link-here)
```

## 🤖 AI Prompt Analysis

```md
![AI Analysis Screenshot](your-image-link-here)
```

---

# 📂 Installation

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

Run using Live Server or any local server.

---

# 📸 Screenshots

> Add your screenshots here.

```md
![Game Screenshot](image-link)
```

---

# 🎓 Academic Relevance

This project demonstrates how traditional Artificial Intelligence algorithms can be combined with modern Generative AI and Prompt Engineering techniques.

The project covers three major layers:

```text
┌────────────────────────────────────┐
│        Generative AI Layer         │
│     Prompt Engineering / LLM       │
├────────────────────────────────────┤
│          Game AI Layer             │
│ A* / BFS / DFS / Greedy / Q-Learn │
├────────────────────────────────────┤
│        Game Environment            │
│       Pac-Man + Three.js           │
└────────────────────────────────────┘
```

This makes the project suitable for demonstrating concepts from **Artificial Intelligence, Reinforcement Learning, Generative AI, and Prompt Engineering** in one interactive application.

---

# 🤝 Connect With Me

💼 LinkedIn
🐙 GitHub
📧 Email

---

# ⭐ Final Note

This project combines a classic arcade game with traditional AI algorithms, reinforcement learning, and modern prompt engineering.

Rather than treating AI as a single algorithm, the project demonstrates different approaches to intelligent behavior:

**Search → Learn → Analyze → Explain → Adapt**

---

<div align="center">

### 🌟 If you liked this project, consider giving it a star ⭐

</div>
