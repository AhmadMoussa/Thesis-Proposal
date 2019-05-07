# Master Thesis

* Generate musical content from text or video
* This repo will be: a storage space for all relevant material, links and research papers that I find; a "diary" for my ideas and thought process; as well as a notebook to report my research advancement, progress and new things that I learn and discover along the way.

## Ideas to explore:
* Idea 5/2/2019: Create a musical concept graph? We could create a graph that represents the emotional content of the text or video
* Idea 5/3/2019: I need to have some input data set to train on. Maybe I can create some program (like the video to music program that I am making), to create music in some structured way. If I could generate and produce a bunch of pieces, that I will still revise later on, then I could create a meaningful data set to train on with an RNN or Wavenet. Could this be useful? Maybe. Probably not.
* Idea 5/7/2019: So basically what my research will be boiling down to is, creating a musical sequence from other types of sequences such as text or video, such that it can be translated in a meaningful way. Why si this relevant? Because not a lot of research has gone into this yet and it could be a useful media application for musicians and those who work in a field tangentially related to music.
* 5/7/2019: Assume we create a model that is able of generating a sequence of musical notes from some arbitrary input sequence? How would we train and evaluate it's results? One way of doing this could be by crowdsourcing, have the results dynamically generated on a webpage and let people evaluate the results, since after all the human ear is still the best evaluator. So for example we give the person that is evaluating a bunch of tags ("such as happy or sad") to classify the output of the model, or maybe let them input a value between 0 and 10 to evaluate how well the model did. I still have to think about how to implement these specifics.

## Tools:
* [Tensorflow](https://www.tensorflow.org/install) crucial package for creating NN models
* [PyTorch](https://pytorch.org/tutorials/beginner/blitz/tensor_tutorial.html) A replacement for NumPy to use the power of GPUs [install from here](https://pytorch.org/get-started/locally/) and check if you have a CUDA enabled GPU [here](https://developer.nvidia.com/cuda-gpus), and [here is a tutorial](https://medium.com/@josh_2774/deep-learning-with-pytorch-9574e74d17ad) on how to use pyTorch with deep learning
* [TensorBoard](https://www.tensorflow.org/guide/summaries_and_tensorboard#setup) to visualize the training process, a nice feature of tensorflow
* [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)
* [Nsynth Dataset](https://magenta.tensorflow.org/datasets/nsynth), audio sample dataset of musical notes a magnitude larger than any other dataset on the internet (300k samples)
* [Theano](http://deeplearning.net/software/theano/) is a Python library that allows you to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently.

## Concepts:
* [Mu-Law Quantization](https://en.wikipedia.org/wiki/%CE%9C-law_algorithm), important for error estimation?
* [Cross Entropy Explained](https://stackoverflow.com/questions/41990250/what-is-cross-entropy)
* [Difference Between Entropy and Cross-Entropy](https://towardsdatascience.com/demystifying-cross-entropy-e80e3ad54a8)
* [Companding Transformation](https://en.wikipedia.org/wiki/Companding)

## Probability Concepts for machine learning:
* [Kullback Leibler Divergence Explained in Detail, Count Bayesie](https://www.countbayesie.com/blog/2017/5/9/kullback-leibler-divergence-explained)
* [Kullback leibler divergence overview, Medium Article](https://medium.com/@samsachedina/demystified-kullback-leibler-divergence-3971f956ef34)
* [Video explaining information entropy](https://www.youtube.com/watch?v=LodZWzrbayY)
* [Course on information entropy MIT](https://www.youtube.com/watch?list=PLDDE03B3BDCA1D9B1&v=phxsQrZQupo)

## Auto-encoders:
* [Introduction to Autoencoders](https://towardsdatascience.com/deep-inside-autoencoders-7e41f319999f)
* [Tensorflow code for different autoencoders](https://github.com/nathanhubens/Autoencoders)

## GANs:
* [Understanding and Optimizing Gans](https://towardsdatascience.com/understanding-and-optimizing-gans-going-back-to-first-principles-e5df8835ae18)

## Other relevant material:
* [This guy has a very Interesting blog](https://www.countbayesie.com/all-posts)
* [Why use the log probability for gradient descent instead of just the probability, very interestion!](https://stats.stackexchange.com/questions/174481/why-to-optimize-max-log-probability-instead-of-probability)
* [Thought Vectors Explained](http://gabgoh.github.io/ThoughtVectors/)
* [Skip or residual connections](https://towardsdatascience.com/residual-blocks-building-blocks-of-resnet-fd90ca15d6ec)

## Optimization techniques:
* [Optimization problem solved by crowdsourcing, Maybe I can make somthing similar to this](https://koyama.xyz/project/sequential_line_search/)
* [Introduction to the Adam Optimizer](https://machinelearningmastery.com/adam-optimization-algorithm-for-deep-learning/)

## Convolutional networks:
* [Understanding Convolutions](https://adeshpande3.github.io/A-Beginner%27s-Guide-To-Understanding-Convolutional-Neural-Networks/), [part2](
https://adeshpande3.github.io/adeshpande3.github.io/A-Beginner's-Guide-To-Understanding-Convolutional-Neural-Networks-Part-2/)
* [Stanford course on convolutional networks](http://cs231n.github.io/)

## Recurrent Neural Networks
* [Andrej Karpathy - The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)
* 

