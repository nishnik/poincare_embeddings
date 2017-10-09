# poincare_embeddings
NumPy implementation of Poincaré Embeddings for Learning Hierarchical Representations (Facebook Research). <br>
[Link to paper](https://arxiv.org/pdf/1705.08039.pdf) <br>
[Link to blog](https://medium.com/towards-data-science/facebook-research-just-published-an-awesome-paper-on-learning-hierarchical-representations-34e3d829ede7)

[poincare.py](https://github.com/nishnik/poincare_embeddings/blob/master/poincare.py) contains the crude implementation, [poincare_adam.py](https://github.com/nishnik/poincare_embeddings/blob/master/poincare.py) contains my experiments with adam.

Sample results:

### Without adam, three levels deep:

#### Initial
![https://github.com/nishnik/poincare_embeddings/blob/master/plots/3_init.png](https://github.com/nishnik/poincare_embeddings/blob/master/plots/3_init.png)
#### Epoch 1
![https://github.com/nishnik/poincare_embeddings/blob/master/plots/3_1.png](https://github.com/nishnik/poincare_embeddings/blob/master/plots/3_1.png)
#### Epoch 181
![https://github.com/nishnik/poincare_embeddings/blob/master/plots/3_181.png](https://github.com/nishnik/poincare_embeddings/blob/master/plots/3_181.png)


### With adam, three levels deep:

#### Initial
![https://github.com/nishnik/poincare_embeddings/blob/master/plots/adam3_init.png](https://github.com/nishnik/poincare_embeddings/blob/master/plots/adam3_init.png)
#### Epoch 1
![https://github.com/nishnik/poincare_embeddings/blob/master/plots/adam3_1.png](https://github.com/nishnik/poincare_embeddings/blob/master/plots/adam3_1.png)
#### Epoch 181
![https://github.com/nishnik/poincare_embeddings/blob/master/plots/adam3_181.png](https://github.com/nishnik/poincare_embeddings/blob/master/plots/adam3_181.png)

### Without adam, four levels deep:

#### Initial
![https://github.com/nishnik/poincare_embeddings/blob/master/plots/4_init.png](https://github.com/nishnik/poincare_embeddings/blob/master/plots/4_init.png)
#### Epoch 1
![https://github.com/nishnik/poincare_embeddings/blob/master/plots/4_1.png](https://github.com/nishnik/poincare_embeddings/blob/master/plots/4_1.png)
#### Epoch 181
![https://github.com/nishnik/poincare_embeddings/blob/master/plots/4_181.png](https://github.com/nishnik/poincare_embeddings/blob/master/plots/4_181.png)


### With adam, four levels deep:

#### Initial
![https://github.com/nishnik/poincare_embeddings/blob/master/plots/adam4_init.png](https://github.com/nishnik/poincare_embeddings/blob/master/plots/adam4_init.png)
#### Epoch 1
![https://github.com/nishnik/poincare_embeddings/blob/master/plots/adam4_1.png](https://github.com/nishnik/poincare_embeddings/blob/master/plots/adam4_1.png)
#### Epoch 181
![https://github.com/nishnik/poincare_embeddings/blob/master/plots/adam4_181.png](https://github.com/nishnik/poincare_embeddings/blob/master/plots/adam4_181.png)
