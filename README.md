# fake-profile-detection-across-online-social-network-using-neural-network
Fake Profile Detection using CNN is a deep learning project that identifies fake accounts across online social networks. By leveraging convolutional neural networks on user data and activity patterns, it classifies profiles as genuine or fake, enhancing trust and security online.

This project implements a *Tkinter-based GUI application* to detect fake profiles in online social networks using an *Artificial Neural Network (ANN). It allows users to upload datasets, preprocess them, train a deep learning model, visualize accuracy/loss, and predict whether profiles are *genuine or fake.  

## 🔹 Features
- Upload and preprocess social network profile datasets  
- Train an ANN model (built with Keras/TensorFlow)  
- View accuracy and loss trends through a graph  
- Predict whether new profiles are *Fake* or *Genuine*  
- User-friendly GUI built with *Tkinter*  

## 🔹 Tech Stack
- *Python 3*  
- *Tkinter* (GUI)  
- *Keras / TensorFlow* (Deep Learning)  
- *Scikit-learn* (Preprocessing & Train-Test Split)  
- *Matplotlib* (Graphs & Visualization)  
- *Pandas / NumPy* (Data Handling)  

## 🔹 How It Works
1. *Upload Dataset* – Load CSV file of profile data (with features and labels).  
2. *Preprocess Data* – Splits data into train and test sets, one-hot encodes labels.  
3. *Train ANN* – Builds and trains a neural network with 2 hidden layers.  
4. *Visualize Performance* – Plots accuracy and loss over training iterations.  
5. *Predict Profiles* – Classifies new profile data as Fake or Genuine.  

## 🔹 Steps to Run
1. Clone this repository:
   bash
   git clone https://github.com/your-username/fake-profile-detection-ann.git
Perfect 👍 You’ve built a Tkinter GUI project for detecting fake profiles using an Artificial Neural Network (ANN) with Keras. Below is a detailed README.md tailored for your project:


---

# Fake Profile Detection Across Online Social Networks using ANN

This project implements a **Tkinter-based GUI application** to detect fake profiles in online social networks using an **Artificial Neural Network (ANN)**. It allows users to upload datasets, preprocess them, train a deep learning model, visualize accuracy/loss, and predict whether profiles are *genuine* or *fake*.  

## 🔹 Features
- Upload and preprocess social network profile datasets  
- Train an ANN model (built with Keras/TensorFlow)  
- View accuracy and loss trends through a graph  
- Predict whether new profiles are **Fake** or **Genuine**  
- User-friendly GUI built with **Tkinter**  

## 🔹 Tech Stack
- **Python 3**  
- **Tkinter** (GUI)  
- **Keras / TensorFlow** (Deep Learning)  
- **Scikit-learn** (Preprocessing & Train-Test Split)  
- **Matplotlib** (Graphs & Visualization)  
- **Pandas / NumPy** (Data Handling)  

## 🔹 How It Works
1. **Upload Dataset** – Load CSV file of profile data (with features and labels).  
2. **Preprocess Data** – Splits data into train and test sets, one-hot encodes labels.  
3. **Train ANN** – Builds and trains a neural network with 2 hidden layers.  
4. **Visualize Performance** – Plots accuracy and loss over training iterations.  
5. **Predict Profiles** – Classifies new profile data as *Fake* or *Genuine*.  

## 🔹 Steps to Run
1. Clone this repository:
   bash
   git clone https://github.com/your-username/fake-profile-detection-ann.git

2. Install dependencies:

pip install -r requirements.txt


3. Run the application:

python app.py

(Replace app.py with your actual filename if different.)



🔹 Dataset

The dataset should be in CSV format with 8 feature columns and 1 label column (0 = Genuine, 1 = Fake).

Place dataset files inside a folder named Dataset/ for easier access.


🔹 Example Output

Training Accuracy and Loss Curve shown in Matplotlib.

Profile Predictions displayed in Tkinter text area (e.g., Given Account Details Predicted As Fake).


🔹 Screenshots

(Add screenshots of your Tkinter app UI and graph here if available)

🔹 Applications

Fake account detection in online social networks

Spam and bot detection

Preventing misinformation and fraud



---

✨ Contributions are welcome – Feel free to fork this repo, raise issues, or submit pull requests.

