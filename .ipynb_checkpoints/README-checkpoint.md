# Simple-NER-from-scatch
Just a implementation of NER model from scratch with my own data.
First, I preprocess the data as I remove all the punctuation, lower the letter and split them all. As we will use all the word in the context window, so I pad the training sentence so we dont have to worry about the first and last word. Then we have to convert the token to the indices and then from the indices we change them to embedding vector. We also add pad and unk word to our vocab. And lastly, training! As the corpus is little, the test set may be overfit.
