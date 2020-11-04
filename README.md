# GANs
This repo contains some experiments with Generative Adversarial Networks which could be tested on Google Colab.

---
## MNIST
### Simple GAN
Generative Adversarial Networks with convolutional **Discriminator** and transposed convolutional **Generator** trainned on Google Colab's GPUs for 490 minutes (~8 hours) and 600000 learning iterations to generate MNIST handwritten digits. At last iteration mean BCE of Discriminator was 0.01261 and mean BCE of Generator was 5.65304.
Generator creates images from 100-dimentional random vector.
You may find pritrainned model here: [latest model checkpoint](https://drive.google.com/file/d/1dwFPifERZixZCgk1pe5aMMoraLXtrQMW/view?usp=sharing).

#### Generator's evolution:
![gif](https://media.giphy.com/media/VEMTqeXAKdkKtkSn4A/giphy.gif)
---

