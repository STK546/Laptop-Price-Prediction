# Laptop Price Predictor

This project is a web application that predicts the price of a laptop based on its specifications. It is built using Python, Streamlit, and Scikit-learn.

## Live Demo

You can try out the live application here: [https://laptop-price-prediction-ba73brtqtgu5qls4z3tjxg.streamlit.app/](https://laptop-price-prediction-ba73brtqtgu5qls4z3tjxg.streamlit.app/)

## Features

The model takes the following features as input to predict the price of a laptop:

- **Brand:** The manufacturer of the laptop (e.g., Apple, Dell, HP).
- **Type:** The type of laptop (e.g., Notebook, Ultrabook, Gaming).
- **RAM:** The amount of RAM in Gigabytes.
- **Weight:** The weight of the laptop in kilograms.
- **Touchscreen:** Whether the laptop has a touchscreen or not.
- **IPS:** Whether the laptop has an IPS display or not.
- **Screen Size:** The size of the screen in inches.
- **Screen Resolution:** The resolution of the screen (e.g., 1920x1080).
- **CPU:** The brand of the CPU (e.g., Intel, AMD).
- **HDD:** The size of the Hard Disk Drive in Gigabytes.
- **SSD:** The size of the Solid State Drive in Gigabytes.
- **GPU:** The brand of the Graphics Processing Unit (e.g., Nvidia, AMD, Intel).
- **OS:** The operating system of the laptop (e.g., Windows, macOS, Linux).

## Installation

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/laptop-price-predictor.git
    cd laptop-price-predictor
    ```

2.  **Create a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Once you have installed the dependencies, you can run the Streamlit application with the following command:

```bash
streamlit run app.py
```

This will open the application in your default web browser.

## Data

The model was trained on the `laptop_data.csv` dataset, which contains information about various laptops and their prices. The preprocessed data is stored in `df.pkl`.

## Model

The project uses a machine learning pipeline created with Scikit-learn to preprocess the data and make predictions. The trained pipeline is saved in the `pipe.pkl` file.
