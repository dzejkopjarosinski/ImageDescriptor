## Searching for graphics based on the contents

The code written in this project uses dense-net and euclidean distance to assess similarities between the input image and other images that may describe it. 
It then selects few of the images that describe the input image the best. Hence the model searches for best describing graphics for the image. 

- The flowers dataset was used in the project
- To generate image descriptor's vector DenseNet network was used.
- Gao Huang first introduced the architecture on a CVPR conference in 2017 Densely Connected Convolutional Networks.
- The project is importing densenet from Keras API (DenseNet121), that was trained on ImageNet dataset.
