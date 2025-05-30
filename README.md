👁️ Glaucoma Detection Using CNN
A deep learning-based web application for automated glaucoma detection from retinal fundus images using Convolutional Neural Networks (CNN). This project uses Python, TensorFlow, TFLearn, and Flask to classify images into four categories: Normal, Stage 1, Stage 2, and Glaucoma.

📌 Project Overview
Glaucoma is a chronic eye disease that can cause irreversible vision loss if not detected early. This project helps in screening fundus images through a CNN model trained to identify the severity of glaucoma. The application includes a user-friendly web interface for image upload and classification.

📷 Input: Fundus Images
Accepted formats: .jpg, .jpeg, .png
Example sources: ORIGA, RIM-ONE, private clinical datasets

🧠 Algorithms and Frameworks Used
Convolutional Neural Networks (CNNs) for image classification

TensorFlow + TFLearn for model creation and training

Flask for building the web interface

OpenCV / PIL for image preprocessing

Python 3.8 for compatibility with TensorFlow 2.x

**Requirements**

🖥️ System
OS: Windows / macOS / Linux
RAM: ≥ 4 GB
Python: Version 3.8

📦 Python Packages
Install all dependencies with: pip install -r requirements.txt

Contents of requirements.txt: tensorflow==2.3.0, tflearn, flask, numpy, pillow, opencv-python

🛠️ Installation & Setup
1. Clone the Repository: git clone https://github.com/your-username/glaucoma-detection-cnn.git
cd glaucoma-detection-cnn

2. Create a Virtual Environment: python -m venv venv
Activate it:
On Windows: venv\Scripts\activate
On macOS/Linux: source venv/bin/activate

3. Install Dependencies: pip install -r requirements.txt

4. Run the Flask App: python app.py
Visit the app at: http://127.0.0.1:5000/

📂 Project Structure
glaucoma-detection-cnn/
│
├── app.py                   # Flask backend
├── model/                   # Trained CNN model (e.g., model.tfl)
├── static/uploads/          # Uploaded images folder
├── templates/               # HTML templates (index.html, result.html)
├── requirements.txt         # Dependencies list
└── README.md                # Project documentation

📊 Output
Displays classification result
Shows confidence percentage
Visual confirmation of uploaded image

📣 Contributions
1)B N KUSHAL
2)BINDU G
