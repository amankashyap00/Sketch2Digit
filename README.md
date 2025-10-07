# 🖊️ Handwritten Digit Recognition (0–9)

A deep learning project that recognizes handwritten digits using Convolutional Neural Networks (CNNs), trained and tested on the classic MNIST dataset.


## 📊 Dataset
	•	Source: MNIST (Modified National Institute of Standards and Technology)
	•	Training samples: 60,000
	•	Testing samples: 10,000
	•	Image details:
	•	Size: 28 × 28 pixels
	•	Format: Grayscale (1 channel)
	•	Pixel values: 0–255 (normalized before training)


## 🏗️ CNN Model Design

The model follows a simple yet effective architecture:
	1.	Input Layer → accepts images of shape (28, 28, 1)
	2.	Convolution + ReLU → 32 filters, kernel (3×3)
	3.	MaxPooling → pool size (2×2)
	4.	Convolution + ReLU → 64 filters, kernel (3×3)
	5.	MaxPooling → pool size (2×2)
	6.	Flatten → convert feature maps to 1D
	7.	Dense Layer → 128 neurons, ReLU activation
	8.	Output Layer → 10 neurons, Softmax activation (digits 0–9)


## 📈 Model Performance
![1](https://user-images.githubusercontent.com/97530517/232014919-390ab15f-67e6-4a63-bef3-9005d795135f.PNG)

The trained CNN achieves high accuracy on MNIST.
## 🚀 Deployment with Streamlit

The model is wrapped with a Streamlit app that allows interactive digit recognition:
	1.	✍️ Draw a digit → Use mouse/touchpad on canvas
	2.	🤖 Prediction → The CNN model predicts the digit in real-time
	3.	📊 Result → The app displays the predicted digit instantly

[Link to Streamlit Application](https://aman-kashyap-Sketch2Digit.streamlit.app/)
## Sample Output
![full](https://user-images.githubusercontent.com/97530517/232018256-94749378-9d7b-4b33-a0a9-376bd2862392.PNG)
![image (1)](https://user-images.githubusercontent.com/97530517/232014753-7cd8a16c-1b42-4a5c-b67b-27998331ef8e.png)
# digit# Digit_recognition
