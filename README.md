# word2vec
Step 1: Add Google Word2Vec Pretrained file using import os print(os.listdir("..
/input"))
Step 2: Create the corpus using the given sentences. Further, create stop_words to 
remove commonly used words.
Step 3: We create a function to eliminate the stop words from the corpus in order to 
increase the efficiency.
Step 4: Count the number of words in the corpus
Step 5: Then we spilt the corpus and Set individual words from the corpus and store
the index position of the words. Using window size as 2, we will use skip gram to 
generate the labels for each individual word in the corpus.
Step 6: We convert the labels in one hot encoding. Further, convert them as numpy 
array. Set placeholder for the training data and embedding dimension as 2. Create 
the hidden and output layer and the training operation.
Step 7: Train the data x_train and the labels
Step 8: Create vector table for the hidden layer
Step 9: Create the graph to visualise the words in 2d using padding as 1.
