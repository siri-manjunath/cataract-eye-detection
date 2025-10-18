Cataract Detection using Deep Learning
This project is a deep learning-based web application that detects the presence of cataracts from eye images. It uses a Convolutional Neural Network (CNN) model built with TensorFlow/Keras, and a simple Flask web interface that allows users to upload an image and view the prediction instantly.

 Features
Detects cataract vs. non-cataract eye images
Simple and intuitive Flask web interface
Pre-trained CNN model for accurate predictions
Real-time image upload and result display
Modular, easy-to-understand code structure

 
 Tech Stack
Python 3
TensorFlow / Keras
Flask
NumPy, OpenCV, Matplotlib
HTML, CSS (for frontend)

 
 Project Structure
Cataract-Detection/
│
├── app.py                     # Flask web application
├── model/                     # Pre-trained CNN model
├── static/                    # CSS, JS, and image files
├── templates/                 # HTML templates for Flask
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation

 
 Installation & Setup
1️ Clone the repository
git clone https://github.com/<your-username>/cataract-eye-detection.git
cd cataract-eye-detection

2️ Install dependencies
pip install -r requirements.txt

3️ Run the Flask app
python app.py

4️ Open in browser

Go to http://127.0.0.1:5000/ and upload an eye image to test the model.

Model Information

The CNN model is trained on a labeled dataset of eye images (Cataract and Normal).
It uses multiple convolutional and pooling layers, followed by fully connected layers, to classify images accurately.

 Example Prediction
Input Image	Predicted Output


Cataract Detected
 Future Improvements
Add more training data for higher accuracy
Integrate Grad-CAM for visualization
Deploy on cloud (Heroku / AWS / Streamlit)

 Author
Siri Manjunath



