# CATAN-Balancer
To explain the provided code and create a flowchart, we will break down the code into parts and then visualize it in a flowchart. Here is a step-by-step explanation of the code:

1. **Importing Libraries**: The code starts by importing necessary libraries like matplotlib and numpy.
2. **Setting Up Plot**: It sets up the plot with specific configurations and creates a hexagonal grid for a board game.
3. **Defining Hexagon and Port Locations**: It defines the locations of hexagons and ports on the board.
4. **Assigning Resources to Tiles and Ports**: Resources like wood, wheat, stone, brick, sheep, and desert are assigned to tiles and ports based on certain rules.
5. **Checking Resource Placement**: It checks if certain resources like brick and stone are not placed next to each other in the grid.
6. **Assigning Dice Roll Numbers**: Random dice roll numbers are assigned to each tile on the board.
7. **Checking Number Placement**: It ensures that no two tiles have the same dice roll number next to each other or share the same number on one resource.
8. **Plotting the Board**: The code then plots the board with colored hexagons representing different resources, ports, and dice roll numbers.

Now, let's create a flowchart based on these steps to visually represent how the code functions:

```flow
st=>start: Start
op1=>operation: Import Libraries
op2=>operation: Set Up Plot
op3=>operation: Define Hexagon and Port Locations
op4=>operation: Assign Resources
op5=>operation: Check Resource Placement
op6=>operation: Assign Dice Roll Numbers
op7=>operation: Check Number Placement
op8=>operation: Plot Board
e=>end: End

st->op1->op2->op3->op4->op5->op6->op7->op8->e
```

This flowchart outlines the sequential steps involved in the code execution, from importing libraries to plotting the final board. Each step contributes to creating a randomized board layout for a game.

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/13235423/b5964dac-1338-4685-8259-28b31ea60d8f/paste.txt
