## Fake-News-Detection-using-BiLSTM
-Built a deep learning model to classify news headlines as real or fake using a Bidirectional LSTM. Focused on reducing false positives and false negatives through careful data cleaning, dropout, and class balancing. Achieved 89% accuracy and 90% recall on a dataset of ~800 labeled headlines using 300D embeddings.

## Features
-Binary classification: real vs. fake headlines
-Bidirectional LSTM with dropout to prevent overfitting
-Custom text preprocessing: stopword removal, stemming
-Tokenization and padding with Tokenizer and pad_sequences
-Trained on ~800 labeled headlines

## Model Performance

 Metric         Score                   
 Accuracy       89%                      
 Recall (Fake)  90%                      
 F1-score       89%                      
 Dataset Size   824 samples (balanced)   

## technology used
-Python
-TensorFlow / Keras
-NLTK (stopwords, stemming)
-Scikit-learn (metrics, train/test split)
-Pandas, NumPy

## Dataset
-This project uses the Fake and Real News Dataset from Kaggle.
-It includes labeled news headlines categorized as real or fake, used here for training and evaluation.

 ## Acknowledgments
-Special thanks to [Krish Naik](https://www.youtube.com/@krishnaik06) for his amazing tutorials and guidance on deep learning and NLP.
-This project was inspired by one of his videos on fake news detection using BiLSTM.
-You can find more of his work on GitHub and LinkedIn.

## Feedback
If you have feedback. Please reach out to 19devadharshini@gmail.com

## License
[MIT License](LICENSE)
