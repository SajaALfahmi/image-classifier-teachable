# Image Classifier with Teachable Machine

This project is a simple image classifier trained using [Teachable Machine](https://teachablemachine.withgoogle.com/).  
It can recognize two animals: **Horse 🐴** and **Cheetah 🐆**.

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `converted_keras.zip` | Full exported model from Teachable Machine |
| `keras_model.h5` | Trained model in TensorFlow / Keras format |
| `labels.txt` | Class labels (Horse, Cheetah) |
| `test_pic.py` | Python script to load and test an image |
| `horse1.jpeg` | Test image used in prediction |
| `output-2.jpeg` | Screenshot showing prediction result |
| `cheetah_test_in_teachable.jpeg` | Cheetah training/testing sample from Teachable Machine |
| `horse_test_in_teachable.jpeg` | Horse training/testing sample from Teachable Machine |

---

## 🚀 How to Use

> Make sure you have Python and TensorFlow 2.12.1 installed.

1. Put the following files in the same directory:
   - `keras_model.h5`
   - `labels.txt`
   - `horse1.jpeg`

2. Run the script:

```bash
python test_pic.py
It will:

Load the model
Read the test image
Predict its class (Horse or Cheetah)
Print the confidence score
Display the image with the prediction

Sample Output

Prediction result from horse1.jpeg:



🧠 Model Details

Trained with Teachable Machine by Google
Image size: 224x224
Exported in Keras format (.h5)
Two classes:
Horse
Cheetah
💡 Notes

Make sure you are using TensorFlow 2.12.1 to avoid version compatibility issues.
You can install it using:
pip install tensorflow==2.12.1
This project is best tested in Google Colab or a local Python environment.
👩‍💻 Created By

Saja Al-Fahmi
This classifier was created as part of a machine learning task using Teachable Machine.
