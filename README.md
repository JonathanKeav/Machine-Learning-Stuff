# Machine-Learning-Stuff

Computer vision and machine learning notebooks.

## Scale-invariant blob detector

[`CE6003_Assignment1.ipynb`](CE6003_Assignment1.ipynb) [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JonathanKeav/Machine-Learning-Stuff/blob/main/CE6003_Assignment1.ipynb)

A from-scratch keypoint detector for circular "blob" regions at different scales, written for the CE6003 Object Recognition module. The test case is finding the centres of sunflowers of different sizes in one image.

- Builds second-order Gaussian derivative kernels and applies them with separable convolution.
- Builds a scale-normalised Laplacian scale space across a range of σ values.
- Finds local maxima across space and scale, then draws each keypoint as a circle sized to its scale.

Uses NumPy, OpenCV and Matplotlib.
