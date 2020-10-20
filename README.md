# Deep Learning Approaches to Fake News Detection
- Explored a number of core deep learning algorithms for their performance in detecting fake news.
- Employed data augmentation techniques to increase the size and quality of the training data set.
- Also made use of GloVe word vectors to enable the algorithms to learn the data.

## Code and Resources Used
__Python Version__: 3.6.9 \
__Libraries__: tensorflow, keras, spacy (en_core_web_sm), nltk, numpy, pandas, pickle, sklearn, matplotlib, seaborn, math, os \
__GloVe__: https://nlp.stanford.edu/projects/glove/ \
__LIAR Dataset__: https://github.com/thiagorainmaker77/liar_dataset

## Approach
The main goal was building a fake news detection model which generalizes well to different settings. The selected approach is illustrated by the following figure: <br/> <br/>
![alt text](https://github.com/MaximilianGoepfert/Deep-Learning-Approaches-to-Fake-News-Detection/blob/master/ExperimentialDesign(1).png "Experimental Design")

## Conclusions
- Using data augmentation we were able to increase prediction accuracy by 5.1% compared to a similar architecture that did not make use of data augmentation.
- The Gated Recurrent Unit (GRU) performed best out of the selected algorithms.
- In order to achieve state-of-the-art accuracies on the LIAR dataset it is necessary to also perform a metadata analysis.
  + 'Credit history' is the metadata parameter that needs to be included to reach the state-of-the-art.
