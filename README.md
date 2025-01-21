# Timetable Scheduler using Genetic Algorithm

## 📋 Overview
This project is a **Timetable Scheduler** implemented using a **Genetic Algorithm**, designed to efficiently generate optimal schedules by considering various constraints. The genetic algorithm optimizes the scheduling process by evolving potential solutions through selection, crossover, and mutation.

## 🎯 Objective
The aim of this project is to create an automated scheduling system that minimizes conflicts and maximizes efficiency based on predefined constraints such as:
- **Hard Constraints:** Must be strictly followed (e.g., no two courses in the same room at the same time).
- **Soft Constraints:** Should be followed but can be adjusted for optimization (e.g., teacher preferences).

## 🛠️ Features
- **Chromosome Encoding:** Encodes timetable data including course IDs, section details, and professor-room assignments.
- **Fitness Function:** Evaluates schedules by penalizing constraint violations.
- **Genetic Operations:**
  - **Selection:** Picks the fittest chromosomes for crossover.
  - **Crossover:** One-point crossover to generate new schedule variations.
  - **Mutation:** Randomly modifies schedules to explore new possibilities.
- **Population Management:** Maintains and evolves multiple schedule solutions.
- **Graphical Analysis:** Displays fitness evolution over generations.
- **Output Representation:** Final schedule is displayed in tabular format.

## 🧬 Genetic Algorithm Process
1. **Initial Population:** Randomly generates 10 chromosomes (schedules).
2. **Selection:** Chooses the top 2 schedules with the highest fitness scores.
3. **Crossover:** Performs one-point crossover to produce offspring schedules.
4. **Mutation:** Introduces changes to avoid local optima and improve fitness.
5. **Iteration:** Process repeats for a set number of generations.
6. **Final Solution:** Returns the fittest timetable with minimal conflicts.

## 📊 Fitness Function
The fitness function calculates the quality of schedules by:
- Assigning penalties for hard and soft constraint violations.
- Aiming for a score where fewer conflicts indicate a better schedule.

## 🎮 How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/timetable-genetic-algo.git
   ```
2. Install required dependencies (if any).
3. Compile and execute the project.
4. View the generated schedule and fitness graphs.

## ⚙️ System Requirements
- C++/Python (depending on implementation)
- Compatible OS (Windows/Linux/Mac)
- Basic understanding of Genetic Algorithms

## 📝 Credits
Developed by Muhammad Luqman Ansari as part of an academic project using genetic algorithms for timetable optimization.

---

Optimize your schedules efficiently with genetic algorithms! 🧬📅

