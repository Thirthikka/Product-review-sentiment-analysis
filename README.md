# Product-review-sentiment-analysis
The analysis develops an automated approach for identifying customer sentiment from product
reviews. The objective is to classify reviews into **positive, neutral and negative categories** so
that businesses can identify customer satisfaction, concerns and areas requiring attention. The
dataset contains 1,007 reviews, with duplicates removed and no missing values. After
exploratory analysis, the reviews are converted into contextual embeddings using the pre-trained
all-MiniLM-L6-v2 Sentence Transformer. The embeddings are divided using an 80:20
stratified split and classified using Random Forest and Gradient Boosting models. Accuracy and
F1-score are used for evaluation. Random Forest achieves approximately 86.5% test accuracy
and 81.8% F1-score, while Gradient Boosting records 84.07% accuracy and 80.3% F1-score.
The higher test performance of Random Forest makes it the preferred model. Although the
models show a training-test performance gap, the results demonstrate that sentence-level
transformer embeddings can effectively capture customer review semantics and support
automated sentiment analysis.
