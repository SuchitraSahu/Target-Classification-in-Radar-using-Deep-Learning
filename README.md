# Target-Classification-in-Radar-using-Deep-Learning
"Target Classification in Radar using deep learning" is a project that aims to leverage the capabilities of deep learning algorithms to classify and identify targets detected by radar systems. Radar is a technology used for detecting and tracking objects by emitting radio waves and analyzing the reflected signals. The project focuses on developing a deep learning model, typically implemented using frameworks like TensorFlow or PyTorch, to process the radar data and accurately classify the detected targets into different categories, such as vehicles, man, group of men, or other relevant classes. By utilizing deep learning, the project aims to improve the accuracy and efficiency of target classification in radar systems, which can have significant applications in various fields, including surveillance, autonomous vehicles, aerospace, and defence.
<img width="484" alt="image" src="https://github.com/SuchitraSahu/Target-Classification-in-Radar-using-Deep-Learning/assets/95865235/b2c53ce9-66ef-4cab-99cd-5a365a9cc319">

The spectrograms:
![image](https://github.com/SuchitraSahu/Target-Classification-in-Radar-using-Deep-Learning/assets/95865235/1bffdba7-ce3d-4548-b05f-7f14f226008b)
The energy vs sampling rate graphs and spectrograms of a few audio signals.
<img width="231" alt="image" src="https://github.com/SuchitraSahu/Target-Classification-in-Radar-using-Deep-Learning/assets/95865235/7d684981-5c47-44ba-9f34-b0a0807fa26e">
<img width="489" alt="image" src="https://github.com/SuchitraSahu/Target-Classification-in-Radar-using-Deep-Learning/assets/95865235/33fda50b-1047-44fe-b7e7-3d18f586e74e">
<img width="518" alt="image" src="https://github.com/SuchitraSahu/Target-Classification-in-Radar-using-Deep-Learning/assets/95865235/c4ce01da-d7f2-49d1-938f-1623ef319029">
<img width="470" alt="image" src="https://github.com/SuchitraSahu/Target-Classification-in-Radar-using-Deep-Learning/assets/95865235/c54dbf64-6cfe-4bb0-89d2-bac1fcf601f6">
<img width="483" alt="image" src="https://github.com/SuchitraSahu/Target-Classification-in-Radar-using-Deep-Learning/assets/95865235/b59e3463-f243-4963-84ce-3829100b59d8">

Why not YOLO or R-CNN?
Misalignment between Input and Object Detection: YOLO and R-CNN are designed for object detection in images, not audio spectrograms, leading to suboptimal performance and difficulty capturing audio features.
Lack of Spatial Information: YOLO and R-CNN rely on spatial information in images, while spectrograms lack inherent spatial dimensions, making it challenging to capture temporal patterns in audio signals.
Complex Feature Representation: Spectrograms contain intricate audio features, which may be difficult for YOLO and R-CNN to effectively capture and interpret due to their image-based design.
Computational Overhead: YOLO and R-CNN are computationally intensive, requiring significant resources for training and inference, making them slower and more computationally expensive for audio classification using spectrograms.
Why no fuzzification is done?
Fuzzification, which converts crisp inputs into fuzzy sets, may not be directly applicable in target classification using deep learning for radar. Deep learning models, such as CNNs, operate on numerical data rather than fuzzy sets, and their effectiveness is primarily optimized through architecture, training, and data preparation techniques. 

Summary :
The main objective of the project is to impose an algorithm onto a machine that can detect the type of target and its distance from the radar accurately as compared to traditional manual methods.
For this purpose, we are using a CNN model because it has a history of easily analysing complex data patterns and extracting meaningful features. 
We trained the model using CNN.
We made a pop-up feature into the code for predicting the input given in.
The training set we used is limited. It can be further improvised with a better and bigger training set.

Refrences:
https://www.kaggle.com/code/christianlillelund/classify-mnist-audio-using-spectrograms-keras-cnn#Convert-audio-files-to-spectograms
https://www.kdnuggets.com/2020/02/audio-data-analysis-deep-learning-python-part-2.html
https://medium.com/x8-the-ai-community/audio-classification-using-cnn-coding-example-f9cbd272269e
https://ieeexplore.ieee.org/document/8995448
https://realpython.com/working-with-files-in-python/#copying-moving-and-renaming-files-and-directories
https://pythongeeks.org/audio-analysis-using-deep-learning/
https://towardsdatascience.com/cnns-for-audio-classification-6244954665ab
https://towardsdatascience.com/audio-deep-learning-made-simple-sound-classification-step-by-step-cebc936bbe5
https://medium.com/x8-the-ai-community/audio-classification-using-cnn-coding-example-f9cbd272269e
https://analyticsindiamag.com/hands-on-tutorial-on-visualizing-spectrograms-in-python/





