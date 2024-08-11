# **Curvetopia: Curve Recognition and Beautification (Adobe GenSolve Task)**

## **Project Overview**

This project is a part of the Adobe GenSolve challenge, specifically under the Curvetopia initiative. The primary goal is to develop a solution that can recognize, regularize, and beautify 2D curves derived from line art. The notebook provided as part of this task processes polyline inputs, identifies various geometric shapes, explores symmetry, and completes partial curves. The final output transforms these polylines into smooth, regularized shapes like cubic Bézier curves.

## **Table of Contents**

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Key Features](#key-features)
- [Examples](#examples)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## **Installation**

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo-name/curvetopia.git
    ```
2. Navigate to the project directory:
    ```bash
    cd curvetopia
    ```
3. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate # On Windows use `venv\Scripts\activate`
    ```
4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## **Usage**

1. Launch the Jupyter notebook:
    ```bash
    jupyter notebook
    ```
2. Open the `Recognisation_of_curve.ipynb` notebook.
3. Follow the instructions within the notebook to process your own polyline data or use the provided example data.
4. The output will include visualizations of the regularized and beautified curves.

## **Project Structure**

```
curvetopia/
│
├── data/
│   ├── examples/         # Contains example polyline CSV files
│   └── output/           # Directory where processed outputs will be saved
│
├── src/                  # Source code files
│   ├── curve_processing.py # Core functions for curve processing
│   └── visualization.py    # Visualization functions
│
├── notebooks/
│   ├── Recognisation_of_curve.ipynb  # Main notebook
│
├── requirements.txt     # Python packages required for the project
├── README.md            # Project documentation (this file)
└── LICENSE              # License for the project
```

## **Key Features**

- **Curve Regularization:** Automatically identifies and regularizes common shapes such as straight lines, circles, ellipses, and polygons from polyline inputs.
- **Symmetry Detection:** Analyzes and identifies symmetry in closed curves.
- **Curve Completion:** Completes partial or fragmented curves to create smooth, continuous shapes.
- **Output:** Generates aesthetically pleasing cubic Bézier curves from the input polylines.

## **Examples**

Examples of the input and output can be found in the `data/examples/` directory. This includes:
- Isolated and fragmented shapes
- Curves with varying levels of symmetry
- Completed curves after occlusion removal

## **Dependencies**

- Python 3.8+
- NumPy
- Matplotlib
- Jupyter Notebook

All dependencies can be installed via the `requirements.txt` file.

## **Contributing**

Contributions are welcome! Please follow the standard GitHub flow:
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## **Acknowledgments**

This project was developed as part of the Adobe GenSolve challenge. Special thanks to Adobe for providing this opportunity and the guidance throughout the project.

---

This README provides a comprehensive guide for anyone who wants to understand, set up, and contribute to your project. Feel free to customize any sections as needed!
