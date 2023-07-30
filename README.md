# Emotions
A model to predict the emotion of a sentence with around a 93% accuracy across 6 classes.
# Procedure
Start by embedding the sentences using GLOVE.  Then using the idea from the paper _Sentiment Analysis
of Comment Texts Based on BiLSTM_ a list of words that are known to be attributed to positive and negative
feelings is created.  Any words that appear in the list are assigned a weight of 2 to allow the model to pick
up what words contribute more to sentiment analysis.
