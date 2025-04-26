# Knights of Eldoria - AI Simulation

- gramming following SOLID principles
- 🧰 Memory sharing and team rWelcome to **Knights of Eldoria**, a Python-based AI simulation where treasure hunters explore a fantasy kingdom to gather riches while avoiding patrolling knights. This project demonstrates artificial intelligence concepts, real-time decision-making, and teamwork coordination.
  ---
  ## Features
  - ⭐ Autonomous hunters with memory, stamina management, and skill-based movement
  - 🥇 Treasures (bronze, silver, gold) scattered and decaying over time
  - 🤵 Knights patrol and challenge hunters within a detection radius
  - 🏠 Hideouts serve as resting and treasure deposit hubs
  - 📈 Real-time visualization using Tkinter with emoji-based grid
  - 👨‍💻 Object-Oriented Proecruitment

---

## Project Structure

```bash
knights_of_eldoria/
├── main.py
├── grid.py
├── simulation_manager.py
├── visualizer.py
├── entities/
│   ├── __init__.py
│   ├── treasure.py
│   ├── hunter.py
│   ├── knight.py
│   └── hideout.py
├── utils/
│   └── helpers.py
├── tests/
│   └── test_simulation.py
```

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/knights_of_eldoria.git
cd knights_of_eldoria
```

2. Install dependencies (Python 3.11+ recommended):

```bash
pip install -r requirements.txt
```

> Note: Tkinter should already be installed with Python. If missing, install using your package manager.

---

## Running the Simulation

```bash
python main.py
```

The Tkinter window will open showing hunters, knights, treasures, and hideouts in real-time.

- Hunters: 🢍
- Knights: 🛡️
- Hideouts: 🏠
- Treasures: 🥇 🥊 🥉

---

## AI Behavior Summary

- **Hunters**

  - Move intelligently toward known treasures or hideouts
  - Rest and recover stamina at hideouts
  - Prioritize higher-value treasures
  - Collaborate by sharing knowledge in hideouts
  - Recruit new hunters when conditions allow

- **Knights**

  - Patrol randomly within a radius
  - Detect and chase nearby hunters
  - Force hunters to drop treasures through detain/challenge
  - Retreat to recover energy when needed

---

## Version Control

- Each feature/module tracked using Git commits.
- Tags for major releases: `v1.0` (basic simulation), `v1.5` (AI improvements), `v2.0` (visualizer added).
- Clean commit history showing feature progression.

---


---

## License

This project is open-source for academic and non-commercial use.

---



