🩺 Diabetic Retinopathy & Glaucoma Detection Using VGG16 (Deep Learning Project)

This project is an AI-powered retinal disease diagnosis system that automatically detects Diabetic Retinopathy (DR) and Glaucoma from retinal fundus images using deep learning.
Built using Python, TensorFlow, Keras, and OpenCV, the model utilizes the VGG16 architecture to classify disease severity into multiple levels with high accuracy.


---

⭐ Features

🔍 Multi-Level Diabetic Retinopathy Detection

Predicts five DR classes:

0 — NoDR

1 — Mild

2 — Moderate

3 — Severe

4 — Proliferative DR


👁 Glaucoma Detection

Using dark-object detection and optic-disc analysis.

🚀 Real-Time Prediction

A Tkinter GUI allows users to:

Upload images

Train the model

Test new retina images

View classification and prescription suggestions


🔧 Image Preprocessing

Includes:

Noise removal

Contrast enhancement

Dark-object detection

Grayscale conversion

Normalization

Image resizing


🧠 Deep Learning Model

VGG16 with transfer learning

Fine-tuned for medical image classification

Softmax output for 5-class DR grading



---

📊 Model Performance

Metric	Score

Accuracy	~98%
Precision / Recall / F1	High across all DR stages
Confusion Matrix	Strong performance on all classes


The model produces:

Accuracy graph

Loss graph

Confusion matrix heatmap

Full classification report



---

🗂 Project Structure

📁 Diabetic-Retinopathy-Detection/
│
├── Data/
│   ├── Train/
│   ├── Test/
│
├── Model/
│   └── diabetic.h5
│
├── Output/
│   └── Out/
│
├── src/
│   ├── gui.py
│   ├── training.py
│   ├── testing.py
│   ├── preprocessing.py
│   ├── model_build.py
│   └── utils.py
│
├── README.md
└── requirements.txt


---

💻 Technologies Used

Languages

Python


Libraries

TensorFlow

Keras

OpenCV

NumPy

Matplotlib

Seaborn

Pillow

Tkinter


Tools

PyCharm / VS Code

GPU acceleration (optional)



---

🏗 Installation

1. Clone the repository



git clone https://github.com/your-username/diabetic-retina-detection.git
cd diabetic-retina-detection

2. Install dependencies



pip install -r requirements.txt

3. Prepare the Dataset Place your dataset inside:



Data/Train/
Data/Test/

Follow the folder naming:

0NoDR
1Mild
2Moderate
3Severe
4ProliferativeDR

4. Run the GUI Application



python gui.py


---

🧪 Training the Model

To retrain the model from scratch:

python training.py

The model will be saved as:

Model/diabetic.h5


---

🖼 Testing a Single Image

python testing.py

Upload a fundus image to view:

DR class prediction

Glaucoma indication

Prescription suggestion



---

📌 Use Cases

Medical imaging research

Automated screening in clinics

Final-year engineering projects

Telemedicine DR detection

Ophthalmology AI tools

Dataset benchmarking



---

🔮 Future Enhancements

OCT (3D retina) support

Explainable AI (Grad-CAM++)

Multi-disease detection (macular edema, cataract)

Mobile or web-based deployment

EHR system integration

GAN-based image enhancement



---

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open a pull request or raise an issue.




---

❤️ Acknowledgements

Kaggle EyePACS Dataset

DRIVE / Messidor datasets

Research works on DR detection

TensorFlow & Keras open-source community
