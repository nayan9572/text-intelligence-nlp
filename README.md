# Text Intelligence: My NLP Projects (IMDb Sentiment & News Classification)

## What This Project Is About

Hey there! This repository holds two of my Natural Language Processing (NLP) projects, where I really got to dive deep into making sense of text data:

1.  **IMDb Movie Review Sentiment Analysis:** Here, I built models to figure out if movie reviews from IMDb were talking positively or negatively about a film.
2.  **News Article Classification:** For this part, I worked on training models to automatically sort news articles into different topics, like sports, politics, or tech.

## Why I Built This (Problem Solved)

* **For Movie Reviews:** I wanted to create a way to automatically understand how people feel about movies from their reviews. This is super useful for seeing public opinion quickly, without having to read through tons of comments.
* **For News Articles:** My goal was to make it easier to organize a huge amount of news. Imagine getting thousands of articles every day – I built something that can sort them for you, making it simpler to find what you're looking for or analyze trends.

## What I Did (Key Features)

### For IMDb Movie Review Sentiment Analysis (Part A - My Approach)

* **Data Prep:** I started by cleaning up the raw IMDb review data. This meant things like breaking sentences into words (tokenization), getting rid of common words that don't add much meaning (stopwords), and simplifying words to their root form (stemming).
* **Turning Text into Numbers:** I used techniques like TF-IDF and also explored Word2Vec to convert the text into numerical data that machine learning models could understand.
* **Building & Testing Models:** I experimented with different classification models, like Logistic Regression, Naive Bayes, and Support Vector Machines, to see which ones were best at predicting sentiment.
* **Checking How Good They Were:** After training, I evaluated my models using standard metrics like accuracy, precision, recall, F1-score, and I used confusion matrices to really see where they performed well or made mistakes.

### For News Article Classification (Part B - My Approach)

* **Data Handling:** I processed a dataset of news articles to get them ready for analysis.
* **Text Cleaning:** Similar to the movie reviews, I cleaned the news text by tokenizing and removing stopwords.
* **Feature Creation:** I transformed the textual data into numerical features, primarily using TF-IDF.
* **Training Classifiers:** I trained multi-class classification models (like Logistic Regression and Naive Bayes) to accurately categorize the articles into different topics.
* **Evaluating Performance:** I checked the models' performance using accuracy, precision, recall, F1-score, and confusion matrices to ensure they could robustly sort the articles.

## Tools I Used

* **Python** (My main programming language)
* **Libraries:** `pandas`, `numpy`, `scikit-learn` (for machine learning), `nltk` (for text processing), `gensim` (for Word2Vec)
* **Jupyter Notebooks** (Where I did most of my coding and analysis)

## How You Can Run This

If you want to try out my notebooks on your own computer, here's how:

1.  **Get the code:**
    ```bash
    git clone [https://github.com/nayan9572/text-intelligence-nlp.git](https://github.com/nayan9572/text-intelligence-nlp.git)
    cd text-intelligence-nlp
    ```

2.  **Install the necessary stuff:**
    ```bash
    pip install pandas numpy scikit-learn nltk gensim jupyter
    ```
    * You might also need to download some NLTK data (like stopwords). If prompted, just run this in Python:
        ```python
        import nltk
        nltk.download('stopwords')
        nltk.download('punkt')
        ```

3.  **Open the notebooks:**
    ```bash
    jupyter notebook "NLP_Project-Part A.ipynb"
    jupyter notebook "NLP_Project_Part B.ipynb"
    ```
    * Then, just run through the cells in each notebook to see how everything works!

## My Results and What I Learned

* **For Sentiment Analysis:** I managed to achieve high accuracy in predicting IMDb review sentiment, showing that my text processing and model choices worked well.
* **For News Classification:** I successfully built models that could categorize news articles effectively into different topics.
* Overall, these projects gave me solid hands-on experience with the entire NLP pipeline – from preparing the data to building features, training models, and checking their performance.

## Get in Touch

Feel free to connect or ask questions!
Nayan Kumar - nayanchaudhary979@gmail.com
