<h1 align='center'> Machine Learning Project </h1>

<h2 align='center'> Sharif University of Technology </h2>

<h3 align='center'> Electrical Engineering Department </h3>

In the first phase of this project, we implemented the EM algorithm.

The Expectation-Maximization (EM) algorithm is an iterative optimization algorithm used to find maximum likelihood or maximum a posteriori (MAP) estimates of parameters in statistical models where the data involves latent (unobservable) variables. The EM algorithm is particularly useful when dealing with incomplete or missing data problems.<br>
The algorithm consists of two main steps: the Expectation (E) step and the Maximization (M) step. These steps are repeated iteratively until convergence to estimate the parameters of the model.

In the second phase, we apply this algorithm to infer clean image from
corrupted images (in this case, MNIST dataset).

In the third phase, we solved the following 3 problems:
- Design and train an AutoEncoder using PyTorch on the dataset(landscape image colorization) to colorize grayscale images.
- Design and train an AutoEncoder on the MNIST dataset to denoise the noisy images. Also denoise images with PCA algorithm.
- Design and train an AutoEncoder using PyTorch on the dataset(image super resolution) to enhance the resolution of images from low resolution to high resolution.
