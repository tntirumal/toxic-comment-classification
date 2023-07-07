# Data Analysis and LSTM Model for Toxic Comment Classification

In this project, I performed a comprehensive data analysis on toxic comments and developed a neural network model using LSTM (Long Short-Term Memory) for classifying these comments. The model achieved an impressive accuracy of 96.83%.

## Data Analysis Techniques

During the data analysis phase, I applied several techniques to gain insights and understand the characteristics of toxic comments. Some of the techniques utilized include:

1. **Exploratory Data Analysis (EDA)**: I conducted an in-depth exploration of the dataset to understand its structure, distribution, and potential patterns. This involved analyzing the length of comments, word frequency, and exploring relationships between different features.

2. **Venn Diagram**: To visualize the overlap between different categories of toxic comments, I used Venn diagrams. This helped identify commonalities and distinctions between different types of toxic comments, aiding in the development of the classification model.

![Venn Diagram](assets/venn_diagram.png)

3. **Word Cloud**: I generated word clouds to visualize the most frequent words in toxic comments. This provided an intuitive representation of the words that appear most often and helped identify prominent themes or patterns.

![Word Cloud](assets/word_cloud.png)

4. **Data Preprocessing**: To prepare the data for the LSTM model, I performed various preprocessing steps such as removing punctuation, converting text to lowercase, tokenizing text into individual words, and removing stop words. These steps ensured that the data was in a suitable format for training the model.

5. **Word Embeddings**: I used pre-trained word embeddings like Word2Vec or GloVe to represent words as dense vectors. These embeddings capture semantic relationships between words and help the LSTM model better understand the context of the toxic comments.

6. **Data Augmentation**: To increase the diversity of the training data and improve the model's generalization, I employed data augmentation techniques such as random deletion, random swap, and random insertion of words.

## LSTM Model

The LSTM model was chosen due to its ability to effectively capture the sequential nature of text data and handle long-term dependencies. The model architecture consisted of an embedding layer, LSTM layer, and fully connected layers.

The LSTM layer utilized a bidirectional approach to take into account both past and future context while processing the comments. This enhanced the model's ability to understand the semantics of the toxic comments and make accurate predictions.

## Model Performance

After training the LSTM model on the preprocessed toxic comment dataset, it achieved an impressive accuracy of 96.83% on the test dataset. This high accuracy indicates that the model has learned to effectively classify toxic comments with a high degree of precision.

The model's performance was evaluated using other metrics such as precision, recall, and F1-score to assess its overall effectiveness in identifying toxic comments.

## Conclusion

The combination of data analysis techniques, including Venn diagrams and word clouds, along with the LSTM model, yielded excellent results in the task of toxic comment classification. With an accuracy of 96.83%, the model demonstrates its ability to identify and classify toxic comments effectively.

This project serves as a foundation for further research and development in the area of natural language processing and content moderation.

For any questions or inquiries, feel free to contact [tirumalnanthakumar@gmail.com](mailto:tirumalnanthakumar@gmail.com).
