# createmore

createmore is the result of following a series of tutorials on language modeling taught by Andrej Karpathy.

createmore takes one file of text as input, where each line is assumed to be one training example, and will generate
more just like it.

This repo will include the models built throughout the tutorial as well as completed exercises if I have the spare time to complete them.

### Autoregressive character-level language model

createmore is a autoregressive character-level language model, which means that it is a model that takes in a sequence of past "things" and generates the next "thing" or "things", in this case the "things" are characters that make up words.

For example, we can feed it the entire English dictionary and createmore will generate unique words that will plausibly
sound Engish-like, or we can give it a database of city names from around the world and generate ideas for the name of a new city.

There will be a wide-range of implementations: from a Bigram model all the way to a Transformer like GPT-2. 

## Bigram Model


