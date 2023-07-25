# pizza-ingredient-problem

# Pizza Preferences Optimizer

This repository contains code that optimizes the selection of ingredients for a pizza to maximize the number of potential clients visiting a pizzeria. Each client has their own pizza preferences, and they will visit the pizzeria if their preferences are met.

## Problem Description

In this problem, there are multiple potential clients, each with their likes and dislikes for pizza ingredients. The goal is to choose the ingredients to put on the pizza such that:

- All the ingredients a client likes are on the pizza, and
- None of the ingredients a client dislikes are on the pizza.

## Input

The input consists of:
- The number of potential clients, `C` (1 ≤ C ≤ 10^5).
- For each client, two lines of input:
  - The first line contains an integer `L` (1 ≤ L ≤ 5) representing the number of ingredients the client likes, followed by `L` names of ingredients the client likes, delimited by spaces.
  - The second line contains an integer `D` (0 ≤ D ≤ 5) representing the number of ingredients the client dislikes, followed by `D` names of ingredients the client dislikes, delimited by spaces.
  
Each ingredient name consists of between 1 and 15 ASCII characters, including lowercase letters (a-z) and digits (0-9).

## Output

The output is a single line with the following format:
```
N ingredient1 ingredient2 ... ingredientN
```
where:
- `N` is the number of ingredients selected to put on the pizza (0 ≤ N ≤ 5).
- `ingredient1`, `ingredient2`, ..., `ingredientN` are the names of the selected ingredients, separated by spaces.

## How to Use

1. Clone the repository to your local machine:
```
git clone https://github.com/your-username/pizza-ingredient-problem.git
```
Install Jupyter Notebook if you haven't already:
```
pip install jupyter
```
Launch Jupyter Notebook:
```
jupyter notebook
```
Open the ` pizza-ingredient-problem ` notebook in Jupyter.

Run the notebook cells to execute the code.

Input the number of potential clients and their preferences as described in the prompt.

The notebook will output the optimal selection of ingredients for the pizza.

## Scoring

The solution is scored based on the number of clients that will visit the pizzeria. One point is awarded for each client whose preferences are met.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to use, modify, and distribute the code according to the terms of the MIT License.

