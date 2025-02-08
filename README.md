
# 🌟 **DeepFake Detection Project** 🌟

## **🔍 Overview**
Welcome to the **DeepFake Detection Project**! This project is designed to help identify deepfake images and videos using cutting-edge machine learning models. The system is composed of three main components:

- **Frontend (React)**: Allows users to upload images or videos for analysis.
- **Backend (Node.js)**: Handles the upload, processes the request, and interacts with the Flask API.
- **Flask API (ML Model)**: This is where the deepfake detection magic happens! It processes the media files and returns the result.

---

## **👥 Contributors**
This project wouldn't be possible without the help of the following contributors:

- **[Sojo06 (Soham Joshi)](https://github.com/Sojo06)**
- **[LaminarFlow24 (Yashas Jain)](https://github.com/LaminarFlow24)**
- **[TanishValesha (Tanish Valesha)](https://github.com/TanishValesha)**
- **[ShashwatAwate (Shashwat Awate)](https://github.com/ShashwatAwate)**
- **[Sukanya0704 (Sukanya Gupta)](https://github.com/Sukanya0704)**

---

## **💻 Project Setup**

### **1. Prerequisites**
Before you get started, ensure you have the following installed:

- **Node.js** (for both frontend and backend)
- **Python** (to run the Flask API and ML model)
- **pip** (to install Python dependencies)
- **React** (to manage frontend dependencies)

---

### **2. Project Structure**
Here’s how the project is organized:

```
deepfake-detection-project/
├── client/          # React frontend
├── server/          # Node.js backend
└── ml/server/       # Flask server and ML model
```

---

### **3. Setup Instructions**

#### **Step 1: Clone the Repository**
Start by cloning the repository to your local machine.

```bash
git clone <repo_url>
cd deepfake-detection-project
```

#### **Step 2: Frontend Setup (React)**

1. Go to the `client/` directory:

    ```bash
    cd client
    ```

2. Install all required dependencies:

    ```bash
    npm install
    ```

3. Start the React development server:

    ```bash
    npm start
    ```

Your frontend should now be running at `http://localhost:5173`.

#### **Step 3: Backend Setup (Node.js)**

1. Navigate to the `server/` directory:

    ```bash
    cd ../server
    ```

2. Install necessary dependencies:

    ```bash
    npm install
    ```

3. Start the Node.js server:

    ```bash
    npm start
    ```

Your backend should now be running at `http://localhost:3000`.

#### **Step 4: Flask API Setup (ML Model)**

1. Go to the `ml/server/` directory:

    ```bash
    cd ../ml/server
    ```

2. Create and activate a Python virtual environment:

    ```bash
    python3 -m venv venv
    source venv/bin/activate   # For Linux/MacOS
    venv\Scripts\activate    # For Windows
    ```

3. Install required Python dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Launch the Flask API:

    ```bash
    python app.py
    ```

Your Flask API should now be running at `http://localhost:5000`.

---

## **🚀 Usage**

1. Open the React frontend in your browser at `http://localhost:5173`.
2. Upload an image or video using the provided upload form.
3. The backend (Node.js) will forward the request to the Flask API.
4. The Flask API will process the media file using the deepfake detection model and return the result.
5. The result will be displayed on the frontend, showing whether the file is a deepfake or not.

---

## **⚙️ Technologies Used**

- **Frontend**: React, HTML, CSS
- **Backend**: Node.js, Express
- **Machine Learning**: Flask, TensorFlow/PyTorch (depending on the model)
- **API Communication**: RESTful API

---

## **📜 License**
This project is licensed under the MIT License. See the [MIT License](./LICENSE) file for details.

---

Thank you for checking out the DeepFake Detection Project! We hope it helps in the ongoing battle against digital manipulation. 👾
