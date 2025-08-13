# Real-Time Object Detector with Teachable Machine

This is a real-time object detection project built using Google's **Teachable Machine** and **TensorFlow.js**. It uses a webcam to identify and classify objects in real-time, displaying the detected object and its confidence level.

The project is designed to be a simple yet effective demonstration of how machine learning models can be trained and deployed on the web without extensive coding.

## ✨ Features

-   **Real-Time Detection**: Utilizes your webcam to continuously analyze and detect objects.
-   **Confidence Score**: Displays a live progress bar showing the confidence level of the prediction.
-   **Clean UI**: A user-friendly interface with modern styling.
-   **Easy to Use**: No installation required—just a web browser and a webcam.

---

## ⚙️ Technologies Used

-   **Teachable Machine**: A web-based tool by Google to easily train machine learning models.
-   **TensorFlow.js**: A JavaScript library for training and deploying machine learning models in the browser.
-   **HTML5**: For the project's structure.
-   **CSS3**: For all the styling and visual enhancements.
-   **JavaScript (ES6+)**: The core logic for running the model and updating the UI.

---

## 🚀 How to Run

1.  **Clone the Repository**:
    ```bash
    git clone [https://github.com/YourUsername/YourRepoName.git](https://github.com/YourUsername/YourRepoName.git)
    cd YourRepoName
    ```
2.  **Open with Live Server**: This project requires a local web server to function correctly. The easiest way to do this is with the "Live Server" extension for Visual Studio Code.
    -   Open the project folder in VS Code.
    -   Right-click on `index.html` and select **"Open with Live Server"**.
    -   Your project will open in your default browser, and you can start detecting objects.

---

## 🤖 How to Train Your Own Model

You can easily train a new model for different objects and replace the URL in the `index.html` file.

1.  **Go to Teachable Machine**: Visit the [Teachable Machine website](https://teachablemachine.withgoogle.com/) and click "Get Started".
2.  **Create an Image Project**: Select "Image Project" and choose "Standard image model".
3.  **Add Classes**: Define the classes (labels) for the objects you want to detect. For example: "Book", "Pen", "Bottle". Be sure to add a "Background" class to train the model on what not to detect.
4.  **Gather Data**: For each class, use your webcam or upload images to provide at least 20-30 examples. Capture the objects from different angles, distances, and lighting conditions to make the model more robust.
5.  **Train Model**: Click the "Train Model" button and wait for the process to complete.
6.  **Export Model**: Once trained, click the "Export Model" button. Select the **TensorFlow.js** tab and click "Upload my model" to get a unique URL.
7.  **Update Code**: Copy this URL and replace the placeholder `"REPLACE_WITH_YOUR_MODEL_URL"` in the `index.html` file with your new URL.

---

## 🤝 Contribution

This project is a personal learning exercise. However, if you find any issues or have suggestions for improvements, feel free to open an issue or a pull request.

---

**Made with ❤️ by Sarang k**
