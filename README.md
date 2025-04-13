# MEDICAL IMAGE CAPTIONING
  An AI system that generates diagnostic captions for radiological images (X-rays, CT scans) using deep learning, improving clinical workflows and accessibility.

# PURPOSE
  The goal is to enhance diagnostic workflows by generating meaningful textual descriptions of medical images. It helps reduce interpretation time and improves accessibility in radiology.   
  
# TECHNICAL STACK

1.**FRAMEWORKS**  -  Tensorflow  and PyTorch

2.**STREAMLIT**   -  For deploying the model and creating an interactive user interface

3.**MATPLOTLIB**  -  For visualization of training performance (accuracy and loss)

4.**PYTHON**      -  Core logic

5.**MODEL**      -  To automate accurate and context-aware caption generation for radiological images

# MODEL
Two models are employed in this project :
1.**CNN-GRU (Convolutional Neural Network + Gated Recurrent Unit)**
It is kind of Ensemble Methods
CNN: For spatial feature extraction from medical images

GRU: For sequential caption generation based on extracted features

2.**GIT (Generative Image-to-Text Transformer)**

Transformer-based model using self-attention for context-aware caption generation . Pretrained on large-scale image-caption datasets

# DATASET

ROCOv2 Radiology Dataset
     Contains ~60,000 radiological images with corresponding expert-written captions
     Includes modalities like CT, MRI, X-rays, and ultrasound

# EVALUATION

Accuracy: GIT – 92%, CNN-GRU – 84%

BLEU Score: GIT – 1.00, CNN-GRU – 0.86

Loss: GIT – 0.08, CNN-GRU – 0.42

GIT outperformed CNN-GRU in all aspects due to its attention mechanisms and parallel processing.

# FUTURE ENHANCEMENT

Integration with Electronic Health Record (EHR) systems for real-time clinical use

Support for multilingual captioning

Expand dataset diversity for better generalization across diseases

Deploy on cloud for scalable access in telemedicine

# STREAMLIT

# PROJECT FILES

