# QR-Code Based Lightweight Neural Network (ML) Project

This project is part of my hands-on learning journey through the LinkedIn Learning + Wolfram Research Machine Learning Certificate demonstrating that machine learning can be accomplished using minimal resources.

🎯 **Objective**  
Develop a lightweight neural network model for image classification using programmatically generated QR codes. Each QR code encodes a single numeric character.

🚀 **For Beginners: How This Project Helps You**  
If you're new to ML, this repo shows you:
- How to work in JupyterLab on a Chromebook or other low-powered device  
- How to generate custom datasets with programmatically created QR codes  
- How to design and train lightweight CNN models for image classification  
- How to manage computational resources effectively in constrained environments  

🧠 **Models Used**  
- **Custom Lightweight Convolutional Neural Network (CNN)** – Optimized for fast training and minimal computational requirements on small QR code images

🧰 **Tools & Technologies**  
- **JupyterLab** (web-based environment)  
- **Python 3**  
- NumPy, and OpenCV/Pillow for image processing

📊 **Dataset**  
- **Source:** Programmatically generated QR codes  
- **Features:** Each image encodes a single numeric character  
- **Target:** Corresponding character label  
- **Constraints:** Entire dataset size is kept under 25 MB for optimal resource efficiency

⚙️ **ML Workflow** 

**Part I: Data Generation & Preprocessing**  
   - Programmatically generate QR codes with minimal file sizes  
   - Resize and normalize images as necessary  
   - Split data into training and validation sets

**Part II: Model Training** (Comming Soon!)
   - Design a lightweight CNN architecture tailored for QR code image classification
   - Train the model on the generated dataset

**Part III: Model Evaluation**  
   - Assess performance using metrics such as accuracy and loss  
   - Fine-tune hyperparameters to optimize results

**Part IV: Inference Example** (Comming Soon!)
  
📁 **Project Structure**  
```
├── notebooks/       - Jupyter notebooks for training and evaluation
├── data/            - Generated QR code images and corresponding labels
├── README.md        - This file
└── requirements.txt - Python dependencies
```

✅ **Next Steps**  
- Enhance the CNN architecture with additional layers and regularization techniques  
- Integrate secure messaging features using modular QR code encoding  
- Explore transfer learning for further performance improvements  
- Add interactive demos via Binder for a one-click launch in a free cloud-based Jupyter environment

💬 **Final Note**  
This repository is meant to prove that you don't need powerful hardware or paid services to dive into machine learning. If you have access to a browser, you have access to ML. Let's build together and empower learners everywhere! ✊🏾💻🧠
