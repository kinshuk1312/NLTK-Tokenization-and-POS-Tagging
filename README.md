# NLTK-Tokenization-and-POS-Tagging

### Stemming 
Stemming is a process, in which we reduce our words to their word stem. In stemming, it is not necessary for these stem words to have a meaning.

eg. We have a set of words as: {'history' and 'historical'} , and we apply stemming on it, the stem word which we get is 'histori'

{'history', 'historical'} -------(Stemming)--------> {'histori'}
{'finally', 'final', 'finalized'}-------(Stemming)--------> {'fina'}
Applications of Stemming:

Since it is not necessary for stem words to have a meaning, the main applications of Stemming are found as classifying positive and negative words to sort reviews, or to do spam or not spam classification in e-mails.

### Lemmatization
Lemmatization is similar to stemming, but here the reduced words are called Lemmas and have a meaning.

eg. We have a set of words as: {'history' and 'historical'} , and we apply lemmatization on it, the stem word which we get is 'history'.

{'history', 'historical'} -------(Lemmatization)--------> {'history'}
{'finally', 'final', 'finalized'}-------(Lemmatization)--------> {'final'}
Applications of Lemmatization:

Since the reduced words in Lemmatization tend to have a meaning, we can use Lemmatization, in applications like Chatbots, in which our machine comprehends meaningful words to give a reply to the user.

### Part Of Speech Tagging
Part Of Speech Tagging is a process in which we convert sentences to form list of words, or list of tuples. In this, each tuple contains element in form: {word, tag}. Using this tag, we can classify whether the word given is a noun, adjective, verb and so on. Basically, the main job here is classifying the type of words.
