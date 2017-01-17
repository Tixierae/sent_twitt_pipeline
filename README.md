* notes from 1/17/2017 Irina's progress report presentation:

 * data collection: when you build the positive and negative sets, make sure you eliminate tweets that are both positive and negative (some tweets may contain both pos and neg emoticons). Also, make sure re-tweets are not taken into account.
 
 * try with 3 classes (adding neutral). You can use for instance the Twitter accounts of some famous newspapers to collect neutral tweets.

 * implement the entropy and salience techniques for feature selection like in Pak and Paroubek (2010).

 * to measure performance, make sure you use 'accuracy' N(correct classifications)/N(all classifications)

 * to evaluate performance in English, you can use the external test set of Go et al. (2009) which you can find [here](http://help.sentiment140.com/for-students) under the section 'Where is the training data?'.

 * try with SVM, Naive Bayes and Maximum Entropy classifier of [Go et al. (2009)](http://cs.stanford.edu/people/alecmgo/papers/TwitterDistantSupervision09.pdf)

 * read this very relevant paper: [Go et al. (2009)](http://cs.stanford.edu/people/alecmgo/papers/TwitterDistantSupervision09.pdf). 

 * try to take into account the part-of-speech tag of the words. This will differentiate when the same word (with the same spelling) is used as an adjective, noun, or verb.
 
  * do some error analysis to see what caused the tweets that were misclassified to be misclassified

 * in addition to the code, upload the data files to github
 
 * Note that in the final report, the 2-3 important papers will need to be briefly summarized in a small literature review section. Also, in the final report, add a brief theoretical introduction for the data representation used (e.g., doc-term matrix with TF-IDF weights) and learning algorithms that you compared. The final presentation and report delivery is forecasted to take place early in March.