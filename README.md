![head](https://github.com/user-attachments/assets/68f8050a-3886-4cb4-a03d-070fbee6d382)


## Introduction
This is a solution for the "Curvetopia" problem given in Adobe GenSolve x GeekForGeeks. It provides various functionalities for working with geometric shapes, including regularization, symmetry detection, and curve completion. Please read the [solution explanation](Solution-Explanation.pdf) for proper clarity of the proposed solution.

## Features
- **Polyline Regularization**: Simplifies and straightens polylines using the Ramer-Douglas-Peucker (RDP) algorithm.
- **Shape Regularization**:  The algorithm leverages contour approximation to classify shapes. For identified shapes like circles, squares, and polygons, 
                             the code computes and draws
 idealized shapes
- **Symmetry Detection**: Identifies lines of symmetry in shapes (vertical, horizontal, and diagonal).
- **Curve Completion**: Completes missing parts shapes

## Installation

### Prerequisites
- Python 3.x
- Required libraries: numpy, matplotlib, scipy, opencv-python (cv2), svgpathtools

To install the required libraries, run:

```bash
pip install -r requirements.txt
```

### Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/shape-analysis-tool.git
   cd Round-2
   ```

2. Ensure your data files are in the correct directories as specified in the scripts.

## Usage
Go to the notebooks folder -> open main.ipynb

## Acknowledgments
This project was developed as part of Adobe GenSolve organised by Adobe and GeeksForGeeks.
