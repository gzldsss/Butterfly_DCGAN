# BUTTERFLY🦋🦋🦋🦋【蝴蝶】

🦋I used the DCGAN tutorial on the tensorflow official website to complete the training, using a butterfly dataset I made myself, and the pictures came from pinterest and the butterfly and moth dataset. This is my first attempt at making my own dataset, and the first time importing my own dataset into a model.

🦋I want to make DCGAN generate new butterfly pictures by learning pictures of butterflies. Some butterfly illustrations and specimens are also included in the data set for DCGAN to learn together.

🦋If you want to run this notebook, just drag and drop the butterfly dataset zip file to the content folder in colab.

## Generated Image

![01](https://github.com/gzldsss/Butterfly_DCGAN/assets/118484191/d66f993e-6b2f-488f-99b2-fda6063e61bb)
![02](https://github.com/gzldsss/Butterfly_DCGAN/assets/118484191/af76e98a-300b-4679-a53c-ff5c653ece1e)



After setting eporch to 500, the outline and color of the butterfly can be generated.

## Code

The original code comes from the DCGAN tutorial： https://www.tensorflow.org/tutorials/generative/dcgan

I modified the part of importing the dataset to have the model read the zip file and adapt the model to the dataset I made. I also modified the layers to correspond to the size of the dataset image and the color channel.
