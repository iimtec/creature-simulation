# Creature Battle Project (OOP + Git Branching Practice)

This project is designed to help me learn **object-oriented programming** in Python — especially **inheritance** — while also practicing key **Git concepts** like branching, merging, conflict resolution, and version history.

I will begin with a base class (`Creature`) and create additional subclasses on separate Git branches to simulate a real development workflow.

---

## Learning Objectives

### Python / OOP
- Understand and implement **classes**
- Use **inheritance** to extend behaviors
- Override and extend methods (e.g., `attack()`)
- Practice writing simple test code in `main`

### Git / Version Control
- Create and switch branches
- Merge branches into `main`
- Resolve merge conflicts
- View commit history (`git log --graph --all`)


---

## Project Structure
oop_creature_code/

│

├── creature_simulation.py # Base class + subclasses

└── README.md

---

## How to Run the Program

1. **Clone the Repository**  
   Use the following command to clone the repository:
   ```bash
   git clone <repository-url>
   cd oop_creature_code```

2. **Run the Simulation**
    Execute the Python script to test the creatures and their behaviors:
    ```bash 
    python creature_simulation.py```

3. **Explore the Code**
    - The Creature class is the base class for all creatures.
    - Subclasses like FlyingCreature, SwimmingCreature, and FireCreature extend the base class with unique behaviors.
    - Test cases are included in the main section of the script.