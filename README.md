
# **MyProject-SCD**

This is a **Chatbot Project** created for the GitHub assignment. It demonstrates how to train a chatbot using intents and provides an interactive GUI for chatting.

---

## **Table of Contents**
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Project Structure](#project-structure)
4. [How to Use](#how-to-use)
5. [Screenshots](#screenshots)
6. [Author](#author)

---

## **Features**
| Feature                  | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| **Train Chatbot**        | Train the chatbot using a custom dataset of intents.                       |
| **Model Persistence**    | Save and load trained models for future use.                               |
| **Interactive GUI**      | Chat with the bot using a user-friendly graphical interface.               |
| **Custom Intents**       | Easily customize the bot's responses by modifying the `intents.json` file. |
| **Real-Time Interaction**| Chat responses are generated instantly during the conversation.            |

---

## **Technologies Used**
- **Programming Language**: Python
- **Libraries**:
  - TensorFlow/Keras: For training the chatbot model.
  - NLTK: For natural language processing tasks.
  - Tkinter: For creating the graphical user interface.
- **Data Format**: JSON (for storing intents and responses)

---

## **Project Structure**
| File/Folder        | Description                                       |
|--------------------|---------------------------------------------------|
| `train_chatbot.py` | Script to train the chatbot using intents.        |
| `chatbot_model.h5` | Saved model after training.                       |
| `intents.json`     | JSON file containing intents and responses.       |
| `chatgui.py`       | Script for launching the chatbot GUI.             |
| `classes.pkl`      | Serialized file for storing class labels.         |
| `words.pkl`        | Serialized file for storing processed vocabulary. |

---

## **How to Use**

### **1. Clone the Repository**
```bash
git clone https://github.com/tayyaba234/MyProject-SCD.git
cd MyProject-SCD
```

### **2. Install Dependencies**
Ensure you have Python installed. Then, install the required libraries:
```bash
pip install tensorflow nltk
```

### **3. Train the Chatbot**
Run the training script to train the chatbot model:
```bash
python train_chatbot.py
```

### **4. Launch the Chatbot GUI**
Start the chatbot interface to interact with the bot:
```bash
python chatgui.py
```

---

## **Screenshots**

### **Training the Chatbot**
![Training Screenshot](https://via.placeholder.com/800x400?text=Training+Chatbot)

### **Chatbot GUI**
![Chatbot GUI Screenshot](https://via.placeholder.com/800x400?text=Chatbot+GUI)

---

## **Future Enhancements**
- Add support for multiple languages.
- Integrate with voice assistants for speech-to-text and text-to-speech capabilities.
- Deploy the chatbot as a web application using Flask or Django.
- Add a database for storing chat history.

---

## **Author**
**Tayyaba Anwer**  
[GitHub Profile](https://github.com/tayyaba234)

---
