Explanation of Each Step:

Step 1: Import Libraries
We import matplotlib.pyplot for plotting and numpy for generating numerical data. These are essential libraries for data visualization and numerical operations in Python.

Step 2: Create Data
We generate data for three mathematical functions—sin(x), cos(x), and tan(x)—using the numpy.linspace() function to create a sequence of 100 values from 0 to 10.

Step 3: Create a Multiplot Layout
plt.subplots() is used to create a 2x2 grid for the subplots. This allows us to display four separate plots in a single figure, and figsize=(10, 8) adjusts the overall size of the plot to ensure clarity.

Step 4: Plot Data
Each subplot is populated with one of the mathematical functions. We specify the color and line style for each plot and add a title, labels, and legends to make the plots more informative.

Step 5: Layout Adjustment
plt.tight_layout() adjusts the spacing between subplots to ensure they do not overlap with each other.

Step 6: Display the Plot
Finally, plt.show() displays the figure with all four subplots.

Output of the Code:

The code will generate a window with four plots:
Sine Wave
Cosine Wave
Tangent Wave (with y-axis limits)
Combined Plot of Sine and Cosine
Each plot will have a title, axis labels, and legends for clarity.
