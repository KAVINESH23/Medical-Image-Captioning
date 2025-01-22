# Medical-Image-Captioning
  ##Introduction
        Medical imaging plays a vital role in diagnosing and managing various diseases. However, interpreting complex radiological images requires significant expertise. To address this 
    challenge, this project explores deep learning techniques to automate image captioning for radiological images, improving diagnostic workflows and accessibility.
    
    Two models are employed in this project :
    
    CNN-GRU (Convolutional Neural Network - Gated Recurrent Unit): Combines convolutional layers for spatial feature extraction with GRU layers for temporal text generation.
    GIT (Generative Image Transformer): A transformer-based architecture leveraging attention mechanisms to generate contextually precise and coherent captions.
    The models are trained on the ROCOv2 dataset, which consists of 59,958 radiological images paired with textual descriptions. Performance is evaluated using BLEU scores, demonstrating 
    the potential of these models in generating high-quality captions to assist healthcare professionals.
  ##Technical Stack
      Frameworks and Tools
      TensorFlow: For CNN-GRU model development and training.
      Hugging Face Transformers: For implementing the GIT model.
      Streamlit: For deploying the model and creating an interactive user interface.
      PyTorch: As an alternative backend for the GIT model.
      Matplotlib: For visualization of training performance (accuracy and loss).

