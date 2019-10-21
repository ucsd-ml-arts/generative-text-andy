# Project 1 Generative Text
Jiaye Wang    jiw609@ucsd.edu



## Abstract

This project is going to use RNN to generate text base on different training data. 
The goal of the project is to configure out if we can tell the generated text have different writting style from related genre.
The training data is especially important cause the generated text will be based on the training data. 
I am planning use different fictions from different genre as training data.
ALthough the machine learning model will not produce meaningful text, I want to test if the computer will generate similar writting style. 

I am going to pass some non-english speaking international masterpiece(The Analects of Confucius) and english speaking masterpiece into the RNN learning model (the little prince). 


![Image of confusi](https://github.com/ucsd-ml-arts/generative-text-andy/blob/master/analect.jpg)
![Image of prince](https://github.com/ucsd-ml-arts/generative-text-andy/blob/master/prince.jpg)




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

Ancient Chinese writing style text generator--The Analects of Confucius.ipynb

Modern English writing style text generator--littleprince.ipynb


## Results
The difference between these two generate text is huge. We can easily distinguish which genre is the generated text from.
The RNN ML model successfully learn the learning data's writting style. 

## sample output:

The little prince:
----------------------------------------------------------------------------------------------------------

he say to him. I felt awkward and blundering. I did not know how to draw anything except boa constrictors 
from the outside and boa constrictor in the act of swallowing an 
animal. Here is a copy of the drawing. 

In the morning where I came to the grown-ups, and asked them whether the drawing frightened them. 
But they answered:Fright 
save me so much to do! I am concerned with matters of consequence. I 
dont amuse myself with bald, and the recollinise it was not 
beauty that she wished to appear. Oh, yes! She was such a proud flower... 



He found himself in the desert, and I had listened to the story 
of the merchant as I was drinking the of 
a little boy who is just like the grown-ups who 
are no longer interested in matters of consequence. 

The little prince went away, to look again at the roses. You are not at all like my rose, the little prince repeited said. 

I shall look as if I were suffering. I shall look a little as if I were suffering. I shall look a little

---------------------------------------------------------------------------------------------------------------
The Analects of Confucius (from the Chinese Classics)
------------------------------------------------------------------------------------------------------------
he saying, "It is not this being beneficent without
great expenditure? When the man of high station is well instructed, he loves millen the arree was answered, 'Baithere like a would not walk on foot to get a
shell for him, but I say that he walks shoulder to
shoulder with his sovereign, I believe he was not straight, he did not sit of multies, he is aware of that.'
        CHAP. XIII. The Master said, 'Shan, my doctrine is that of an
all-pervading upon the land, but neither of them did
a former wickednesses of men in mind, and hence the
resentments directed towards them were four things from which the Master was
entirely free. He had no foregone conclusions, no arbitr frme from the world all the stars turn towards it.'
        CHAP. III. The Master said, 'The superior man has nine things
which are subjects with him of thoughtful contrary to propriety; speak not what is contrary to
propriety; make no movernment?' and was answered, 'I am not you will not be fit to converse with." I

## Technical Notes

I try to change different hyperparameters to make the outcome more meaningful. By changing the temperture hypermeter low and embedding dim high, I am getting a more meaning ful text. The outcome difference between different trainning data is also more significant. 

It is also very interesting that if the epoch is too large; the model will over trained. It will keep output the same text line. Hence, a number of 50 will be enough. 



References to any papers, techniques, repositories you used:
- Papers
  - [This is a paper](this_is_the_link.pdf)
- Repositories
- Blog posts
