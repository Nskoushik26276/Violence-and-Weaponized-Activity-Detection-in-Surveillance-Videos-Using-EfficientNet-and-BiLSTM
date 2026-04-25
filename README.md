# Violence-and-Weaponized-Activity-Detection-in-Surveillance-Videos-Using-EfficientNet-and-BiLSTM
AI-based Smart Surveillance Violence Detection System that classifies uploaded videos as Normal, Violence, or Weaponized using EfficientNetB0 and deep learning. It provides test accuracy, confusion matrix, classification report, GradCAM heatmaps, confidence graphs, and XAI video outputs for transparent threat detection in smart city surveillance.
This project presents an AI-based Smart Surveillance Violence Detection System that automatically identifies suspicious activities in video footage and classifies them into three categories: Normal, Violence, and Weaponized scenes. The system is designed to support modern surveillance environments such as public places, campuses, transportation hubs, and smart cities by providing early threat detection and faster emergency response.

The model uses EfficientNetB0 as a deep learning feature extractor to analyze frames captured from uploaded videos. Multiple frames are sampled from each video and processed as a temporal sequence, allowing the system to understand motion patterns and scene context rather than relying on a single image. An ensemble prediction strategy is applied to improve classification stability and accuracy.

For performance evaluation, the project generates key metrics such as test accuracy, precision, recall, F1-score, confusion matrix, and classification report. These metrics help measure how effectively the model distinguishes between safe and dangerous situations.

A major highlight of the project is its Explainable AI (XAI) component. Using Grad-CAM, the system visualizes which regions of a frame influenced the model’s decision. It displays:

Prediction confidence heatmap
GradCAM heatmap
Original frame vs highlighted suspicious regions
XAI overlay video output
Class confidence bar graph

This makes the model transparent and easier to trust in real-world safety applications.

The system is implemented in Python, using libraries such as TensorFlow, OpenCV, NumPy, Matplotlib, Seaborn, and Scikit-learn, and is optimized to run in Google Colab.

Overall, this project combines computer vision, deep learning, and explainable AI to build an intelligent surveillance solution capable of detecting violence-related incidents with high accuracy while also providing visual justification for every prediction.
