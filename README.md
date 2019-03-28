# Hidden Markov Model Part-of-Speech Tagger

This project is practice at programming a part-of-speech tagger - an integral part of many language interpretation programs, 
chatbots, and similar AI applications - using first a Most Frequent Class tagger, and then a Hidden Markov Model, to compare
the accuracy of the two algorithms. This is my implementation of Udacity's HMM Tagger project for the Artificial Intelligence
specialization, which is available for download [here](https://github.com/udacity/hmm-tagger).

Hidden Markov Models are a significant innovation in artificial intelligence. They function by generating a sequence of data - 
observations, which are a set of finite internal states that model external events, and hidden state changes, which are 
invisible to an observer outside the system. The next state of the sequence depends on the immediate previous state, which 
is the Markov process. The purpose of this part-of-speech HMM is to predict a sequence of state changes - the class
of the words used in a given sentence - based on the sequence of observations, or the context in which each word is used.
