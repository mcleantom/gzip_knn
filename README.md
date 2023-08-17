~~Attention~~ Gzip is all you need.

This repository follows along the [youtube video by Sentex](https://www.youtube.com/watch?v=jkdWzvMOPuo). It uses GZip as a feature for a language model.

Why does the the the length of a compressed string, compared to the length of the compressed representation of the two strings concatenated together work so
well as a feature for classification tasks? Why is there a relation between how much gzip can compress a string, and the sentiment of the string?

The reason is because if two strings are similar, then GZip will be able to compress the two strings joined together, more than if the two strings were disimilar. 
