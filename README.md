
### Word embedding

Word embeddings is a technique of representing word tokens in the data as representations such that words semantically similar will be closely represented in the embedding space.Hence for a word2vec model to correctly identify a subject or entity in a corpus, the model should be trained with the definitions of those entites before-hand where the definitions provide the context where they are used.This can provide a gist/sense of the inew input sentence where that entity is used.


This intuition of training the model this way is inspired from human way of learning.Consider a little girl who is learning a new language for the first time.The child is first taught basic sequence of words (sentences with minimum number of words) which when used together, make sense and have meaning.After learning a few sentences (each time with a different set of  vocabulary) the child is finally given another sentence, this time a little complex sentence (with greater no. of  words than earlier).Apart from introducing a few new words,this sentence contains most of the words already known to the kid (i.e already in the vocabulary). 

In layman's language, we can say this is the critical part of learning where any new information is comprehended and learnt based on the prior knowledge and that is how the kid eventually keeps learning more complex sentences that come across her.

But how did the girl learn the first couple of words in the first place to be able to form a knowledge base?
Unlike machines humans interpret things with multiple perspectives and hence are able to create a basic knowledge base of words that we hear for the first time by listening to the tone it is pronounced with, grasping the verbal expression that follows it and with the help of visual aspects (images/watching them for real). The perceived information help us create a knowledge base around the basic words in our vocabulary which keeps growing.

An AI only has words to start with for creating its knowledge base hence, we can train it how to learn by providing it training data that suits its learning method.
