
#Neural Networks Overfitting is GOOD 

Overffiting may caused a lot of problems to many machine learning developers, and mostly all articles discuess how to avoid it, however in this notebook we will see what if overfitting is actually good in some senarios.

The idea is to use overfetting to memorize bytes of data into a neural network, the ordinary way that we do this is to map each index to one byte.
Our apprach here is to map multipe indices to the same byte.

what do we get from this ? 
- a lossless compression algorithm
- a read only data: any changes to the weights of the neural network will impact the data, thus assuring its integrity
- an abstraction to the type of data

click [here](https://github.com/nadirbelarouci/NN-overfitting-isgood/blob/master/NN_overfitting_is_good.ipynb) to see read the complete example. 
