# Vision_Transformer_Transfer_Learning

Vision Transformers (ViTs) have become a leading choice for various computer vision tasks due to their state-of-the-art performance. Among them, some models stand out for transfer learning in different scenarios.


## ViT (Vanilla Vision Transformer)

**Description:** 
    Vision Transformers (ViTs) are a type of neural network architecture designed primarily for processing images. Unlike traditional convolutional neural networks (CNNs), which process images in a hierarchical manner, ViTs apply self-attention mechanisms to capture global dependencies between image patches. This allows them to achieve strong performance on various computer vision tasks without relying on convolutional layers. ViTs have gained popularity for their ability to handle long-range dependencies effectively, making them suitable for tasks like image classification, object detection, and segmentation.
    The original Vision Transformer developed by Google. It divides images into patches, processes them as tokens, and applies transformer layers.

**Best For:** 
    General-purpose vision tasks when large-scale pretraining is available.

**Pre-trained Weights:** 
    Available on datasets like ImageNet-21k and ImageNet-1k.

**Transfer Learning Strength:** 
    Performs well for classification, particularly with fine-tuning on smaller datasets.


# Notebooks

1. [vision-transformer-trainer-and-pytorch-lightning]()
   
        Fine-tune Vision Transformer (ViT) models with PyTorch Lightning, leveraging its flexible and scalable framework for streamlined model training and experimentation.

2. [vision-transforme-with-hugging-face-transformer-and-keras]()
   
        This notebook includes tools for fine-tuning Vision Transformer (ViT) models using Keras, offering a simple and intuitive interface for building, training, and evaluating models.

3. [vision-transforme-with-pytorch-trainer]()
        The repository utilizes Lightning Trainer to simplify training workflows, enabling efficient fine-tuning of Vision Transformer (ViT) models with features like automatic checkpointing, logging, and distributed training.

