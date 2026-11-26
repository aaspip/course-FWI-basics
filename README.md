# Fundamentals of Full Waveform Inversion (FWI)

## Course Overview

This short course introduces the fundamental concepts, mathematical principles, and computational workflows of full waveform inversion (FWI). Through a series of interactive Python notebooks, participants will explore seismic wave propagation, forward and inverse problems, gradient-based optimization, velocity model reconstruction, cycle skipping, and multiscale inversion.

The course emphasizes hands-on learning through numerical experiments and scientific visualization. All notebooks are designed to run directly in Google Colab without requiring local software installation.

## Interactive Notebooks

Click the **Open in Colab** button to launch the corresponding notebook.

| No. | Notebook | Google Colab |
|:---:|:---------|:-----------:|
| 01 | Seismic Wave Propagation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaspip/course-FWI-basics/blob/main/notebooks/01_wave_propagation.ipynb) |
| 02 | Seismic Forward and Inverse Problems | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaspip/course-FWI-basics/blob/main/notebooks/02_forward_inverse.ipynb) |
| 03 | FWI Gradient and Optimization | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaspip/course-FWI-basics/blob/main/notebooks/03_fwi_gradient.ipynb) |
| 04 | Full Waveform Inversion: Numerical Examples | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaspip/course-FWI-basics/blob/main/notebooks/04_fwi_example.ipynb) |
| 05 | Cycle Skipping and Multiscale FWI | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaspip/course-FWI-basics/blob/main/notebooks/05_multiscale_fwi.ipynb) |

## System Requirements

To participate in the hands-on exercises, you only need:

- A Google account.
- A laptop or desktop computer.
- A modern web browser (Google Chrome recommended).
- A stable internet connection.

No local installation of Python, Jupyter Notebook, PyTorch, CUDA, or other scientific computing software is required.

## Getting Started with Google Colab

### Step 1: Open a Notebook

Sign in to your Google account and click the **Open in Colab** button next to the notebook you wish to explore.

### Step 2: Configure the Computing Environment

For computationally intensive exercises, enable GPU acceleration:

1. Select **Runtime → Change runtime type**.
2. Under **Hardware accelerator**, select an available GPU (e.g., T4 GPU).
3. Click **Save**.
4. Click **Connect** to initialize the computing environment.

For lightweight exercises, the default CPU runtime may be sufficient.

Google Colab provides free computing resources, including GPUs, subject to availability and usage limits.

### Step 3: Initialize the Environment

Run the first code cell of the notebook to initialize the computing environment.

The initialization section is intended to automatically:

- Install the required Python packages.
- Download the necessary datasets and supporting code.
- Configure the computing device.
- Prepare the environment for numerical experiments.

The main Python packages used in this course may include:

- NumPy: Numerical computing.
- SciPy: Scientific computing.
- Matplotlib: Scientific visualization.
- PyTorch: Automatic differentiation and optimization.
- Deepwave: Differentiable seismic wave propagation and inversion.

### Step 4: Run the Notebook

There are two ways to execute the notebook:

- **Run individual cells:** Click the play button next to each cell or press `Shift + Enter`.
- **Run the entire notebook:** Select **Runtime → Run all**.

For the best learning experience, we recommend running the cells sequentially, reading the explanations, examining the figures, and experimenting with different parameters.

If Google Colab displays a warning that the notebook was not authored by Google, review the notebook before selecting **Run anyway**.

### Step 5: Save Your Work

To save your modifications and experimental results, select:

**File → Save a copy in Drive**

This creates a personal copy of the notebook in your Google Drive without modifying the original course materials.

## Troubleshooting

- **Missing Python packages:** Rerun the initialization cell.
- **GPU unavailable:** Try a CPU-compatible example or reconnect later.
- **Out-of-memory errors:** Reduce the model size, number of sources, or batch size, where applicable.
- **Runtime disconnected:** Reconnect and rerun the initialization and preceding cells.
- **Unexpected errors:** Select **Runtime → Restart session**, then rerun the notebook from the beginning.

## Course Resources

- [Course Website](https://aaspip.github.io/course-FWI-basics/)
- [GitHub Repository](https://github.com/aaspip/course-FWI-basics)
- [Google Colab](https://colab.research.google.com/)
- [Google Colab Documentation](https://colab.research.google.com/notebooks/basic_features_overview.ipynb)
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
- [Deepwave Documentation](https://ausargeo.com/deepwave/)

---

**Happy learning and experimenting with full waveform inversion!**
