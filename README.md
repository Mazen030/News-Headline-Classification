# News-Headline-Classification
# 🎯 Project Objective
To automatically classify news headlines and descriptions into predefined categories (e.g., business, sports, tech, etc.) using advanced NLP and deep learning techniques.
# ⚙️ Techniques and Methods Used
1. 🔍 Exploratory Data Analysis (EDA) 
- Dataset inspection 
- Category distribution visualization with pie charts and count plots.

# 2. 🧹 Data Cleaning & Text Preprocessing
Merging title and description columns

Removing:
- Punctuation (up and down types)

- Emojis

- HTML tags

- URLs (http, www)

- Hashtags and emails

- Non-ASCII characters
- Lowercasing all text

- Decontracting words (e.g., "won’t" → "will not")

- Stripping extra whitespace  

# 3. 🔠 Linguistic Preprocessing
- Tokenization using NLTK

- POS tagging with nltk.pos_tag

- Lemmatization using WordNetLemmatizer with POS mapping

- Stopword Removal using NLTK’s English stopwords list

# 4. 🧪 Data Splitting

- Train/test split using train_test_split

- Stratification based on category labels

- 80% training / 20% testing

 # 5. ✨ Text Vectorization
- Tokenization using Keras Tokenizer
- Texts converted to sequences

- Padding sequences to fixed length using pad_sequences
# 🤖 Models Used
# 1. 🧠 Simple RNN
- A basic recurrent neural network

- Suitable for short sequences

- Fast but limited in capturing long-term dependencies

# 2. 🔁 LSTM (Long Short-Term Memory)
- Handles long-range dependencies

- Avoids vanishing gradient problem

- Effective for sequence modeling

# 3. 🔁 GRU (Gated Recurrent Unit)
- More efficient alternative to LSTM

- Comparable performance with fewer parameters

- Faster training time


