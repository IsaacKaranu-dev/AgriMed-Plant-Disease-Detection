# ⭐ Plant-Disease-Detection

## 📝 Project Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch to identify 39 distinct plant diseases from leaf images. Leveraging the PlantVillage dataset, this application provides a practical tool for farmers, gardeners, and plant enthusiasts to detect diseases quickly and accurately. The user interface is built with Flask, HTML, CSS, JavaScript, and Bootstrap, ensuring a responsive and user-friendly experience.

**Dataset:**
The model was trained on the publicly available PlantVillage dataset, which contains thousands of images of healthy and diseased plant leaves across various species. This dataset provided a robust foundation for training a reliable disease detection model.

**Model Accuracy:**
The trained CNN model achieves an accuracy of approximately 95% on the test dataset, demonstrating its effectiveness in identifying plant diseases.

**Goals:**
The primary goal of this project is to create an accessible and user-friendly tool that empowers users to quickly identify plant diseases, thereby promoting plant health and preventing crop losses.

**Features:**
* **Image Upload:** Users can upload leaf images directly through the web interface.
* **Real-Time Disease Prediction:** The application provides immediate disease predictions upon image upload.
* **Confidence Scores:** Along with disease predictions, the application displays confidence scores, indicating the certainty of the prediction.
* **User-Friendly Interface:** The interface is designed to be intuitive and easy to navigate for users of all technical backgrounds.

## 🎥 Video Demo

[![Video Demo](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

## 🖼️ Screenshots

### Upload Page
![Upload Page](screenshots/upload_page.png)

### Results Page
![Results Page](screenshots/results_page.png)

## 🚀 Run Project in your Machine

**Operating Systems:**
This project is compatible with Windows, macOS, and Linux operating systems.

**Hardware Requirements:**
It is recommended that your machine have at least 8GB of RAM and a stable internet connection. A GPU is recommended for faster model inference, but not required.

1.  **Install Python 3.8:**
    * Ensure Python 3.8 is installed on your system.
    * Download from: [Python 3.8.18 Release](https://www.python.org/downloads/release/python-3818/)

2.  **Create and Activate a Virtual Environment:**
    * It is highly recommended to use a virtual environment to manage project dependencies.
    * Refer to: [Virtual Environment Instructions](https://docs.python.org/3/tutorial/venv.html)

3.  **Install Dependencies:**
    * Navigate to the project directory in your terminal.
    * Run the following command:
        ```bash
        pip install -r requirements.txt
        ```

4.  **Navigate to the Flask App Folder:**
    * Change your current directory to the "Flask Deployed App" folder.

5.  **Download the Pre-trained Model:**
    * Download the `plant_disease_model_1.pt` file from: [Here](https://drive.google.com/file/d/1moSLVuAevmCgSiBsYWbi1ueJIXXRzlrG/view?usp=sharing).

6.  **Place the Model File:**
    * Move the downloaded `plant_disease_model_1.pt` file into the "Flask Deployed App" folder.

7.  **Run the Flask App:**
    * Execute the following command:
        ```bash
        python3 app.py
        ```

**Using the application:**
Once the application is running, open your web browser and navigate to `http://127.0.0.1:5000/`. You can then upload a leaf image using the provided interface.

**Output:**
The application will display the predicted disease name, along with a confidence score indicating the probability of the prediction being correct.

**Troubleshooting:**
* If you encounter issues with dependency installation, ensure you have the correct Python version and that your virtual environment is activated.
* If the application fails to start, verify that the model file is correctly placed in the "Flask Deployed App" folder.
* If you encounter any other issues, please contact [Your Email].

**Model Training:**
The CNN model was trained using the following parameters:
* Optimizer: Adam
* Loss Function: CrossEntropyLoss
* Epochs: 20
* Batch Size: 32
* Learning Rate: 0.001
The model architecture consisted of convolutional layers, pooling layers, and fully connected layers, optimized for image classification tasks.

## 🤝 Contributions

Contributions are welcome! If you'd like to contribute, please follow these guidelines:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Commit your changes with clear and descriptive commit messages.
4.  Push your changes to your fork.
5.  Submit a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 📧 Contact

[Your Name] - [Your Email]
