# Restaurant-Review-Using-NLP-and-Machine-Learning

## Why Sentiment Analysis?

Understanding customer feedback has become more crucial than ever. Sentiment analysis helps restaurant owners and managers quickly gauge customer feelings about their dining experience. This insight is invaluable for:

- **Identifying Strengths:** Highlighting what customers love, whether it's a specific dish, friendly service, or a cozy atmosphere.
- **Addressing Weaknesses:** Spotting common complaints or issues, like slow service or a noisy environment, allowing for timely improvements.
- **Enhancing Customer Satisfaction:** By understanding and acting on customer feedback, restaurants can tailor their offerings and service to better meet expectations, creating a more satisfying dining experience.



![Image](https://github.com/user-attachments/assets/799eeb66-74dd-4870-925f-6d8d0cc2f33b)


## Project Workflow: Restaurant Review Sentiment Analysis

1. **Data Preprocessing:**  
   I started with a diverse dataset of restaurant reviews, cleaning and prepping the text for analysis. Key steps included:
   - **Lowercasing:** Ensuring consistency by converting all text to lowercase.
   - **Punctuation Removal:** Stripping away unnecessary punctuation to reduce noise.
   - **Tokenization:** Breaking down sentences into individual words or tokens.

2. **Custom Stopwords:**  
   One of the interesting challenges was deciding which words to keep or remove. While standard stopwords are usually stripped away, I recognized that certain words like "not" or "but" are crucial in understanding sentiment. This led to the creation of a custom stopword list, allowing me to fine-tune the preprocessing and retain words that significantly impact sentiment analysis.

3. **Feature Extraction: Converting Words to Numeric Vector**  
   Using techniques like CountVectorizer, I transformed the cleaned text into numerical data that models can understand. This step is akin to recognizing patterns in word usage across positive and negative reviews.

4. **Sentiment Classification: Building the Model**  
   With the features ready, I trained machine learning models using an ML algorithm to classify the sentiment of reviews. ML algorithms like Support Vector Machines (SVM) helped build a robust model that can predict whether a review is positive or negative with impressive accuracy. They are widely used for textual data because they effectively handle high-dimensional feature spaces.

5. **Key Insights and Learnings**  
   The process underscored the importance of retaining critical words that could drastically alter sentiment. Words like "not" can completely flip the meaning of a sentence, making custom stopwords a vital part of the preprocessing pipeline. This fine-tuning ensures that the models aren't just accurate but also contextually aware.

![Image](https://github.com/user-attachments/assets/31144d15-c174-41b6-8f91-b014cc8c2b9d)

