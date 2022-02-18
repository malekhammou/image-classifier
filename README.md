# image-classifier
This is gentle implementation of an image classifier in Pytorch. The goal of this project is to understand the building blocks of a neural network architecture.
The following concepts are addressed:
<br>
<strong>1. Loading data with DataLoaders.
<br>
2. Performing/composing transformations on data.
<br>
3. Normalizing input.
<br>
4. Building thedifferent layers of a nn.
  </strong>
  
 WHAT I LEARNED  ✔
  - Handling 2-D image classification tasks with fully connected networks is not the best choice because these networks are not translation invariant.They try to relate every input pixel to every output pixel regardless of the spacial arrangement. The trained model will therefore have a hard time recognizing the same shape in a different location in the image.
  - Convolutions deliver locality and translation invariance.
