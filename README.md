# transfer-learning
Here I used a pretrained Xception model. I trained that model on the following data https://drive.google.com/open?id=13TzzeIMZc-ZHn8-R80Jkz-UbDD7GFjL6

I replaced the original fully connected layer with a new one of 512 nodes and relu activation followed by batch normalization and output layer of 20 nodes. Then I also fined tuned block 14 of the model.

This model achieved **96.0%** validation accuracy
