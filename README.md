1️⃣ Preprocessing the Emails
Before feeding the emails into our model, we had to clean and prepare the text:
🔹 Converted everything to lowercase
🔹 Removed stopwords (common words like "the", "is", etc.)
🔹 Tokenized the text (split it into words)
🔹 Used TF-IDF (Term Frequency-Inverse Document Frequency) to convert text into numerical format

2️⃣ Training the Model
We tested different machine learning models, but Logistic Regression performed the best. It learned patterns in the emails and became really good at detecting spam!

3️⃣ Testing & Results
Once trained, the model was able to accurately classify spam emails. It correctly flagged phishing emails and promotional spam while keeping normal emails safe.

