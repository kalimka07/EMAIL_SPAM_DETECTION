NLP Spam Detection Project

Files included in this folder:

1. NLP_Spam_Project_Colab.ipynb
   - Google Colab notebook containing all the code and outputs.
   - Steps include: loading dataset, preprocessing, training Naive Bayes model, evaluation, and testing.

2. NLP_Spam_Project_Report.docx
   - Detailed project report with Abstract, Introduction, Dataset, Methodology, Experiments/Results, and Conclusion.

3. spam_nb_model.pkl
   - Trained Naive Bayes model file (optional).
   - Can be loaded in Python/Colab for predictions without retraining.

4. vectorizer.pkl
   - Trained CountVectorizer used to transform text messages into numerical features.

Optional files:
- sample_inputs.csv
  - Example spam/ham messages and predicted results.
- charts/
  - Confusion matrix or accuracy plots (if included).

How to run the project:
1. Open the Colab notebook (NLP_Spam_Project_Colab.ipynb).
2. Upload the CSV dataset (spam.csv) if required.
3. Run all cells in order.
4. Use the function predict_spam("Your message here") to test new messages.