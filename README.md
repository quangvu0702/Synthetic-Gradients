# Synthetic-Gradients
Implement systhetic gradients decent on pytorch

It's a simple idea: rather than compute gradients through backpropagation, we can train a model to predict what those gradients will be, and use our prediction to update our weights. I wanted to try using this in my own work and didn't find a Tensorflow implementation to my liking, so here is mine. I also take this opportunity to (attempt to) answer one of the questions I had while reading the paper: why not use synthetic loss instead of synthetic gradients?

## Reference link:
https://r2rt.com/synthetic-gradients-with-tensorflow.html

https://arxiv.org/abs/1703.00522

https://deepmind.com/blog/decoupled-neural-networks-using-synthetic-gradients/

http://deliprao.com/archives/187
