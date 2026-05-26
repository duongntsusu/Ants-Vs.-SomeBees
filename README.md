1. Introduction:
Ants Vs. SomeBees is a tower defense game inspired by Plants vs. Zombies, where players defend an ant colony from waves of invading bees using strategically placed ants with unique abilities. Built in Python using object-oriented programming principles, the project focuses on game logic, inheritance, polymorphism, and large-scale program design. Originally completed as part of UC Berkeley’s Data C88C course, the project involves extending and testing an existing codebase while implementing different ant behaviors, enemy interactions, and game mechanics.

2. Gameplay: Each game consists of a sequence of turns:
- Bees invade the colony tunnels
- Players deploy ants to defend the colony
- Ants perform actions such as:
+ Throwing leaves at bees
+ Collecting food
+ Protecting other ants
- Bees advance through tunnels and sting ants in their way
- The game ends when: A bee reaches the queen/ The QueenAnt is destroyed/All bees are defeated

3. Project Structure
- ants.py — Core game logic and insect behaviors
- ants_plans.py — Difficulty configurations and attack waves
- gui.py — Graphical user interface
- ucb.py — Utility functions
- tests/ — Automated tests
- static/ — Game assets and images
- templates/ — HTML templates used by the GUI
