# Animal Image Classification

## Overview
This project is an **image classification system** that identifies animals in a given image. It uses a **Convolutional Neural Network (CNN)** built with TensorFlow/Keras and a **Flask web application** for user interaction. The model is trained on a dataset of 15 animal classes and can predict the animal in an uploaded image.

---

## Features
- **Image Classification**: Predicts the animal in an uploaded image.
- **Flask Web App**: Allows users to upload images and view predictions.
- **Transfer Learning**: Uses MobileNet as the base model for better performance.
- **Data Augmentation**: Improves model generalization by augmenting training data.

---

## Dataset
The dataset contains 15 animal classes:
- Bear
- Bird
- Cat
- Cow
- Deer
- Dog
- Dolphin
- Elephant
- Giraffe
- Horse
- Kangaroo
- Lion
- Panda
- Tiger
- Zebra

Each class has images of size `224x224x3`.

---

## Requirements
To run this project, you need the following:
- Python 3.7 or higher
- TensorFlow 2.x
- Flask
- NumPy
- Pillow

Install the required libraries using:
```bash
pip install tensorflow flask numpy pillow
```

---

## Project Structure
```
project/
│
├── app.py                  # Flask application
├── templates/              # HTML templates
│   ├── index.html          # Home page
│   └── results.html        # Results page
├── uploads/                # Temporary storage for uploaded images
├── dataset/                # Dataset folder (not included in the repo)
│   ├── bear/               # Images of bears
│   ├── cat/                # Images of cats
│   └── ...                 # Other animal folders
├── animal_classification_final_model.keras  # Trained model
└── README.md               # Project documentation
```

---

## How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/animal-image-classification.git
cd animal-image-classification
```

### 2. Prepare the Dataset
- Place your dataset in the `dataset` folder.
- Ensure the dataset has the correct folder structure (see **Dataset** section).

### 3. Train the Model (Optional)
If you want to retrain the model, run:
```bash
python app.py
```
The trained model will be saved as `animal_classification_final_model.keras`.

### 4. Run the Flask App
Start the Flask application:
```bash
python app.py
```
Open your browser and go to `http://127.0.0.1:5000/`.

### 5. Upload an Image
- On the home page, upload an image of an animal.
- The app will predict the animal and display the result.

---

## Deployment
To deploy the app to a cloud platform like **Heroku**:
1. Install the Heroku CLI and log in:
   ```bash
   heroku login
   ```
2. Create a `Procfile` in your project directory:
   ```
   web: python app.py
   ```
3. Commit your code to a Git repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```
4. Create a Heroku app:
   ```bash
   heroku create
   ```
5. Deploy your app:
   ```bash
   git push heroku main
   ```

---

## Screenshots
### Home Page
![Home Page](![Screenshot 2025-03-02 130550](https://github.com/user-attachments/assets/5ef76e55-c2b7-4141-b7a6-b6000f63e14b))
)

### Results Page
![Results Page](![Screenshot 2025-03-02 130617](https://github.com/user-attachments/assets/14fa2a7e-6109-4efe-97f6-a44736a3084c))
)

---

## Future Improvements
- Add more animal classes to the dataset.
- Fine-tune the model for better accuracy.
- Improve the user interface using a front-end framework like Bootstrap.
- Deploy the app to a cloud platform for public access.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- **TensorFlow/Keras** for the deep learning framework.
- **Flask** for the web application framework.
- **MobileNet** for the pre-trained model used in transfer learning.

---

## Contact
For questions or feedback, feel free to reach out:
- **Name**: Peddapati Santhi Raju
- **Email**: santhinani364@gmail.com
- **GitHub**: SanthiNani (https://github.com/SanthiNani)

---

Enjoy using the **Animal Image Classification** system! 🚀

---
