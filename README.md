AI/ML Advance Project
# Generative Adversarial Networks for Image Generation

This project implements a Generative Adversarial Network (GAN) to generate realistic handwritten digit images using the MNIST dataset. The GAN consists of two neural networks: a Generator that creates fake images and a Discriminator that distinguishes between real and fake images. Both networks are trained together in an adversarial manner until the Generator produces images that closely resemble real digits.

## Key Steps
1. Loaded and preprocessed the MNIST dataset.
2. Built a Generator network using Conv2DTranspose layers.
3. Built a Discriminator network using Conv2D layers.
4. Defined adversarial training objectives using binary cross-entropy loss.
5. Trained the GAN using alternating updates for Generator and Discriminator.
6. Visualized generated images at different training epochs.

## Results
After training, the Generator produces high-quality digit images resembling those from the MNIST dataset. The output improves as epochs progress, showcasing how adversarial training enhances generative performance.

## Technologies Used
Python, TensorFlow/Keras, NumPy, Matplotlib

## Dataset
The MNIST dataset is used and directly loaded via TensorFlow’s built-in function:
(X_train, _), (_, _) = tf.keras.datasets.mnist.load_data()
Hence, there is no need to download the dataset manually.
Link : https://www.kaggle.com/datasets/hojjatk/mnist-dataset
and I have downlaoded: 
train-images.idx3-ubyte
train-labels.idx1-ubyte
t10k-images.idx3-ubyte
t10k-labels.idx1-ubyte

## How to Run
1. Clone the repository.
2. Install dependencies using: pip install tensorflow numpy matplotlib
3. Run the notebook or script to train the GAN.
4. Generated images will be saved automatically after every 10 epochs.

## Learning Outcome
This project demonstrates the fundamental principles of Generative Adversarial Networks, data preprocessing, adversarial training, and deep learning-based image generation.

## Contributing
Contributions are welcome!
Feel free to fork the repository, improve the game, and open a pull request. Let's grow this classic game together!

## License
This project is licensed under the [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

## Author
**Aarya Mehta**  
🔗 [GitHub Profile](https://github.com/AaryaMehta2506)


