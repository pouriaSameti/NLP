
# The Natural Language Processing Course Projects 

These projects are related to NLP & Machine Learning for Text in English & Persian languages under the supervision of **Dr. Hamidreza Baradaran Kashani** at the University of Isfahan.

### Table of Contents
[Text Preprocessing](https://github.com/pouriaSameti/NLP/tree/master?tab=readme-ov-file#text-preprocessing)<br>
[Language models](https://github.com/pouriaSameti/NLP/tree/master?tab=readme-ov-file#language-models)<br>
[RNN, GRU & LSTM](https://github.com/pouriaSameti/NLP/tree/master?tab=readme-ov-file#rnn-gru--lstm)<br>
<br>

## Text Preprocessing
In this part, we prepare data to train a model.

### Steps
#### for Persian data
1. Text cleaning & removing emojis.
2. removing English characters and signs.
3. text normalization.
4. Tokenizing with respect to words.
5. Stopwords removal.
6. Lemmatization.

#### for English Data
1. Text cleaning and removing web addresses, and signs.
2. Remove numbers and emojis.
3. Tokenizing with respect to words.
4. Stopwords removal.
5. Showing words cloud.
 

### Installation

To Run this project, run these commands:

```python
  pip install numpy
```
```python
  pip install pandas
```
```python
  pip install matplotlib
```
```python
  pip install hazm
```
```python
  pip install nltk
```
```python
  pip install wordcloud
```
<br><br>

## Language models
In this part, we implement the elementary language models based on the probability of the tokens.

### Steps
1. Text cleaning & preprocessing.
2. Implementation of the Unigram Model.
3. Implementation of the bigram Model.
4. Implementation of the trigram Model.
5. Showing the most probable unigram, bigram, and trigram combinations based on data.
6. Calculating the probability & perplexity of test examples with unigram, bigram, and trigram models.
7. Text completion with the unigram, bigram, and Trigram models.
8. POS Tagging on the data.
9. Counting occurrence of all tokens with respect to pos tagging.
10. Showing the most observed Nouns.

### Installation

To Run this project, run these commands:

```python
  pip install numpy
```
```python
  pip install pandas
```
```python
  pip install hazm
```
<br><br>
## RNN, GRU & LSTM
In this part, we implement models for text classification.

### Steps
1. Text cleaning & preprocessing.
2. Creating vocabulary.
3. Encoding(encoding any word to its index with respect to vocabulary).
4. Applying zero padding.
5. Creating Train set, Validation set, and Test set.
6. Importing word2vec.
7. RNN Training and applying it on the test set.
8. GRU Training and applying it on the test set.
9. LSTM Training and applying it on the test set.

> [!TIP]
>  To apply word embedding, we use **Word2Vec** with 300 dimensions.<br>
> The embedding layer of all three models is frozen.<br>
> We transfer all models into GPU and train them in GPU.so you should have the **CUDA**.<br>
> The criterion of all models is **Cross Entropy** function.<br>
> The optimizer of all models is **Adam**.<br>


### Installation

To Run this project, run these commands:

```python
  pip install numpy
```
```python
  pip install pandas
```
```python
  pip install nltk
```
```python
  pip install torch
```
```python
  pip install gensim
```
