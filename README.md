🌱 Plant Disease Detection – Alpha Release
Plant Disease Detection is an open-source project using deep learning + computer vision to detect plant diseases from leaf images.
It comes with a Flask-based web app to upload images, run predictions, and view remedies from a CSV database.

📜 Contents

##Overview

Target Audience

Getting Started

Supported Scenarios

##How It Works

##Repository Structure

Example Usage

Contributing

Code of Conduct

##🔍 Overview

Upload any leaf image

Detect disease type using CNN model

Get remedies & details from dataset

Easy web interface built with Flask

##🎯 Target Audience

Farmers & Gardeners → Identify plant diseases early

Researchers → Use as a baseline for agriculture AI

Developers → Integrate into mobile/web tools

##🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/Haswanth1234/Plant_Disease_Detection_main.git
cd Plant_Disease_Detection_main

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Application
python app.py

4️⃣ Open in Browser
http://localhost:5000

🌿 Supported Scenarios

Detect diseases for multiple crops (from PlantVillage dataset or custom)

Classify healthy vs diseased leaves

Provide treatment suggestions

⚙ How It Works

Upload Leaf Image → through Flask web UI

Preprocessing → resize, normalize, prepare for CNN input

Prediction → CNN model (CNN.py) runs classification

Output → Display disease name, description, remedies from CSV

📂 Repository Structure
Plant_Disease_Detection_main/
├── staticFiles/                     # Static assets (uploaded images)
│   └── uploads/
├── templates/                       # HTML templates for Flask UI
├── test_images/                      # Sample images for testing
├── CNN.py                            # CNN model definition/training
├── app.py                            # Main Flask app
├── Procfile                          # Deployment config (Heroku)
├── disease_info.csv                  # Plant disease descriptions
├── supplement_info.csv               # Additional remedy data
├── flask_get_post_upload_read_csv.py # Example CSV upload/read script
├── requirements.txt                  # Python dependencies
└── README.md                         # Documentation

💻 Example Usage
Upload a Test Image
# Place your image in test_images/ folder
# Run the app
python app.py
# Open browser → upload image → click "Predict"


Expected output:

Prediction: Apple Scab  
Remedy: Apply recommended fungicides and remove infected leaves.

🤝 Contributing

We welcome contributions:

# Fork the repository
# Create a new branch
git checkout -b feature-name

# Make changes
git commit -m "Added new feature"

# Push changes
git push origin feature-name
