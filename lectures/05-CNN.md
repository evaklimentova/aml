## Convolutional Neural Networks

### Required Study Materials

- [introduction to CNNs](https://www.youtube.com/watch?v=2-Ol7ZB0MmU)
- [transfer learning and explainability](https://www.youtube.com/watch?v=PCIGOK7WqEg&t=2s)
- [AI for Tesla self-driving car](https://www.youtube.com/watch?v=hx7BXih7zx8)

### Activities

#### 1. Convolution on pixel image

- every teams gets a paper with grid (10x10) and draws a pixel image with black, gray and white colors
- write on board different kernels (3x3 matrices filled with values, use eg. smoothing, edge detection or horizontal line detection)
- explain again how the convolution works
- take the pixel image, black ~ -1, gray ~ 0, white ~ 1, do the convolution (no padding, stride 1) for all kernels, go back to 1/0/-1 values (we can call this function pooling) and their colors -> we will get new images, each corresponding to one kernel
- to make the computations easier, we can use [this notebook](05-convolution_for_pixel_image.ipynb) (or it can be just for teachers as supportive material)
- after the activity explain the terms usually used while building the convolution layer in context of our images - eg. kernel size, stride length, padding, filters, pooling; also ask about what they think each kernel was for

#### 2. Mobilenet for traffic sign classification

- real code, run through Google Colab
- we will use already trained Mobilenet - CNN for image classification
- finetune it for our custom dataset of traffic sign images downloaded from google image search
- check the [notebook](05-mobilenet_for_traffic_signs.ipynb)

### Reasoning

- try the convolution, know how it's computed and understand what the parameters we are inputting to the convolution layer means
- understand the idea of finetuning and why it can be useful
- get to some real coding, try Google Colab
