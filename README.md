# AI Road Condition Classifier 🛣️

An AI-powered web application that analyzes images of roads and classifies their condition as **Good**, **Satisfactory**, **Poor**, or **Very Poor**.

## Tech Stack
- **AI Model:** EfficientNetB0 (Transfer Learning via TensorFlow/Keras)
- **Backend:** Python Flask
- **Frontend:** HTML/JS (built into the Flask app)

## How it works
The AI was trained on a dataset of thousands of road images. It uses advanced data augmentation and a fixed RandomContrast layer to prevent overfitting and deployment bugs. It achieves ~93% real-world accuracy on completely unseen test data.

## How to Run it Locally
1. Clone this repository:
   `git clone https://github.com/LasferYaaqoub/road-condition-ai.git`
2. Install the requirements:
   `pip install -r requirements.txt`
3. Run the Flask server:
   `python app.py`
4. Open your browser and go to `http://localhost:5980`
