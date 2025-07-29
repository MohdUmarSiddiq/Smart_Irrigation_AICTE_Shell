# 💧 Smart Sprinkler Irrigation System

A machine learning–powered web application for predicting sprinkler status based on sensor data. This system uses a trained model to optimize irrigation across multiple agricultural parcels by determining whether sprinklers should be ON or OFF.

---

## 📂 Project Structure

├── **app.py**                                   # Streamlit app for sprinkler prediction  
├── **Irrigation_System.ipynb**                  # Notebook for model development and training  
├── **Farm_Irrigation_System.pkl**               # Trained machine learning model (saved using joblib)  
├── **Irrigation_Machine.csv**                   # Dataset used for training and evaluation  


---

## 🚀 How It Works

- The system takes in **20 scaled sensor values**  as inputs.
- Based on these values, the model predicts whether each sprinkler (parcel-wise) should be **ON or OFF**.
- The application is built using **Streamlit** for a simple and interactive browser interface.

---

## 🧪 Technologies Used

- Python 🐍
- Streamlit
- Scikit-learn
- NumPy
- Jupyter Notebook
- joblib

---

## 🖥️ Running the App Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. **Install required packages**  
  Run the jupyter notebook in your environment

3. **Run the Streamlit app**
  ```bash
  streamlit run app.py
  ```
4. **Access the app**  
Visit http://localhost:8501 in your web browser.

## 📊 Dataset
File: Irrigation_Machine.csv  
Contains sensor readings used to train the irrigation system model.

## 🧠 Model
The trained model (Farm_Irrigation_System.pkl) is loaded in app.py.  
It predicts a binary output (0 = OFF, 1 = ON) for each sprinkler.

## 📓 Jupyter Notebook
Irrigation_System.ipynb contains:
- Data preprocessing
- Model training and evaluation
- Saving the trained model
