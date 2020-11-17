# Deep_Learning_Assignments
## **Backpropagation:**
Implementation of backpropagation to minimize the error given a complex computational graph as shown in the figure below:
![Capture](https://github.com/nagik17/Deep_Learning_Assignments/blob/main/Capture.JPG) 
#### Summary:
Task 1 was about implementing forward and backward propagation functions. \
Task 2 was to plot the loss with different optimizers such as Vanilla sgd, Momentum based, Adam. \
As seen, Adam and Momentum updates work better with our data where as Vanilla is not reducing loss as effectively with increase
in epoch. 
## **CallBacks:**
#### **Model-1**
1. Used tanh as an activation for every layer except output layer \
2. used SGD with momentum as optimizer \
3. used RandomUniform(0,1) as initilizer \
3. Analyzed output and training process \
#### **Model-2**
1. Used relu as an activation for every layer except output layer \
2. used SGD with momentum as optimizer \
3. used RandomUniform(0,1) as initilizer \
3. Analyzed output and training process \
#### **Model-3**
1. Used relu as an activation for every layer except output layer \
2. used SGD with momentum as optimizer \
3. used he_uniform() as initilizer \
3. Analyzed your output and training process.
## **CNN:**
Heavy Text Preprocessing and Data Cleaning. 
Applying CNN on all text documents and doing character embedding, then passing it onto neural network to get desired accuracy score.
## **LSTM:**
![Capture](https://github.com/nagik17/Deep_Learning_Assignments/blob/main/1.JPG)
3 tasks including 3 different models, one of which is above. Tasks included optimization, complex model architecture, decreasing genreal loss.
## **Transfer Learning:**
#### **Model 1:**
1. Used VGG-16 pretrained network without Fully Connected layers and initilize all the weights with Imagenet trained weights. \
2. After VGG-16 network without FC layers, added a new Conv block ( 1 Conv layer and 1 Maxpooling ), 2 FC layers and a output layer. \
3. Final architecture: INPUT --> VGG-16 without Top layers(FC) --> Conv Layer --> Maxpool Layer --> 2 FC layers --> Output \
4. Trained only new Conv block, FC layers, output layer. Didnt train the VGG-16 network.
#### **Model 2:**
1. Used VGG-16 pretrained network without Fully Connected layers and initilize all the weights with Imagenet trained weights. \
2. After VGG-16 network without FC layers, don't use FC layers, use conv layers only as Fully connected layer. \
3. Final architecture: VGG-16 without FC layers(without top), 2 Conv layers identical to FC layers, 1 output layer for 16 classes. \
4. Trained only last 2 Conv layers identical to FC layers, 1 output layer. Didn't train the VGG-16 network.
## **BERT:**
It contains 5 parts as below. \
1. Preprocessing \
2. Creating a BERT model from the Tensorflow HUB. \
3. Tokenization \
4. getting the pretrained embedding Vector for a given review from the BERT. \
5. Using the embedding data apply NN and classify the reviews. \
6. Creating a Data pipeline for BERT Model. \



