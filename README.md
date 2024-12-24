# Invisibility-Cloak

Welcome to the Invisibility Cloak project repository! This repository contains two implementations of an invisibility cloak using computer vision and machine learning techniques:

1. **OpenCV-based implementation**
2. **PyTorch-based implementation**

Both implementations are provided as Jupyter Notebook (.ipynb) files for an interactive and easy-to-follow demonstration of the concepts.

## Project Overview
The goal of this project is to simulate an invisibility cloak effect, similar to what you've seen in movies. By detecting a specific color (e.g., red) in a video stream, the code masks the cloak region and replaces it with the background, creating the illusion of invisibility.

### Key Features:
- Real-time color detection and masking.
- Background capture for seamless cloaking.
- Interactive visualization using Jupyter Notebook.

## Repository Contents
- `InvisibilityCloak using OpenCV.ipynb`: Implementation using OpenCV's image processing techniques.
- `InvisibilityCloak_using_Pytorch.ipynb`: Implementation leveraging PyTorch for additional machine learning capabilities.

## Prerequisites
To run the projects, ensure you have the following installed:

### General Requirements:
- Python 3.7 or later
- Jupyter Notebook

### Python Libraries:

#### For OpenCV Implementation:
- `opencv-python`
- `numpy`

#### For PyTorch Implementation:
- `torch`
- `torchvision`
- `numpy`
- `opencv-python`

You can install the required libraries using pip:
```bash
pip install opencv-python numpy torch torchvision
```

## Getting Started
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/invisibility-cloak.git
   cd invisibility-cloak
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open and run either of the following notebooks:
   - `Invisibility_Cloak_OpenCV.ipynb`
   - `Invisibility_Cloak_PyTorch.ipynb`

4. Follow the instructions within the notebook to run the project.

## Usage Instructions
- Make sure your camera is connected and accessible.
- Use a brightly colored cloak (e.g., red) for the best results.
- Run the notebook cells sequentially to set up the cloak effect.


## Future Improvements
- Enhance cloak detection using deep learning-based segmentation.
- Support for multiple cloak colors.
- Improve background capture for dynamic environments.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.


---

Enjoy experimenting with the invisibility cloak effect! 🚀

