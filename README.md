# VoicePathNet: Classifier Fusion with CNN-Driven Multiclass Voice Disorder Diagnosis with Enhanced Preprocessing



#Abstruct

Automated voice disorder classification is an important resource in clinical assess-
ments, allowing for prompt identification and management of voice disorders.
This article presents a robust technique for categorizing voice disorders, combin-
ing deep learning and traditional machine learning methods. This study utilizes
five pre-trained Convolutional Neural Networks (CNNs) to capture high-level
characteristics from endoscopic images. Then, five distinct classifiers—Support
Vector Machine (SVM), Random Forest, k-Nearest Neighbors (KNN), Decision
Tree, and Gradient Boosting (XGB)—enhance the CNN-based feature extraction
method to classify 14 categories of voice pathology. In order to improve clas-
sification accuracy, this study performs multiple preproessing methods on the
images. First, noise reduction algorithms work by initially removing unwanted
noise in images. Then, contrast enhancement technique boosts the contrast of the
images, enabling CNNs to identify crucial features with greater efficiency. Also,
principal component analysis decreases dimensionality by preserving important
features and minimizing computational complexity. This research validates the
outcomes through an extensive cross-validation approach, ensuring the model’s
ability to generalize effectively on various data subsets. Utilizing a combination
of CNNs for extracting features and traditional classifiers for the final classifi-
cation, this multi-stage method achieves an impressive test accuracy of 95.77%
using a combination of KNN and ResNet50. Utilizing a variety of CNN struc-
tures and machine learning classifiers enhances adaptability and resilience. This
shows the promise of the method for clinical use in diagnosing voice disorders
through automation, emphasizing the importance of accurate and dependable
classification for successful treatment decisions.
