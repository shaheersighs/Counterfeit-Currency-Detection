The Counterfeit Currency Detection System is an AI-powered solution that uses deep learning and computer vision to detect counterfeit Pakistani banknotes in real-time. The project leverages TensorFlow, OpenCV, and Raspberry Pi to analyze the colour density and sharpness and classify currency as real or fake. The system consists of several components:  

A Convolutional Neural Network (CNN) model was developed and trained, achieving a notable 91% accuracy in classifying currency authenticity. Concurrently, a YOLOv8 model was deployed to accurately identify the denominations of Pakistani banknotes. Both models were hosted on Google Drive, enabling efficient and seamless updates. These models were integrated within a real-time detection framework powered by Raspberry Pi 5 hardware, utilizing Natural Language Processing (NLP) to audibly announce the detection results. A significant and unexpected outcome was the CNN model’s perfect generalization to accurately detect the authenticity of 5000 rupee notes without prior training on this denomination.



