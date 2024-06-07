# Tamil-Brahmi Script Translation Project

## Introduction
This project focuses on the translation of Brahmi script into modern Tamil characters using image processing and deep learning techniques. The primary aim is to preserve and understand ancient texts by developing a robust model capable of accurately identifying and classifying characters from the Tamil-Brahmi script.

The Brahmi script, an ancient writing system, presents numerous challenges for translation due to its intricate characters and variations in handwriting. Over time, these scripts have become degraded, adding to the complexity of accurate translation. Traditional methods of decipherment are time-consuming and require expert knowledge, which limits accessibility and efficiency.

To address these challenges, our project integrates advanced image processing methods with deep learning models. By preprocessing the images, segmenting characters, and employing Convolutional Neural Networks (CNNs), we can automate the recognition and translation process. This approach not only improves accuracy but also speeds up the translation, making it possible to digitize and preserve ancient texts effectively.

## Key Components
### Image Preprocessing
- **Skew Correction:** Corrects any skewness in the scanned images.
- **Image Enhancement:** Enhances the quality of the images for better recognition.
- **Binarization:** Converts images to binary format for segmentation.

### Character Segmentation
- **Dilation:** Enhances the segmented characters.
- **Contours Detection:** Detects contours of the characters.
- **Bounding Box:** Draws bounding boxes around detected characters for extraction.

### Character Recognition
- **CNN Model:** A Convolutional Neural Network trained on the Tamil-Brahmi dataset for character classification.

## Acknowledgements
Special thanks to the Tamil Development Department and other experts for their invaluable input and resources. Tools and resources like the Jinavani web application greatly enhanced the dataset's accuracy and comprehensiveness.
