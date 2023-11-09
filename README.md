**Sign-Language-To-Text-and-Speech-Conversion**

**ABSTRACT:** 

 Sign language is a rich and ancient mode of communication, which has for ages molded the way specially-abled individuals interact with each other. This set excellent context and allowed us to work towards smoothening the communication experience between frequent and inexperienced signers. Our project is dedicated to advancing the conversion of sign language into text in real-time. We employ state-of-the-art neural network technology to transform finger-spelling-based American Sign Language into written text, offering a powerful tool for inclusive communication.

Automatic recognition of human gestures from camera images is a fascinating field within computer vision, and it holds immense potential for various applications. In our project, we focus on developing a robust solution that employs Convolutional Neural Networks (CNNs) to identify and understand hand gestures performed in the context of human activities, all from camera-captured images.

Our approach begins by capturing the position and orientation of the hand, which serves as the foundation for our CNN model's training and testing data. These images are first preprocessed through a filter designed to enhance the pertinent features. After this preprocessing step, the filtered images are fed into a classifier that predicts the specific class of the finger spelling.

In the final phase, the CNN is trained using these calibrated images, enabling it to accurately recognize and translate American Sign Language(ASL) gestures into written text. This project not only aims to facilitate communication for the deaf and hard of hearing but also showcases the potential of cutting-edge technology in bridging linguistic and cultural gaps.




**Proposed System**

 Our proposed system represents a significant improvement in enhancing communication and inclusivity for sign language users and non-signers alike. With a primary goal of enabling real-time comprehension of word-level sign language, this innovative platform offers a user-friendly interface that can seamlessly fit in conversations organically.At the core of our system lies the integration of cutting-edge deep learning and computer vision algorithms, ensuring accurate and real-time predictions. By receiving finger spelling signals as input, our application excels at interpreting intricate finger-level sign language gestures and constructing meaningful sentences, facilitating smooth and effective communication.

To achieve this level of accuracy and performance, our system undergoes training using a custom dataset specifically designed for the purpose. This dataset is comprised of a file directory containing images that have been meticulously processed with a Gaussian blur filter. This filter is crucial for extracting essential features, with a particular focus on identifying and tracking the hand within the frame.

At the heart of the application MediaPipe and CV algorithms are used to identify the hand and then use the created landmarks in CNN to identify and classify the finger spelling into the mentioned classes. The UI is supported by a backend enabled by flask which serves the videofeed and results for the realtime text conversion.

In summary, our proposed system looks to implement  realtime conversion and combine the best of significant deep learning algorithms.

**Scope:**
This System will be Beneficial for Both Dumb/Deaf People and the non signers as well. 
