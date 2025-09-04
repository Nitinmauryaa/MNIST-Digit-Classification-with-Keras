# 🧠 MNIST Digit Classification with Keras

A Python notebook demonstrating a multi-layer neural network for handwritten digit classification using the MNIST dataset and Keras. It covers data preprocessing, model training, evaluation, and prediction.

---

## 🚀 Features

- 📥 Loads and visualizes the MNIST image dataset  
- 🧹 Preprocesses data for model input  
- 🏗️ Builds a multi-layer neural network using Keras  
- 🏋️‍♂️ Trains the model and tracks performance  
- 📊 Evaluates accuracy on unseen test data  
- 📈 Plots training and validation metrics  
- 🖼️ Interactive single-image prediction  

---

## 🛠️ Installation

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/MNIST-Digit-Classification-with-Keras.git
cd MNIST-Digit-Classification-with-Keras
pip install tensorflow scikit-learn matplotlib
📓 Usage

Open the MNIST-Digit-Classification-with-Keras.ipynb notebook in Jupyter Notebook or Google Colab.

Run the cells step-by-step:

🔍 Visualize input images and preprocessing with built-in matplotlib plots.

⚙️ Modify model architecture: number of layers, neurons, activation functions.

🚀 Train the model and monitor training/validation loss and accuracy.

🔮 Make predictions.

🔢 Example: Predict a test image
model.predict(X_test[10].reshape(1, 28, 28)).argmax(axis=1)

✍️ Try predicting your own handwritten digits!
✅ Results

Achieves ~97.3% accuracy on MNIST test set

Clear and informative plots showing loss and accuracy trends

Easy-to-modify architecture for experimentation

📁 Project Structure
MNIST-Digit-Classification-with-Keras/
│
├── MNIST-Digit-Classification-with-Keras.ipynb   # Main Jupyter notebook
├── README.md                                     # Project documentation

🤝 Contributing

Contributions are welcome!
Feel free to fork the repo, open issues, or submit PRs to:

Improve model performance

Add features (e.g., hyperparameter tuning, CNN layers, etc.)

📄 License

This project is open-sourced for educational purposes.
