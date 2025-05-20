# HumanActivityRecognition-Using-hybrid-Approach

This project, Hybrid Approach to Recognize Human Activity,
 focuses on classifying human activities such as walking, sitting, 
standing, and jogging using sensor data from wearable devices. It uses a
 combination of deep learning and traditional machine learning 
techniques to improve activity recognition accuracy.


We used Long Short-Term Memory (LSTM)
 networks to handle the time-series nature of the sensor data, capturing
 patterns over time. In parallel, we applied machine learning algorithms
 like Random Forest and Support Vector Machine (SVM)
 on extracted features such as mean, standard deviation, and energy. 
These features were derived from accelerometer and gyroscope data 
collected from public datasets like UCI HAR and WISDM.


The outputs of both the 
LSTM and ML models were then combined using a hybrid fusion technique, 
such as majority voting or weighted averaging. This helped improve the 
model's overall performance by taking advantage of both sequence 
learning and feature-based classification.


The hybrid model achieved 
better accuracy and robustness compared to using either deep learning or
 machine learning alone. This approach can be applied in real-world 
scenarios such as fitness tracking, elderly care (fall detection), and 
smart health applications.
