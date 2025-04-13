# osteosarcoma-detection
In my osteosarcoma detection project, I effectively applied my Python programming skills along with deep learning techniques to develop a robust and efficient diagnostic model. The goal was to accurately classify osteosarcoma—a rare and aggressive form of bone cancer—using multimodal data sources. To achieve this, I implemented a deep learning pipeline that leveraged the strengths of pre-trained convolutional neural networks, including VGG and ResNet architectures.

Using Python’s extensive ecosystem for AI development, I preprocessed the data using libraries like OpenCV and NumPy to normalize, augment, and balance the dataset. For the deep learning models, I utilized TensorFlow and Keras to build and train both the VGG and ResNet-based classifiers on separate modalities, such as histopathological images and radiographs. These models were then fused using a multimodal fusion strategy, where features extracted from each network were concatenated and passed through fully connected layers for final classification.

This approach enabled the model to learn complementary patterns across modalities, significantly enhancing the prediction accuracy compared to single-modality models. I also fine-tuned hyperparameters and implemented dropout and batch normalization to minimize overfitting and improve generalization.

Additionally, I utilized Python’s visualization libraries like Matplotlib and Seaborn for EDA and performance analysis, generating ROC curves, confusion matrices, and accuracy plots. The final model demonstrated high precision and recall, showcasing its potential for aiding medical professionals in early and accurate diagnosis of osteosarcoma.

This project not only strengthened my understanding of deep learning and transfer learning but also deepened my experience in Python-based model development, end-to-end pipeline design, and real-world application of AI in healthcare.
