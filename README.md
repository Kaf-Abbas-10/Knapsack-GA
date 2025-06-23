# Genetic Algorithm

This project demonstrates the use of a Genetic Algorithm to solve the classic Knapsack Problem. The implementation is provided in a Jupyter Notebook as part of the Operating Systems lab coursework at FAST-NUCES.

## 🧠 Objective

The goal is to apply genetic algorithm techniques to optimize the selection of items for a knapsack, maximizing value without exceeding a weight limit. The notebook showcases population initialization, fitness evaluation, selection, crossover, mutation, and replacement strategies.

## 📁 File Overview

- **GeneticAlgo.ipynb**: Main Jupyter Notebook implementing the genetic algorithm for the Knapsack Problem. Contains all code, logic, and output.

## 🛠 Requirements

To run the notebook, ensure you have:

- Python 3.8+
- Jupyter Notebook

All code uses only built-in Python modules (`random`), so no extra packages are required.  
To install Jupyter Notebook, use:

```bash
pip install notebook
```

## 🚀 How to Run

1. Open the notebook in Jupyter:

   ```bash
   jupyter notebook GeneticAlgo.ipynb
   ```
2. Run each cell sequentially or run the entire notebook.

## 🧩 Features

* **Problem Setup**: Defines a set of items, each with a value and weight, and a maximum knapsack weight.
* **Population Initialization**: Randomly generates an initial population of possible solutions.
* **Fitness Function**: Evaluates solutions based on total value and weight constraints.
* **Selection**: Chooses parents for reproduction based on fitness.
* **Crossover**: Combines parents to produce new offspring.
* **Mutation**: Randomly alters offspring to maintain genetic diversity.
* **Replacement**: Ensures only valid solutions remain in the population.
* **Execution**: Runs the genetic algorithm for a set number of generations and prints the best solution found.

## 📊 Output

The notebook prints the best solution found by the genetic algorithm after all generations, showing which items are selected for the knapsack.

## 📚 Concepts Demonstrated

* Genetic algorithm workflow
* Fitness evaluation and selection pressure
* Crossover and mutation operations
* Validity checking and population replacement

## 👨‍💻 Author

* **Name**: Kaf Abbas
* **Roll No**: i22-0763
* **Institute**: FAST-NUCES

## 📜 License

This project is for educational purposes as part of the Operating Systems lab. Feel free to explore, modify, and learn from it!
