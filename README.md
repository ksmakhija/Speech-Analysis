Speech Analysis Project
Objective
The goal of this project is to perform textual analysis on three different speeches. The notebook applies fundamental Natural Language Processing (NLP) techniques to extract insights such as word counts, sentence counts, and the most frequently used words.

Key Tasks Performed
Text Statistics:

Counted characters, words, and sentences across all speeches.

Preprocessing:

Stopword Removal: Eliminated common English words that do not add significant meaning.

Stemming: Reduced words to their base/root form using a stemming algorithm.

Analysis:

Identified the top 3 most frequent words used across all speeches.

Technologies Used
Language: Python

Libraries:

nltk (Natural Language Toolkit) for tokenization, stopword removal, and stemming

Standard Python libraries like re and collections for text processing and frequency analysis

Instructions to Run
Open Speech Analysis.ipynb in Jupyter Notebook.

Ensure the following Python packages are installed:

bash
Copy
Edit
pip install nltk
Run the notebook cells sequentially to reproduce the analysis.

Results
Basic descriptive stats (character, word, sentence counts) were obtained.

Stopwords were filtered and stemming was applied to normalize text.

The 3 most common words across all speeches were identified, offering insight into their key themes or focuses.

Future Enhancements
Apply lemmatization instead of stemming for improved word normalization.

Visualize word frequencies using bar plots or word clouds.

Perform sentiment analysis or topic modeling.

