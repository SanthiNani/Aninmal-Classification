🐾 Animal Image Classification
This project classifies animals using deep learning and a Flask web app. It leverages MobileNet for feature extraction and fine-tunes it on a dataset of 15 animal classes.

📌 Features
- Deep Learning Model: MobileNet-based CNN trained with image augmentation.
- Web Interface: Upload images to classify animals via a Flask app.
- Real-time Predictions: Get instant predictions on uploaded images.

🚀 Setup
- 1️⃣ Install Dependencies
- pip install -r requirements.txt

2️⃣ Train the Model (Optional)
- python app.py
- (Model will be trained and saved automatically.)

3️⃣ Run Flask App
- python app.py
- Visit http://127.0.0.1:5000 in your browser.

🖼️ Screenshots

- Upload Image -![Screenshot 2025-03-02 130550](https://github.com/user-attachments/assets/5ef76e55-c2b7-4141-b7a6-b6000f63e14b)

- Prediction Output - ![Screenshot 2025-03-02 130617](https://github.com/user-attachments/assets/14fa2a7e-6109-4efe-97f6-a44736a3084c)

📜 Dataset

- 15 Animal Classes
- Images resized to 224×224×3
- Data Augmentation applied

📌 Future Work

- Improve accuracy with model tuning
- Deploy as a cloud-based API
