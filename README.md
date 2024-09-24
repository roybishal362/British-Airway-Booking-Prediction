# British Airways Booking Prediction

This project analyzes British Airways customer reviews using web scraping and builds a predictive model for booking patterns. Web scraping was conducted using BeautifulSoup, and review analysis was performed with Latent Dirichlet Allocation (LDA). The final step involves building a machine learning model to predict customer booking intentions based on review sentiments.


## Project Workflow

1. **Web Scraping:**
   - Used BeautifulSoup to extract customer reviews from the British Airways website.
   - Data extracted: review titles, review body, rating, and date.

2. **Data Preprocessing:**
   - Cleaned the review text by removing stop words, punctuations, and applying tokenization.
   - Topic modeling using Latent Dirichlet Allocation (LDA) identified recurring themes in the reviews.

3. **Sentiment Analysis:**
   - Sentiment analysis conducted to understand the emotional tone of customer reviews (positive, negative, neutral).

4. **Predictive Model:**
   - Built a classification model using review features to predict customer booking behavior.
   - Models used: Logistic Regression, Random Forest, Gradient Boosting.

## Technologies Used

- **Languages:** Python (Jupyter Notebook)
- **Libraries:**
  - BeautifulSoup for web scraping
  - Pandas and NumPy for data processing
  - Scikit-learn for machine learning models
  - Gensim for LDA topic modeling
  - Matplotlib and Seaborn for visualizations

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/roybishal362/British-Airway-Booking-Prediction.git
   cd British-Airway-Booking-Prediction
## Conclusion
The British Airways Booking Prediction project provided valuable insights into customer feedback using web scraping and topic modeling techniques. By analyzing customer reviews, we identified key themes and sentiments that influence booking decisions. The predictive model successfully leveraged these insights to forecast booking behaviors, offering a practical solution for enhancing customer experience and driving business strategies. Future improvements could involve adding more sophisticated NLP techniques and expanding the dataset for greater accuracy.

