# Sentiment Analysis on Product Reviews
## _Deep Learning Model using custom LSTM + Attention Mechanism_

This project builds an end-to-end sentiment analysis system that classifies  product reviews into Positive, Negative, or Neutral sentiments. It uses a custom LSTM architecture enhanced with an Attention Layer, trained on 19k+ reviews.

### _Features_
- Web-scraped dataset of 4k real customer reviews from flipkart and remaining form kaggle

- Custom LSTM + Attention architecture 

- Multi-class sentiment classification

- Evaluation using accuracy, precision, recall, F1-score

- Complete NLP preprocessing pipeline

- web interface for real-time prediction

- Built with PyTorch, sklearn, Selenium, Pandas

## _Tools Used_
- Programming Language: Python 3.x.
- Deep Learning Framework: PyTorch (for model and training) 
- Data Handling: Pandas for CSV handling, NumPy for numerical operations.
- Preprocessing: python libraries re, String, emoji.
- Web Scraping: Python Selenium for collecting Flipkart reviews.
- Visualization: Matplotlib for plotting confusion matrices and metric curves.
- Evaluation: sklearn for accuracy, precision, recall, F1 calculations.

  ## _Evaluation_

| Embedding | Hidden Size | Learning Rate | Attention           | Accuracy | Precision | Recall | F1 Score |
|-----------|------------|---------------|-------------------|---------|-----------|--------|----------|
| 100       | 64         | 0.0004        | Attention         | **0.98**| **0.98**  | **0.98**| **0.98** ✅| 
| 100       | 64         | 0.001         | Attention          | 0.95    | 0.95      | 0.95   | 0.95     |                
| 50        | 64         | 0.0004        | Attention          | 0.91    | 0.91      | 0.91   | 0.91     |                  
| 100       | 64         | 0.0004        | Attention Disabled | 0.90    | 0.90      | 0.90   | 0.90     |                  

For Logistic Regression and SVM, the text data were transformed into numeric features
by TF-IDF vectorization

| Model                        | Accuracy | Precision | Recall | F1_score |
|-------------------------------|---------|-----------|--------|----------|
| Logistic Regression           | 0.70    | 0.69      | 0.70   | 0.69     |
| SVM                           | 0.71    | 0.70      | 0.71   | 0.70     |
| Custom LSTM + Attention       | **0.98**| **0.98**  | **0.98**| **0.98** ✅|


<img width="480" height="240" alt="Screenshot (83)" src="https://github.com/bishal-pandey/Sentiment-Analysis-on-Product-review/blob/master/Project_Image/architecture.png?raw=true" />
                                  #### model architecture

                              

  





