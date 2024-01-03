# Face Generation from Textual Descriptions

This project explores an innovative approach for generating photorealistic faces from textual descriptions using deep learning. It pushes the boundaries of text-to-image generation by tackling the complexities of mapping textual facial attributes to lifelike images.

## Introduction
Generating faces from textual descriptions presents unique challenges compared to other text-to-image generation tasks. Faces have intricate attributes, proportions, and features that must be accurately translated from descriptions. This project develops an end-to-end pipeline to convert facial attribute descriptions into photorealistic portraits.

### Key highlights:
- Automatically generates captions for images in the CelebA dataset using Sentence BERT embeddings, enriching training data
- Employs a DC-GAN architecture with custom optimizations for face generation
- Achieves impressive synthesis of identity-preserving faces from textual descriptions

## Data Pipeline
- CelebA dataset images and manual attribute annotations
- Automated caption generation for CelebA images using Sentence BERT embeddings
- Preprocessing and dataset balancing techniques to improve training stability

## Model Architecture
- DC-GAN generator and discriminator networks
- Projection of text embeddings using a dense layer
- U-Net optimizations for improved facial coherence and sharpness
- Custom loss functions prioritizing identity and attribute preservation

## Results
The model is able to convincingly generate diverse faces matching the provided text descriptions. Some examples:

- _A middle-aged man with a chubby face and a friendly smile. He has a receding hairline and wavy brown hair that is starting to gray. He has big lips, a big nose, and narrow eyes that twinkle with humor. He is clean-shaven, with only a little bit of stubble on his chin_
<img width="167" alt="Screenshot (1)" src="https://github.com/ashreethaudhay/face_generation_from_textual_description/assets/155312402/2d535370-e2ac-4654-9577-ca6e1bd49b4e">

- _A young woman with an oval face, rosy cheeks, and a cheerful smile. She has high cheekbones, a double chin, and is slightly chubby. She has curly brown hair, big lips, and sparkling green eyes. She is wearing earrings and lipstick_


  


