# MLOPS Project


## Overview

Welcome to the MLOPS Project! This project aims to streamline and enhance the machine learning workflow through the use of ZenML, providing a robust and efficient MLOps solution.

## Local Repository

For local development, you can access the ZenML dashboard using the following link:

[Local Dashboard](http://127.0.0.1:8237)

## Google Colab Integration

If you prefer to run your experiments in Google Colab, access the ZenML dashboard through the following link:

[Colab Dashboard](https://038d-34-81-222-230.ngrok-free.app)

![ZENML Dashboard](insert_image_link_here)

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/MLOPS-Project.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd MLOPS-Project
    ```

3. **Set up the virtual environment:**

    ```bash
    # Replace 'env' with your preferred virtual environment name
    python -m venv env

    # Activate the virtual environment
    source env/bin/activate  # On Windows, use 'env\Scripts\activate'
    ```

4. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

5. **Run the ZenML dashboard:**

    ```bash
    # For local development
    zenml up --blocking --port 8237

    # For Google Colab
    # Make sure to run the provided Colab integration code in your Colab notebook
    https://038d-34-81-222-230.ngrok-free.app
    ```
