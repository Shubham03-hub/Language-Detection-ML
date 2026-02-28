## Language Detection with Machine Learning
This project is about creating a machine learning model that can automatically identify the language of any given piece of text. Using natural language processing (NLP) techniques, I preprocess the text to make it easier for the model to understand, then classify it into the correct language.

### Why does this matter?
As the internet becomes more and more multilingual, having an automatic way to detect languages is pretty much essential. It’s useful for a lot of things, like:
- Keeping online content appropriate through moderation
- Powering chatbots that support multiple languages
- Improving translation tools
- Refining search engine results
- Filtering social media content
My goal with this project is to build a reliable, solid language classification model that can handle these kinds of tasks effectively.

### The dataset - 
I used a multilingual text dataset that includes samples from various languages. It’s a supervised dataset, meaning I trained the model with labeled examples so it can learn to recognize different languages accurately.

### Tools and technologies
To put this together, I relied on:
- Python
- Pandas and NumPy for data handling
- Scikit-learn for machine learning
- NLP techniques like TF-IDF and CountVectorizer for text vectorization
- Jupyter Notebook or Google Colab for development

### How I approached it
1. Cleaning and preprocessing the data
2. Converting text into numerical form with TF-IDF
3. Training my machine learning models
4. Evaluating how well they performed
5. Measuring accuracy to see how reliable the system is

### The models I used
I experimented with a couple of classifiers:
- Naive Bayes
- Logistic Regression

Both models used TF-IDF vectors to understand the text better.
The results are pretty encouraging — I achieved accuracy rates between 98% and 99%. The model also shows stable performance across cross-validation tests, which suggests it’s pretty reliable for practical use.

