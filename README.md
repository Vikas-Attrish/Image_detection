# Image Detection using CNN on CIFAR-10 Dataset

This project implements an image detection system using a Convolutional Neural Network (CNN) on the CIFAR-10 dataset. The model is built and trained using TensorFlow and Keras.

## 📊 Dataset
- **CIFAR-10**: A dataset of 60,000 32x32 color images in 10 classes, with 6,000 images per class.
- **Classes**: Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck.

## 📋 Project Structure
```
├── image_detection_.ipynb   # CNN Model and Training Code (Jupyter Notebook)
├── README.md               # Project Documentation
└── requirements.txt        # Dependencies
```

## 🧰 Requirements
Ensure you have Python installed and install dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies (in `requirements.txt`)
```
tensorflow
matplotlib
numpy
```

## 🚀 How to Run
1. Clone the repository:

```bash
git clone https://github.com/Vikas-Attrish/Image_detection.git
cd Image_detection
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook image_detection_.ipynb
```

Ensure you have Jupyter Notebook installed. If not, install it using:

```bash
pip install notebook
```

## 📈 Model Summary
- **Architecture**:
  - 2 Convolutional Layers
  - 2 MaxPooling Layers
  - Flatten Layer
  - Dense Layer (128 neurons, ReLU activation)
  - Output Layer (10 neurons, Softmax activation)

## 📊 Output
- Prints training and validation accuracy during training.
- Evaluates model accuracy on test data.
- Visualizes predictions on sample images.

## 📷 Sample Output
Example of predicted vs. true labels:

```
Pred: Airplane, True: Airplane
Pred: Dog, True: Dog
```

## 📌 Future Improvements
- Implement data augmentation
- Apply transfer learning for better accuracy
- Optimize hyperparameters

## 🤝 Contributing
Feel free to submit issues or pull requests!

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).


