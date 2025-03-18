# Classifying-human-or-machine-generated-texts

The objective is to identify human or machine-generated texts.

1. Data Collection (Data_Collection.ipynb)
   Scraped human-generated text from Wikipedia, Aljazeera News, and Gutenberg books using BeautifulSoup.
   Generated synthetic text using GPT-2 via the Hugging Face library.
   Collected 10,244 samples in total, preprocessed by removing duplicates, links, and non-alphanumeric characters.
   Final dataset saved as final_combined_dataset.csv.

2. Data Analysis (Data_Analysis.ipynb)
   Applied One-Hot Encoding and TF-IDF feature extraction techniques.
   Conducted exploratory data analysis to understand text patterns.

4. Deep Learning-Based Classification (Deeplearning_based_Classification.ipynb)
   Implemented a LSTM-based deep learning model to classify text.
   Addressed overfitting by tuning LSTM size and dropout layers.
   Evaluated performance using different training strategies.
