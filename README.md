# Deep CNN-LSTM With Self-Attention Model for Human Activity Recognition Using Wearable Sensor

Human activity recognition is a complex problem that aims to predict user activities based on their device interactions, which has numerous applications in people's daily lives. Two main methods are currently used to detect human activity: video image recognition and wearable sensors. Wearable activity detectors are widely used in various healthcare applications for tracking fitness activities, but the effectiveness of these methods remains unknown. Therefore, researchers are working to enhance the contribution of inertial sensors for human activity recognition (HAR). 
To address this issue, this paper proposes a novel deep learning model, combining convolutional neural networks (CNNs) and long short-term memory (LSTM) networks with self-attention, for human activity recognition using wearable sensors. The proposed model is specifically designed to recognize activities such as standing/sitting, regular walking, running, and jogging, using data collected from smartphone sensors. 
The proposed model is evaluated using a publicly available dataset, MHEALTH, and achieves remarkable accuracy in recognizing human activities, with an accuracy rate of 99.6%. The model extracts features from time-series sensor data using CNNs and LSTMs and enhances the predictive capabilities of the system with a self-attention mechanism. 
Overall, the paper presents a novel approach to human activity recognition using wearable sensors and deep learning techniques. The proposed model accurately recognizes human activities and has potential applications in clinical settings. The paper's findings provide a solid foundation for further research to improve human activity recognition systems' accuracy and efficacy.


<p align="center">
<br><img src="https://user-images.githubusercontent.com/72060359/236917257-eb152c09-d242-4c1a-91f4-02c7c5b97baa.png"><br><br>
<b>Train: 99.96%, Test: 99.61%</b><br>
Best model: Accuracy on various runs
</p>

## Results and Conclusion:
The model was trained on the MHealth dataset, achieving near-perfect accuracy on the test set. Precision, recall, and F1 scores were calculated for each activity class, indicating good performance across all classes. Experiments were conducted to assess the accuracy of detecting activity classes using only one pair of sensors, either from the ankle or lower arm. Results showed that using sensors from the arm yielded an accuracy of 90% while using sensors from the ankle yielded an accuracy of 75%. However, combining both pairs of sensors significantly improved accuracy, highlighting the benefits of using multiple pairs of sensors in activity classification. 

In conclusion, we have developed a model using accelerometer and gyroscope data from the left ankle and right lower arm to classify human activities. The model uses a combination of convolutional neural networks (CNNs), long short-term memory (LSTM) networks, and self-attention mechanisms to extract and capture both spatial and temporal features in the data. Our model achieved high accuracy on the test set, demonstrating its effectiveness in classifying human activities. These findings indicate potential applications in healthcare, fitness tracking, and sports analysis. Future work may focus on deploying this model on a smartphone to predict activity classes in real time. Overall, this study demonstrates the potential of machine learning techniques for accurately classifying human activities, which has significant implications across various fields.
