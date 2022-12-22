StackOverflow is widely considered as one of the largest and more trusted websites for developers to learn and share their knowledge, the website presently hosts in excess of 10,000,000 questions. The users are required to tag each question before they post it. A tag is a word or phrase that describes the topic of the question and helps categorize the question with other, similar questions. Tags help connect experts with questions they will be able to answer, by sorting questions into specific, well-defined categories.

In my project I try to train a neural network such that it can process the question and come up with the best tags for it.

1. I start with a unclean dataset and clean it with my preprocessor function
2. I create a torch dataset
3. I create a Vocab 
4. I create a DataLoader for embedding
5. I use pretrained embeddings from stackexchange dataset
6. I pick a metric and tweak the model hyperparameter sto optimize for the metric
