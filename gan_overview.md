# Generative Advesarial Networks [GANs]

GANs belong to a class of neural networks - Generative Netwokrs

- Mojorly used for enerating realistic images
- Made up of two neural networks which are competing with each other
    - **Generator Network:** Used for generation
    - **Discriminator Network:** Used to determine if the generated image is a real or a fake
- [ Understand GANs better](https://arxiv.org/pdf/1406.2661)

---

## Generator - Discriminator Network

These two neural networks ompete with one another to become more accurate in their predictions

- **Generator Network:** 
    - This network is responsible for generation of realistic data
    - Can generate any sort of data based on training data
    - Learns to generate plausble data
    - Improves the quality of samples during the training process i.e. with time it generates better data

- **Discriminator Network:**
    - A simple classification Model performing binary classification (Real or Fake)
    - Takes input samples from real dataset and from the generator network and figures out which samples are real or fake
    - Learns to distinguish he generator's fake data from real data
    - Forces Generator to improve whenever it correctly distinguishes the generated data from real data

- *** Initialy in the training process its easy for the Discriminator to distinguish between fake and real data but during the training process its ability falls steadily as generator learns to develop better data ***

- Architecture of GANs

![This image shows the architecture of GANs](archGAN.png)

---

## Applications of GANs

- Generating realistic images
- Text to Image translation
- Photo Inpainting
- Generating 3D objects from 2D images
- Synthetic data generation