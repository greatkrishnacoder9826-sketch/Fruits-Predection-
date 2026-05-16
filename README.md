🍎 Fruits Classification using SVM Machine Learning

A Machine Learning project that classifies different types of fruits using the Support Vector Machine (SVM) algorithm and image processing techniques.

📌 Project Overview

This project uses Computer Vision and Machine Learning to identify fruits from images.
The model is trained on fruit images and predicts the fruit category with high accuracy.

The project includes:

Image preprocessing
Data resizing and flattening
Model training using SVM
Hyperparameter tuning using GridSearchCV
Prediction on new fruit images
Accuracy evaluation
🚀 Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
scikit-image (skimage)
🍓 Fruit Categories

The model can classify:

Apple 🍎
Banana 🍌
Grape 🍇
Mango 🥭
Strawberry 🍓
🧠 Machine Learning Algorithm

This project uses:

Support Vector Machine (SVM)

SVM is a supervised machine learning algorithm used for classification tasks.
It works by finding the optimal boundary between different classes.

📂 Project Workflow
1️⃣ Image Loading

Images are loaded from dataset folders.

Category = ['Apple','Banana','Grape','Mango','Strawberry']
2️⃣ Image Preprocessing

Each image is:

Resized to 150 x 150
Converted into array format
Flattened into 1D vector
img_resize = resize(img, (150,150,3))
3️⃣ DataFrame Creation

The processed image data is stored inside a Pandas DataFrame.

4️⃣ Train-Test Split

Dataset is divided into:

Training Data
Testing Data
train_test_split()
5️⃣ Hyperparameter Tuning

GridSearchCV is used to find the best SVM parameters.

GridSearchCV()
6️⃣ Model Training

The SVM model is trained on image data.

model.fit(x_train, y_train)
7️⃣ Prediction

The trained model predicts fruit categories for new images.

8️⃣ Accuracy Evaluation

Model accuracy is calculated using:

accuracy_score()
📊 Features

✅ Fruit image classification
✅ SVM-based prediction
✅ Image preprocessing
✅ Hyperparameter tuning
✅ High accuracy model
✅ Easy to understand beginner project

📁 Project Structure
📦 Fruits-Classification-SVM
 ┣ 📜 Fruits_Classification.ipynb
 ┣ 📂 Dataset
 ┣ 📜 README.md
▶️ How to Run the Project
Step 1 — Clone Repository
git clone https://github.com/your-username/your-repository-name.git
Step 2 — Install Libraries
pip install numpy pandas matplotlib scikit-learn scikit-image
Step 3 — Open Jupyter Notebook
jupyter notebook
Step 4 — Run the Notebook

Run all cells step by step.

📈 Model Performance

The model is trained using optimized SVM parameters and achieves good classification accuracy on test data.

🎯 Future Improvements
Add more fruit categories
Improve dataset quality
Use Deep Learning (CNN)
Build a web app using Flask or Streamlit
Deploy the model online
🤝 Contributing

Contributions are welcome!

If you want to improve this project:

Fork the repository
Create a new branch
Commit changes
Open a pull request
📜 License

This project is open-source and available under the MIT License.

👨‍💻 Author

Krishna Great 

Made with ❤️ using Python and Machine Learning.
