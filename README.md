# 🖊️ Handwritten Digit Recognition using CNN

This project implements a **handwritten digit recognition system** using a **Convolutional Neural Network (CNN)** trained on the **MNIST dataset**. The model can classify digits (0-9) and is integrated with a **GUI for drawing digits** using Tkinter.

---
## 🚀 Features
✅ Draw a digit on the canvas and predict its value.  
✅ Displays **top prediction** with confidence percentage.  
✅ Uses a **pre-trained CNN model** for high accuracy.  
✅ Supports **real-time digit recognition** using OpenCV (optional).  
✅ Simple GUI using **Tkinter**.


---
## 🛠️ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Handwritten-Digit-Recognition.git
cd Handwritten-Digit-Recognition
```

### 2️⃣ Install Dependencies
Install required libraries using:
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the GUI
Run the Tkinter-based digit recognition GUI:
```bash
python src/digit_gui.py
```

---
## 📊 Model Training (Optional)
If you want to **retrain the model**, use the Jupyter Notebook:
```bash
jupyter notebook
# Open 'notebook/digit_recognition.ipynb' and run all cells.
```

---
## 🖥️ How It Works
1️⃣ Draw a digit on the canvas.
2️⃣ Click the **'Predict'** button.
3️⃣ The model predicts the digit and displays the **confidence score**.
4️⃣ Click **'Clear'** to redraw and try again!

---
## 🔥 Future Enhancements
🔹 Deploy as a **web app** using Flask or Streamlit.  
🔹 Add **image preprocessing** to improve recognition accuracy.  
🔹 Support **handwritten letters** using the EMNIST dataset.  
🔹 Implement **speech output** using `pyttsx3`.

---
## 🤝 Contributing
Feel free to fork the repository, make improvements, and submit pull requests. 😊

---
## 📜 License
This project is licensed under the **MIT License**.

---
## ✨ Acknowledgments
🔹 **MNIST Dataset** - Used for training the model.  
🔹 **TensorFlow & Keras** - For implementing the CNN.  
🔹 **Tkinter** - For building the GUI interface.  

📢 **If you found this project useful, give it a ⭐ on GitHub!** 😊

