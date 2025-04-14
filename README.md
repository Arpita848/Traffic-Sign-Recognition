# 🚦 AI-Powered Traffic Sign Recognition System

An AI-based system to detect and classify traffic signs using a custom-trained Convolutional Neural Network (CNN). The model is trained and tested locally in VS Code using Keras and TensorFlow, and deployed using a Flask web application for real-time predictions.

---

## 🧠 Technologies Used
- Python
- TensorFlow / Keras
- OpenCV, NumPy
- Flask
- HTML, CSS (for web UI)
- VS Code

---

## 📁 Project Structure
├── app.py # Flask app to handle image upload and prediction ├── model.h5 # Trained CNN model file ├── labels.csv # Class labels for traffic signs ├── templates/ │ └── index.html # Frontend HTML form for image upload ├── static/ │ └── sample_images/ # Optional: Sample test images ├── requirements.txt # Python dependencies ├── README.md # Project overview and instructions


---

## ⚙️ Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/traffic-sign-recognition.git
   cd traffic-sign-recognition
2. Create a Virtual Environment (optional but recommended)
python -m venv venv
source venv/bin/activate    # For Mac/Linux
venv\Scripts\activate       # For Windows
3. Install Dependencies
pip install -r requirements.txt
4. Run the Flask App
python app.py
5. Open in Browser Navigate to http://127.0.0.1:5000 in your browser to test the app.
🔍 How It Works

The CNN model is trained on labeled traffic sign images (stored in folders by class).
Images are preprocessed using:
Grayscale conversion
Histogram equalization
Resizing to standard input shape
The model is trained and saved as model.h5.
A Flask app (app.py) loads the model and predicts the uploaded image.
The result is displayed on a web interface.

🙋‍♀️ About Me
👩‍💻 Arpita Panigrahi
MCA Student | AI & ML Enthusiast
📍 Odisha, based in Dehradun
🔗 LinkedIn "www.linkedin.com/in/arpita-panigrahi-429b70269"
