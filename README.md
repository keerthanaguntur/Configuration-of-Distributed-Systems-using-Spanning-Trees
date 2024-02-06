# Configuration of Distributed Systems using Spanning Trees

This repository contains Python code for configuring distributed systems using spanning trees. The code implements Kruskal's algorithm to generate minimum spanning trees (MSTs) and provides visualization capabilities for both 2D and 3D representations of the resulting configurations.

## Installation

To use this code, you'll need Python installed on your system along with the following dependencies:

- python-igraph
- pandas
- numpy
- matplotlib

You can install these dependencies using pip:

```bash
pip install python-igraph pandas numpy matplotlib
```

## Usage

### Generating Spanning Trees

To generate spanning trees and configure distributed systems, follow these steps:

1. Prepare a CSV file with vertex coordinates representing the nodes of the distributed system.
2. Set the file path to your CSV file in the `csv_file_path` variable within the Python script.
3. Run the script.

```python
# Example usage for generating spanning trees
python Distributed_Systems.ipynb
```

### Visualization

The code provides visualization capabilities for both 2D and 3D representations of the resulting spanning trees.

#### 2D Visualization

For 2D visualization, simply run the script, and the output will display a scatter plot of the vertices along with the edges representing the spanning tree configuration.

#### 3D Visualization

For 3D visualization, prepare a CSV file with 3D vertex coordinates, set the file path accordingly, and run the script. The output will display a 3D scatter plot along with the edges representing the spanning tree configuration.

## Examples

Below are examples of the generated MST visualizations:

- **2D Visualization**: ![2D Visualization](2d_visualization.png)
- **3D Visualization**: ![3D Visualization](3d_visualization.png)

## Contributing

Contributions to this project are welcome. You can contribute by reporting issues, suggesting enhancements, or submitting pull requests.

## Acknowledgements

This project was inspired by concepts in distributed systems and graph theory. Special thanks to the contributors of the python-igraph, pandas, numpy, and matplotlib libraries for their valuable contributions.
