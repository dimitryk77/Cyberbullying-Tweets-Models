### Classification of Cyberbullying Tweets Using LSTM, GRU, CNN, and Transformer Models
The paper explores the efficacy of LSTM, GRU, CNN, and Transformer models for text classification of cyberbullying tweets. The analysis consists of 8 experiments (12 models in all) and utilizes a dataset of more than 47,000 cyberbullying tweets and the Keras library in Python. The experiments start with data cleaning and EDA. The next five experiments utilize cross-validation and hyperparameter tuning to test various structures of LSTMs, GRUs, their bidirectional counterparts, and CNNs. These experiments utilize trained embedding and pre-trained tweet-based GloVe embeddings. The last two experiments involve an attention-based transformer and a fine-tuned DistilBERT model. The best model from the analysis is the DistilBERT model, which obtained an 89.44% accuracy on the test set.

**Software:** Python, Keras/TensorFlow

**Methods:** LSTMs, GRUs, CNNs, Transformers, GloVe Embeddings, Cross-validation and Hyperparameter Tuning.

[Link to Paper](https://drive.google.com/file/d/1pVNc4LXxP6sw9A7DGvD6xWizAn3vEtdq/view?usp=sharing) 

[Link to Code](https://github.com/dimitryk77/Cyberbullying-Tweets-Models/tree/main/Model_Code)  
