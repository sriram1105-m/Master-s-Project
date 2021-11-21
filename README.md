# Master-s-Project

**Problem Statement**

The basic role of a designer is to construct an instinctive and engaging website. There are
numerous steps associated with creating a website prior to pushing it to live starting from
drawing concept sketches to testing process. HTML and CSS are the most widely recognised
that are being used in web development. Executing the interfaces in HTML and CSS is
cumbersome and painful task. At the same time, the front-end developers are also not very
proficient. Simultaneously, there are multiple iterations of the design are necessary to make a
website appealing to the customers. To manage the situation, there is a need of a powerful tool
that ought to speed-up the front-end development, coding, testing the layout quicker and more
efficient.

**Aim and objective**

The aim of this project is to build a deep learning pipeline that will convert the visual designs
into intermediatory code that enables rendering components ready to be scaled at the
industrialization level.

**Architectures Used**

![image](https://user-images.githubusercontent.com/75327547/142779718-f0da43c0-47a2-4fe0-ac2a-49c2acf14094.png)

Inception-ResNet architecture is nothing but the use of residual connections in the inception architecture. Inception ResNetV2 is a type of convolutional neural network that is trained on more than a million images from the ImageNet Dataset. The network is 164 layers deep and can classify images into 1000 classes. This network has an input size of 299x299 and the output is a list of estimated class probabilities. 

**Encoder-Decoder Model**

The conventional deep neural networks are amazing AI models that accomplish great execution on troublesome issues like speech recognition and visual object recognition. But they can only be used for large amount of labelled data where the inputs and the targets can be reasonably encoded with vectors of fixed dimensionality. They cannot be used to map sequence to sequence learning. In order to solve the problem of sequence-to-sequence learning, encoder-decoder model was developed.

![image](https://user-images.githubusercontent.com/75327547/142779798-5f17efa2-5d32-459c-ba6e-e30839df8a60.png)

The internal structure of the Encoder-Decoder is shown below:

![image](https://user-images.githubusercontent.com/75327547/142779824-ebf62738-ad57-4ae2-abe4-615c18aebd92.png)

**The Encoder Block**

The Encoder part is a LSTM cell. It is taken care of in the input sequence over the long run and it attempts to epitomize all its data and store it in the final internal states ht (hidden state) and ct (cell state). The internal states are then passed on to the decoder part, which it will use to attempt to create target sequence. The outputs at each time step are discarded in the encoder part 

![image](https://user-images.githubusercontent.com/75327547/142779848-90ff9641-6de1-4657-9918-145b8ee3b61f.png)

**The Decoder Block**

So, in the wake of pursuing the entire information sequence, the encoder passes the inside states to the decoder and this is the place where the prediction of the output sequence begins. The Decoder block of the Encoder-Decoder model is shown below.

![image](https://user-images.githubusercontent.com/75327547/142779863-5558a638-4400-4711-b9f5-5a56c229e72e.png)

**Proposed AI Pipeline architecture**

![image](https://user-images.githubusercontent.com/75327547/142779884-0b233101-c10a-42d2-90fe-3b4e4a5803c3.png)

**References**

1. https://arxiv.org/pdf/1705.07962.pdf

2. https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8720784

3. https://machinelearningmastery.com/deep-learning-caption-generation-models/


