# RNN with "The Time Machine" dataset and ReLU
 Implementing a RNN for a character-level language model and training it with the "The Time Machine" dataset and the ReLU activation function.
 
If we remove the gradient clipping and still use the tanh activation function, we can see its results in the first figure below. The perplexity is positive infinity which is the worst case for perplexity value.\
![image](https://user-images.githubusercontent.com/70276800/145123772-b6a5b76e-7da1-4fb8-b8ee-57d2f66c8e6e.png)



Using ReLU as the activation function eliminates the need for gradient clipping. This is possible because changing to ReLU stops the numerical overflow or underflow referred to as exploding gradients. The second figure shows the model results without gradient clipping and with the ReLU activation function. The perplexity is 1.0 which is the best case scenario.\
![image](https://user-images.githubusercontent.com/70276800/145121583-2d3f419b-d708-4239-ab0d-2ea3a848e66d.png)
