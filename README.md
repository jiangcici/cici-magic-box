# cici-magic-box
EC601 Group10 Homework 1

Team member: Vikram Vikram, Yuxi Jiang, Yanxing Zhang

Tensor Flow model Namignizer revised. To use the model please check Note.md file

In this assignment, we picked Namignizer Tensorflow model from the Github. We will modify the code and tweak the parameters for the better results. 
Training the Neural Network:-
For Initial training for the model we are using the Keggle Dataset. Code for this module is available in TF-Namignizer-Linux branch.
To read more about Reccurent Neural Networks please check this link :- https://www.tensorflow.org/tutorials/recurrent#recurrent-neural-networks

DATASET:-
We used dataset from https://www.kaggle.com/kaggle/us-baby-names. The source code for converting raw data to tranining format is available here https://github.com/benhamner/us-baby-names/.

Name's database has three main feature: ["Name", "Gender", "Count]
Data are arranged statewise and nationwise.

After training we can get the output which can be seen as a side effect write model checkpoints to the model directory. After giving any arbitary sets of name while using the same model. We can have the output which shows the perplexity for each name. The output is like "Name xxxx gives us a perplexity of xxxxxxxxxx"

Also, we can use this trained model which needs us to use the same config and checkpoint directory to generate the name. The output is like  ['m','a','r','y','`'].
