# Glossary

This file contains definitions on terms related to world models.

## Definitons

### World model

**World models** are neural networks that understand the dynamics of the real world, including physics and spatial properties. They can use input data, including text, image, video, and movement, to generate videos that simulate realistic physical environments. [1]

### Reactive world model

Genrating the next chunk based on the current context and the recieved action.

### Streaming generation

Generate multiple frames that are then added to the context.

### Long-horizon consistency

The ability to maintain scene identity, geometry, object positions, and plausible dynamics over many seconds or minutes.

### Temporal drift 

Accumulated error over time.

### Action conditioning

Set of actions used to generate the next frame. Same context with different actions results in a different future.

### Controllability

Is a property originating from control theory, defining the ability to regulate a system. Basicaly   the degree to which generated output follows the intended action or condition. [2]

### Diffusion model 

Diffusion Models are a type of generative model that creates new content like images by adding and then subtracting “noise.” For example, an image generator would take a real image and slowly add random pixels until they become pure static and unrecognizable, then reverse this process to create a clear, realistic image. The technology is behind AI generators like DALL-E, Midjourney, and Stable Diffusion. [3]

### Latent diffusion

The key innovation of latent diffusion models is that they apply this diffusion process not to the raw pixel values of an image but instead to an encoded latent representation of the image. [4]

### DiT — Diffusion Transformer

A Diffusion Transformer is a new type of diffusion model that combines the denoising diffusion probabilistic model (DDPM) with the Transformer architecture. The core idea of the Diffusion Transformer is to use the Transformer as the backbone network for the diffusion model, instead of traditional convolutional neural networks (such as U-Net), to handle the latent representations of images. [5]

### Denoising objective

The loss used to train the diffusion model.

### Conditioning

Extra information given to the model.

### ControlNet

ControlNet is a neural network structure to control diffusion models by adding extra conditions.

### Autoregressive model

In statistics, an autoregressive (AR) model is a modelled representation of a type of random process. It can be used to describe time-varying processes from many natural and artificial sources. The model specifies output variables that are dependent linearly on their own previous values on a stochastic basis. The model is in the form of a stochastic difference equation (or recurrence relation). [7]

### Autoregressive generation

Generate future data step by step.

### What is a tensor

Tensors are simply mathematical objects that can be used to describe physical properties, just like scalars and vectors. In fact tensors are merely a generalisation of scalars and vectors; a scalar is a zero rank tensor, and a vector is a first rank tensor. The rank (or order) of a tensor is defined by the number of directions (and hence the dimensionality of the array) required to describe it. [8]

### Backpropagation

TODO

### Epochs

TODO

### Rectified linear unit (ReLu)

Rectified linear unit is an activation fuction that nullifes all negative values. It is used to reduce non-linearities. [9]

### Softmax

Rescales an n-dimensional input Tensor elements so that the elements of the n-dimensional output Tensor lie in the range [0,1] and sum to 1. [10]

### Back propagation

In this algorithm, parameters (model weights) are adjusted according to the gradient of the loss function with respect to the given parameter. [11]

### Gradient descent

The starting point is just an arbitrary point for us to evaluate the performance. From that starting point, we will find the derivative (or slope), and from there, we can use a tangent line to observe the steepness of the slope. The slope will inform the updates to the model parameters—i.e. the weights and bias. The slope at the starting point will be steeper, but as new parameters are generated, the steepness should gradually reduce until it reaches the lowest point on the curve, known as the point of convergence. [12]

### Few-step distillation

TODO

### Single-view video generation

TODO

### Multiview generation

TODO

### Single-view-to-multiview expansion

TODO

### View consistency

TODO

### Camera intrinsics

TODO

### Camera extrinsics

TODO

### Ego frame

TODO

### SE(3)

TODO

### Depth

Distance from camera to visible surfaces.

### Optical flow

Apparent pixel motion between frames. Useful for measuring temporal consistency.

### Plücker coordinates

TODO

### HDMap

TODO

### 3D cuboids

TODO

### Ego vehicle

TODO

### Ego trajectory

TODO

### Long-tail scenarios

TODO

### Downstream task

TODO

### Reconstruction metrics

TODO

### Temporal consistency metric

TODO

### Epipolar error

TODO

### Action sensitivity

TODO

### Ablation

TODO




# Biblio



## Biblio

[1] [What Is a World Model? ](https://www.nvidia.com/en-us/glossary/world-models/)
[2] [Controlability](https://en.wikipedia.org/wiki/Controllability)
[3] [Diffusion model](https://hai.stanford.edu/ai-definitions/what-are-diffusion-models)
[4] [Latent diffusion](https://medium.com/@aguimarneto/what-is-latent-diffusion-in-ai-43aa1ad4f71e)
[5] [DiT — Diffusion Transformer](https://medium.com/@threehappyer/understanding-dit-diffusion-transformer-in-one-article-2f7c330ad0ea)
[6] [ControlNet](https://stablediffusionweb.com/fr/ControlNet)
[7] [Autoregressive model](https://en.wikipedia.org/wiki/Autoregressive_model)
[8] [What is a Tensor?](https://www.doitpoms.ac.uk/tlplib/tensors/what_is_tensor.php)
[9] [Rectified linear unit](https://docs.pytorch.org/docs/2.12/generated/torch.nn.ReLU.html)
[10] [Softmax](https://docs.pytorch.org/docs/2.12/generated/torch.nn.Softmax.html)
[11] [Back propagation](https://visionbook.mit.edu/backpropagation.html)
[12] [What is gradient descent?](https://www.ibm.com/think/topics/gradient-descent)