# Plant_Disease_Detection_main
🌱 Plant Disease Detection  An AI-powered solution to identify plant diseases from leaf images using deep learning and computer vision. This project aims to assist farmers, gardeners, and agricultural researchers in detecting plant health issues early, reducing crop losses, and improving productivity.

Plant Disease Detection

An AI-powered application that identifies plant diseases from leaf images using deep learning and computer vision. Designed to help farmers, gardeners, and agricultural researchers detect plant health issues early—reducing crop losses and improving yield.

Project Overview

Purpose: Upload leaf images, then receive predictions on plant disease status using a trained convolutional neural network (CNN).

Use Case: Early detection helps in timely treatment and prevention, aiding efficient agricultural practices.

Features

User Interface: Built using Flask; users can upload images and view results seamlessly.

CNN Model: Architecture implemented in CNN.py for disease classification.

Backend & Deployment: Includes Procfile for deployment, e.g., on Heroku.

Supplementary Data:

disease_info.csv – disease descriptions.

supplement_info.csv – extended information (e.g., remedies or treatment suggestions).

Sample Images: Located under test_images for quick testing.

Static & Template Assets: Organized under staticFiles/uploads and templates.

Repository Structure

Plant_Disease_Detection_main/

├── staticFiles/

│   └── uploads/

├── templates/

├── test_images/

├── CNN.py

├── app.py

├── Procfile

├── disease_info.csv

├── supplement_info.csv

├── flask_get_post_upload_read_csv.py

└── requirements.txt

Getting Started

Clone the repo

git clone https://github.com/Haswanth1234/Plant_Disease_Detection_main.git

cd Plant_Disease_Detection_main


Install dependencies

pip install -r requirements.txt


Run the app

python app.py


Access the web interface
Open your browser at http://localhost:5000, upload a leaf image, and get the prediction.

How It Works

Image Upload: Users upload a leaf image via the web interface.

Preprocessing & Prediction: The image is processed and passed through the CNN (CNN.py), generating a disease prediction.

Result Display: The UI shows the predicted disease along with helpful details from the CSV files.

Dataset & Model (Optional)

If the model was trained using public datasets like PlantVillage, you can include details about training methodology and datasets here. If using a custom dataset, explain that instead.

Contributing

Contributions are welcome! Feel free to:

Improve model accuracy.

Add more plant species.

Make the UI more responsive.

Optimize deployment – suggest platforms like Heroku, Docker, or AWS.

Please open an issue for major enhancements before submitting a pull request.

License

Include your project's license information here (e.g. MIT, Apache-2.0, etc.).

Short Description (One-Liner)

Plant Disease Detection: Deep learning-powered app for detecting plant diseases from leaf images—helping you save crops before it's too late!
