# Sorting Algorithm Visualization

This Python application visually demonstrates the sorting process of two algorithms: Bubble Sort and Insertion Sort. Built with **Pygame**, it provides an interactive experience to understand how these algorithms work.

## Features

* Visualizes the sorting process step-by-step.
* Supports Bubble Sort and Insertion Sort.
* Allows customization of the sorting order (Ascending or Descending).
* Randomized data generation for unique sorting experiences.

## Requirements

* Python 3.x
* Pygame library

Install Pygame using pip:

```bash
pip install pygame
```

## How to Run

1. Ensure Python 3.x and Pygame are installed.
2. Save the script as `main.py`.
3. Run the script:

   ```bash
   python main.py
   ```

## Usage

### Controls

* **R**: Reset and generate a new random list.
* **SPACE**: Start or pause the sorting.
* **A**: Set sorting order to Ascending.
* **D**: Set sorting order to Descending.
* **I**: Use Insertion Sort for sorting.
* **B**: Use Bubble Sort for sorting.

### Interface

* The window title displays the active sorting algorithm and the order (Ascending/Descending).
* Controls and sorting options are displayed at the top of the window.

## Code Overview

* **`DrawInformation` Class**: Manages display properties and the list to be sorted.
* **`draw` Function**: Handles rendering the interface, controls, and sorted list.
* **`generate_starting_list` Function**: Generates a random list of integers within a specified range.
* **Sorting Algorithms**:

  * `bubble_sort`: Implements Bubble Sort with real-time visualization.
  * `insertion_sort`: Implements Insertion Sort with real-time visualization.
* **`main` Function**: Initializes the application and manages user interaction and the main loop.

## Customization

To modify the number range or list size, edit the `n`, `min_val`, and `max_val` variables in the `main` function:

```python
n = 50       # Number of elements
min_val = 0  # Minimum value
max_val = 100 # Maximum value
```

