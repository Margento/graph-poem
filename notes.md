# Auto encoder:

Can we represent a poem as a vector of random variables? 

Can we make an auto encoder for each poem?

Metric:  use auto encoders.

poet a : define an auto encoder for poet a.  
poet b : define an auto encoder for poet b.

use the auto encoder for poet a on poet b and use the auto encoder from poet b
and use it on poet a and then measure the size of the distance between a and a
generated from b and b and b generated by a. take the average value of these two
differences and let this distance be the distance between. We can define
variance this way too.

learn to encode high dimensional vector into three dimensions.  and then learn how to decode three dimensional data back into original dimensions.

normalize each random variable.

# Distributions

1. plot out frequency of values each feature takes on.
2. figure out the distribution for each random variable.
3. 

# Dimension

- 1 dimension finite
- 2 dimension finite
- 3 or more infinite

# Training a neural network

- Is it like pruning a random walk?

# Metaphor

- Semantic disambiguation
- Semantic web
- Linked data?
- dog is an animal.  but if a person is called a dog, that doesn't make sense, so maybe a metaphor.
- can we measure the distance of word use from usual word use?
- computational metaphor:
# Diction

- Wordnet has api for classification of words by type, topic, abstractness.
here: http://www.nltk.org/book/ch02.html

- Ground level: bag of words comparison.
- Vaibhav used gensim api.
  - knowledge graph
  - word association (these words are found together)
- what about: knowledge graph where each word has a subgraph of related words
  - if a word seems out of place but the subgraph contains words that would make sense in the given context, it may be a metaphor
  - use synonyms as the subgraph.
  - delmonte paper on metaphor
  - cowell and gerophski paper
- Poets that favor certain senses over others
- quantify degree of abstractness
- Choice of words can give the poem a certain feel. Formal, casual, tense, playful.
- How is poetic speech different from ordinary speech? 
- Art comes from artifice. 

- poets may be:
  - tendency to be tactile
  - be juvenile
  - be philosophical
  - favour smells
  - favour sight