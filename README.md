# AI4DRM: Artificial Intelligence for Disaster Risk Management

## Workshop Overview

This repository contains materials for the 3-day intensive workshop on Artificial Intelligence for Disaster Risk Management (AI4DRM). The workshop provides comprehensive training on neural networks, advanced deep learning architectures, and their applications in natural disaster prediction and detection.

It is designed for students, researchers, and professionals seeking to advance their skills in AI through a blend of theoretical foundations and practical hands-on sessions.

---

## Repository Contents

The content is organized by daily sessions, including code notebooks and relevant datasets.

### Day 1

#### Session 1: Introduction to Artificial Neural Networks (ANN)
- **Location**: `./Day 1/Session 1`
- **Notebook**: `ANN_Code.ipynb`
- **Topics**: Fundamentals of Artificial Neural Networks, ground motion prediction.

#### Session 2: Landslide Prediction
- **Location**: `./Day 1/Session 2`
- **Notebook**: `Landslide_Prediction_for_MLP_CNN.ipynb`
- **Topics**: Landslide susceptibility mapping, MLP, CNN.

#### Session 3: Satellite Flood Detection
- **Location**: `./Day 1/Session 3`
- **Notebook**: `Deep_Learning_for_Satellite_Flood_Detection.ipynb`
- **Topics**: Computer vision for disaster management, satellite imagery analysis, flood segmentation, Convolutional Neural Networks (CNNs).

#### Session 4: Image Classification for Exposure Models
- **Location**: `./Day 1/Session 4`
- **Notebook**: `AI4DRM_CNN_Final.ipynb`
- **Topics**: Data augmentation, CNNs, image classification.

### Day 2

#### Session 1: NeuralHydrology & Rainfall-Runoff Modeling
- **Location**: `./Day 2/Session 1`
- **Notebook**: `AI4DRM_RR.ipynb`
- **Topics**: Deep Learning in Hydrology, LSTM networks, hydrological modeling, data preprocessing, model evaluation using NeuralHydrology.

#### Session 2: Aurora - Atmospheric Forecasting
- **Location**: `./Day 2/Session 2`
- **Notebook**: `Aurora.ipynb`
- **Topics**: Atmospheric prediction, large-scale weather data analysis.

#### Session 3: Image Classification using Vision Transformers
- **Location**: `./Day 2/Session 3`
- **Notebook**: `AI4DRM_ViT_Final.ipynb`
- **Topics**: Vision Transformers (ViT), Transfer Learning, advanced image classification.

#### Session 4: Landslide Movement Prediction
- **Location**: `./Day 2/Session 4`
- **Notebook**: `Landslide_Movements_Prediction_using_LSTM.ipynb`
- **Topics**: Time-series forecasting, LSTM networks, landslide displacement prediction.

---

## Usage Instructions

Recommended environment: Google Colab or a local environment with GPU support.

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Fundamental understanding of Deep Learning

### Getting Started

Follow these steps to set up the project on your local machine.

#### 1. Clone the Repository

Open your terminal or command prompt and run the following commands:

```bash
# Clone the repository
git clone https://github.com/Barbhuiya12/AI4DRM.git

# Navigate into the project directory
cd AI4DRM
```

#### 2. Environment Setup

It is highly recommended to use a virtual environment to manage dependencies.

**Using `venv` (Standard Python):**

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

**Using `conda`:**

```bash
conda create -n ai4drm python=3.8
conda activate ai4drm
```

#### 3. Install Dependencies

Install the required Python libraries. While there is no single requirements file, the notebooks rely on the following common packages:

```bash
pip install pandas numpy matplotlib jupyter neuralhydrology
```

*Note: `neuralhydrology` is specifically required for Day 2 sessions.*

#### 4. Launch Jupyter Notebook

Start the Jupyter Notebook server:

```bash
jupyter notebook
```

#### 5. Run the Notebooks

- In the Jupyter interface, navigate to the specific session directory (e.g., `Day 1/Session 1`).
- Open the desired `.ipynb` file (e.g., `ANN_Code.ipynb`).
- Execute the cells to run the code.

---

