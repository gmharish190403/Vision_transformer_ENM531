# Vision_transformer_ENM531
Code for a simple vision transformer that uses the CIFAR_10 dataset with
Patch size: 4
Number of heads: 4
Hidden dimension: 256
MLP ratio: 2
Number of encoder layers: 6
Using the multi-class cross entropy loss function and the AdamW optimizer with a weight decay of 1e-02. Use a warmup exponential decay learning rate scheduler, with an inital value of 1e-07, peak value of 1e-03, 500 warmup steps, transition every 500 steps and a decay rate of 0.9. 
