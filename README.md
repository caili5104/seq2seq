Neural Machine Translation by Jointly Learning to Align and Translate:

http://arxiv.org/abs/1409.0473

Explanation of tensorflow seq2seq code:

https://www.tensorflow.org/versions/r0.8/tutorials/seq2seq/index.html

How to read data (look at TFRecords):

https://www.tensorflow.org/versions/r0.8/how_tos/reading_data/index.html#reading-from-files

Also:

https://github.com/tensorflow/tensorflow/blob/0c3f116837b08957630eba996d83e517d47e38ac/tensorflow/g3doc/how_tos/new_data_formats/index.md


Given a question, a candidate answer, and a document, our model asks "how closely 
does the world described by this question/answer pair match the world described 
by this document?" The model chooses the candidate that produces the closest
match. The major advantage of this approach is that 
