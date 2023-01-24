# IMDB-Movire-Review
# The Full pipeline to go from the raw form to the prepared form
__A - Text preprocessing__
   1- Data sequencing: each sentence be sequence (list) of words
   2- Data cleaning: This step varies from task to task. For some tasks it's better to remove special characters and punctuations, for other they are critical (emotiocons).
   3- Text normalization: in general text morphology is a big issue in NLP. Upper and lower cases, stemming and lemmatization, ... etc. It's task dependent.
   4- Padding (model dependent): Dense and CNN. RNN can skip this step.
__B- Text preparation__
   5- (Binarization/vectorization/digitization): transform words into numbers according to a vocab index.
