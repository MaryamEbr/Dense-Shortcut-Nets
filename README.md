# Dense-Shortcut-Nets

This is a final group project for Neural Networks and Deep Learning course (CSC413/2516, Winter 2022, UofT). 
In this project, we explore the domain of convolutional networks with residual connections. Our primary focus lies in comparing three renowned architectures: ResNet, DenseNet, and DSNet.
DenseNets have demonstrated superior performance on vision tasks, but have a
much higher memory footprint than ResNets. DSNets claim to have solved this
trade-off. We take a deeper look at this architecture and compare
it side-by-side with the other two in multiple experiments. We find that DSNets are
indeed significantly better than ResNets, but only if the model size is large enough.
We also test the effect of different hyperparameters and provide a guideline on
when to use each model based on memory and time requirements.

The codes are written in PyTorch, and the result of our investigations is provided in the report file.
