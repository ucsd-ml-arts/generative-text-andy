# Project 1 Generative Text
Jiaye Wang    jiw609@ucsd.edu



## Abstract

This project is going to use RNN to generate text base on different training data. 
The goal of the project is to configure out if we can tell the generated text have different writting style from related genre.
The training data is especially important cause the generated text will be based on the training data. 
I am planning use different fictions from different genre as training data.
ALthough the machine learning model will not produce meaningful text, I want to test if the computer will generate similar writting style. 

I am going to pass some non-english speaking international masterpiece(The Analects of Confucius) and english speaking masterpiece into the RNN learning model. 

The goal is to check if I can tell the difference of each generated text.

I will use the same seed and the same training model for different fiction genres to see how different will be the outcome.
The training model will be the same for each genre. 

## Model/Data


- trained models: RNN
- training data (or link to training data):
http://www.gutenberg.org/cache/epub/3330/pg3330.txt')#The Analects of Confucius (from the Chinese Classics) by Confucius
'https://archive.org/stream/TheLittlePrince-English/littleprince_djvu.txt'#  the little prince

## Code

Your code for generating your project:
- training_code.py or training_code.ipynb - your training code
- generative_code.py or generative_code.ipynb - your generation code

## Results

- Documentation of your generative text in an effective form. A file with your generated text (.pdf, .doc, .txt). 

## Technical Notes

I try to change different hyperparameters to make the outcome more meaningful. By changing the temperture hypermeter low and embedding dim high, I am getting a more meaning ful text. The outcome difference between different trainning data is also more significant. 

## Reference

References to any papers, techniques, repositories you used:
- Papers
  - [This is a paper](this_is_the_link.pdf)
- Repositories
- Blog posts
