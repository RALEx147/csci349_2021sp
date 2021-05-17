# CSCI349 Data Mining Final project

## Overview
This project is the final project for Brian King's CSCI349, Introduction to Data Mining,
at Bucknell University. We are working on a classification project involving Hate Speech and Offensive Language.The internet is growing at an insane pace that humans cannot monitor everything posted, but site have an obligation to
prevent the spreading of hate and bullying through text. If we could categorize this and punish accordingly, it would
free up lots of time for humans to just be reviewers.We have a tweet, and it is assigned to a label of either hatespeech, offensive language, or neither. Our goal is to
create a model that can learn from those human labeled tweets to extrapolate into a general formula to determine which class
it falls under.

## Data

[Automated Hate Speech Detection and the Problem of Offensive Language
](https://github.com/t-davidson/hate-speech-and-offensive-language)


[RAW DATA](https://raw.githubusercontent.com/t-davidson/hate-speech-and-offensive-language/master/data/labeled_data.csv
)
## Video demo

https://youtu.be/


## Model

The model that we chose in the end was the Stochastic Gradient Descent.
The Convoluted Neural Network didn't work as well as we expected, albeit the average macro-f1 score increased, but the hatespeech
recognition was reduced. We thought the gloVe word embedding would at least increase the neither category accuracy, but it did help for some semantic examples such as 'I love my mom'. But in the end the CNN put too much focus on offensive language and detracted from the goal of categorizing hatespeech.

## used dependencies
pandas
<br>
numpy
<br>
sklearn
<br>
nltk
<br>
matplotlib
<br>
WordCloud
<br>
tensorflow
<br>
keras
<br>
sklearn
<br>
imblearn
<br>
mlxtend

## Resources
[Imbalanced classification](https://towardsdatascience.com/what-to-do-when-your-classification-dataset-is-imbalanced-6af031b12a36 )
<br>
[CNN text classification](https://medium.com/saarthi-ai/sentence-classification-using-convolutional-neural-networks-ddad72c7048c )
<br>
[naive bayes text classification](https://towardsdatascience.com/implementing-a-naive-bayes-classifier-for-text-categorization-in-five-steps-f9192cdd54c3)
<br>
[naive bayes research paper on imbalanced text classes](https://people.csail.mit.edu/jrennie/papers/icml03-nb.pdf)
<br>
[text classification comparison (SGD)](https://towardsdatascience.com/multi-class-text-classification-model-comparison-and-selection-5eb066197568)
<br>
[word embeddings](https://keras.io/examples/nlp/pretrained_word_embeddings/)
