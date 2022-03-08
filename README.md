# Sentiment Analysis using CNN

data for building of this model can be downloaded here http://cs.stanford.edu/people/alecmgo/trainingandtestdata.zip

## Why CNNs in text classification?
The filters/kernels in CNNs can help identify relevant patterns in text data – bigrams, trigrams, or n-grams (contiguous sequence of n words) depending on kernel size. Since CNNs are translation invariant, they can detect these patterns irrespective of their position in the sentence. Local order of words is not that important in text classification, so CNNs can perform this task effectively. 

Each filter/kernel detects a specific feature, such as if the sentence contains positive (‘good’, ‘amazing’) or negative (‘bad’, ‘terrible’) terms in the case of sentiment analysis. Like sentiment analysis, most text classification tasks are determined by the presence or absence of some key phrases present anywhere in the sentence. This can be effectively modelled by CNNs which are good at extracting local and position-invariant features from data. 

Hence we have chosen CNNs for our intent classification task.
