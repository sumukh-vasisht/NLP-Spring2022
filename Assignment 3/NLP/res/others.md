# Convolutional Neural Networks

* [CNN for NLP](http://www.wildml.com/2015/11/understanding-convolutional-neural-networks-for-nlp)

# Recurrent Neural Networks
## Architectures
* Many to One: Sentiment classification
* Many to Many: 

** Named Entity Recognition
** Translation

* One to Many: Music Generation
* One to one: Standard NN
* [The unreasonable effectiveness of RNN](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)

## Issues
### Vanishing Gradients
Difficulty in capturing long range dependencies:

*The trip* to Niagara Falls, pleasent despite cold weather, was smooth.

*The trips* to Niagara Falls, pleasent despite cold weather, were smooth.

*The trip* or *The trips* ? : for a model (i.e. RNN) it is hard to produce probability of such a distant dependency. 
 

Technically, 

The effect of deeper (later) layers on change in the weights of shallower (earlier) layers is negligible or **vanishing**

The derivative decreases exponentially as function of the number of layer.

### Exploding Gradients
The derivative increases exponentially as function of the number of layer.

## Gated Recurrent Units

## LSTM Networks

* [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)

## Bidirectional RNNs

