# Fake-news-classification-using-LSTM
Classification of news as fake or real using Long short term memory (LSTM). LSTM is a type of recurrent neural network that succeeded to overcome the limitations of RNN such as gradient vanishing and exploding. ![1_7cMfenu76BZCzdKWCfBABA](https://user-images.githubusercontent.com/76652458/190478118-c0f0158b-a137-477f-83ee-659b5dc86bc3.png)



Here the texts need to be preprocessed before applying LSTM. The steps invloved in text preprocessing are: 
1. Stemming- which is a technique used to extract the base form of the word by removing affixes. 
2. One hot representation- vector representation of words in a vocabulary 
3. Word Embedding- learned representation for text in which words that have simiar meaning get similar representation. 

The model was trained using Jupyter Notebook. The dataset used here can be found on kaggle. 
# References 
1. https://machinelearningmastery.com/gentle-introduction-long-short-term-memory-networks-experts/
2. https://towardsdatascience.com/lstm-recurrent-neural-networks-how-to-teach-a-network-to-remember-the-past-55e54c2ff22e
