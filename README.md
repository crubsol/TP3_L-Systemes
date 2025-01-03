




# L-Systemes

**By Clara Rubio**  


This project uses Blender and Geometry Nodes to generate infinite trees based on Lindenmayer System (L-Systems) rules. It is a creative and programmable tool for designing complex plant-like structures.

## Description

**L-Systems** are a mathematical rule-based technique that describes iterative growth patterns. This project implements these rules in Blender using Geometry Nodes, allowing:

- The creation of trees with diverse shapes and structures.
- Configuration of growth rules through customizable parameters.
- Generation of infinite tree variations by changing rules and iteration parameters.

The system supports:
- L and R rules to define left or right growth.
- Angle, length, and direction configurations.

## Features

- **Configurable parameters:** Define rules like `A`, `F`, and combinations.
- **Highly customizable:** Control the number of iterations, branch length, and bifurcation angles.
- **Visual interface:** Geometry Nodes facilitate understanding and modifying the system's behavior.


### Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/crubsol/TP3_L-Systemes.git
   ```

2. **Open the `L-systems.blend` file** in Blender.

3. Navigate to the **Geometry Nodes** section to explore and edit the system's configurations.

## Usage

1. Select the `Cube` object in the viewport.
2. Open the Geometry Nodes panel.
3. Configure the following options:
   - **Premise:** Define the initial rule (e.g., `A`).
   - **Rules:** Specify L and R rules for branching.
   - **Iteration:** Adjust the number of iterations to control tree complexity.
   - **Angle:** Modify the bifurcation angle.
   - **Length:** Change branch length.

4. Visualize the results in real-time in the viewport.

## Example Configuration

- **Premise:** `A`
- **Rules:**
  - `A -> [&FLA]/////[&FLA]///////[&FLA] ` 
  - `F -> S/////F `
  - `S -> FL`
- **Iterations:** `3`
- **Angle:** `23.090`
- **Length:** `0.410`

## More examples
- `Muestras arboles.blend` you will see a line with many trees with diferents rules and configurations
- `Escenario.blend` is a example of scene with the differents trees created.

