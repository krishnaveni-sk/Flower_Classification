🪷 Flower Classification using CNN
📘 Project Overview

This project uses a Convolutional Neural Network (CNN) model to classify flower images into multiple categories.
It demonstrates image preprocessing, deep learning model design, training, and performance evaluation using TensorFlow and Keras in Google Colab.

🌸 Dataset Information

Dataset: [Flower Dataset (PlantVillage / Kaggle-based)]

Total Classes: 5 (Daisy, Dandelion, Rose, Sunflower, Tulip)

Total Images: ~4,000+

Split: 80% Training / 20% Validation

⚙️ Model & Training Details

Model Type: CNN (Sequential Model with Conv2D, MaxPooling, Flatten, Dense Layers)

Epochs: 10

Optimizer: Adam

Loss Function: Categorical Crossentropy

Libraries Used: TensorFlow, Keras, NumPy, Matplotlib, OpenCV

📊 Results
Metric	Value
Validation Accuracy	69.30%
Validation Loss	79.88%
Epochs	10
🖼️ Output

Below is an example output showing flower image prediction result:

📁 Project Structure                                                                                                                                                       
Flower-Classification/
│
├── categorical_CNN_model_flower_image.ipynb   # Main model code (Colab)                                                                                                    
├── flowers_split/                             # Dataset (Train/Validation folders)                                                                                  
├── screenshot.png                             # Model output screenshot                                                                                                 
├── README.md                                  # Project documentation                                                                                                 
└── LICENSE                                    # License file

🚀 Future Improvements

Increase dataset size for higher accuracy

Apply Data Augmentation and Dropout regularization

Tune hyperparameters and learning rate

Test with pre-trained models (VGG16, ResNet50)

👩‍💻 Author

Krishnaveni S
📧 krishnavenisubramanian552@gmail.com

🌐 GitHub
 | LinkedIn

🌼 “A flower does not think of competing with the flower next to it. It just blooms.” 🌼
