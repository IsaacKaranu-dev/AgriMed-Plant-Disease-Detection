# 🌱 Plant Disease Detection using Deep Learning

**Early detection of plant diseases is critical for farmers to mitigate crop loss.** This project leverages a Convolutional Neural Network (CNN) built with PyTorch to classify leaf images into **39 disease categories** using the [PlantVillage dataset](https://plantvillage.psu.edu/). The model is deployed via a user-friendly Flask web app.

---

## ✨ Key Features

-   **CNN Model**: Trained on 39 plant disease classes for high-accuracy predictions.
-   **Flask Deployment**: Intuitive web interface for real-time image uploads and predictions.
-   **Pre-Trained Model**: Download and integrate the model directly for quick setup.

---

## 🚀 Quick Start

### Prerequisites

-   Python 3.8
-   `pip` package manager

### Installation

1.  **Clone the repository**:

    ```bash
    git clone [https://github.com/your-username/Plant-Disease-Detection.git](https://github.com/your-username/Plant-Disease-Detection.git)
    cd Plant-Disease-Detection
    ```

2.  **Set up a virtual environment**:

    ```bash
    python -m venv venv
    source venv/bin/activate # Linux/MacOS
    venv\Scripts\activate # Windows
    ```

3.  **Install dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

4.  **Download the pre-trained model**:

    -   Get [`plant_disease_model_1.pt`](https://drive.google.com/file/d/1moSLVuAevmCgSiBsYWbi1ueJIXXRzlrG/view?usp=sharing).
    -   Place it in the `Flask Deployed App` folder.

5.  **Run the Flask app**:

    ```bash
    cd Flask\ Deployed\ App
    python3 app.py
    ```

    Access the app at `http://localhost:5000`.

---

## 🧪 Testing the Model

Sample images with labeled diseases are provided in the `test_images` folder. Use these to validate predictions.


---

## 📚 Resources

-   **Dataset**: [PlantVillage Dataset](https://plantvillage.psu.edu/)
-   **Blog Post**: [Project Overview and Dataset Details](your-blog-link-here)
-   **Model Exploration**: Use the Jupyter notebook in the `Model` folder to experiment with the CNN.

