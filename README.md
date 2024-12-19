##Sorting Algorithm Visualizer

#Description :
This project is a Sorting Algorithm Visualizer built using Pygame, a Python library for creating graphical applications. It provides an interactive way to understand and visualize how sorting algorithms work, step-by-step. The visualizer highlights the comparisons and swaps made during sorting, helping you grasp the algorithm's inner workings.

#Features :
Algorithms Supported:
Bubble Sort
Insertion Sort
Interactive Controls:
Reset the list with random numbers
Toggle between ascending and descending order
Start sorting with your selected algorithm
Gradient Color Blocks:
Blocks are color-coded with gradients to make the visualization visually appealing.
Active elements are highlighted in green (comparison) and red (swap).

#How to Run
1.Ensure you have Python installed (version 3.8 or later is recommended).
2.Install the required library:
  "pip install pygame"
3.Run the program:
  "python sorting_visualizer.py"

#Controls
R: Reset the list to new random numbers.
SPACE: Start sorting.
A: Sort in ascending order.
D: Sort in descending order.
I: Select Insertion Sort algorithm.
B: Select Bubble Sort algorithm.
QUIT: Close the program.

#How It Works
When you run the program, a random list of numbers is generated and displayed as blocks.
Use the controls to reset or start sorting with your preferred settings.
Watch as the algorithm highlights the blocks being compared and swapped in real time!

#Customization
You can adjust the number of elements in the list or their range by changing the following variables in the main() function:
n = 50  # Number of blocks
min_val = 0  # Minimum value of the blocks
max_val = 100  # Maximum value of the blocks

