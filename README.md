# Document-Classification
The document classification model was developed using a combination of LSTM (Long Short-Term Memory), SVM (Support Vector Machine), and Naive Bayes algorithms. The process began with data preprocessing, where the text data was tokenized, cleaned, lowercased, and stopwords were removed. Additionally, the text data was vectorized using TF-IDF (Term Frequency-Inverse Document Frequency) technique to convert it into numerical vectors.

Following data preprocessing, the models were trained on the preprocessed data. The LSTM model was trained to learn long-term dependencies in sequences of words for document classification. SVM, a supervised learning algorithm, was utilized to find the hyperplane that best separates different classes in the feature space. Naive Bayes, a probabilistic classifier based on Bayes' theorem, was employed with the "naive" assumption of feature independence.

After training, the performance of each model was evaluated using metrics such as accuracy, precision, recall, and F1-score on a testing set. The best-performing model was selected based on these evaluation metrics.

Finally, with the developed model, new documents could be classified into predefined categories based on their content. This classification process enabled efficient organization and categorization of various document types such as bank statements, invoices, and receipts.




