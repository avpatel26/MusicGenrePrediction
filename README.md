# Music Genre Prediction

This repo analyse supervised Machine Learning algorithms(Naïve Bayes, logistic regression, Decision tree), for automatically identify the genre of a song on the basis of its audio, metadata and textual features.

### File Description

1) AudioandTextFeatures.ipynb\
  This file loads the audio and text features and converts the text features in numeric data using one hot encoding in preprocess function.

2) MetadataandTextFeatures.ipynb\
  This file loads the metadata and text features and converts the text features and title in numeric data using one hot encoding in preprocess function.

3) MetadataandAudioFeatures.ipynb\
  This file loads the metadata and audio features and converts the title in numeric data using one hot encoding in preprocess function.

All the notebook files performs Naive Bayes, Logistic Regression, Decision Tree and zero-R baseline classifier and train and predict the genre of the music. In the evaluate function they are using confusion matrix.

### Dataset

T. Bertin-Mahieux, D. P.W. Ellis, B. Whitman, and P. Lamere. The million song dataset. In
Proceedings of the 12th International Conference on Music Information Retrieval (ISMIR),
2011.

A. Schindler and A. Rauber. Capturing the temporal domain in Echonest Features for improved
classification effectiveness. In Proceedings of the 10th InternationalWorkshop on Adaptive Multimedia Retrieval (AMR), 2012.

### Features

* trackID: unique identifier for each song 
* title: title of the song
* tags: A comma-separated list of tags representing the words that appeared in the lyrics of the song 
* loudness: overall loudness in dB
* tempo: estimated tempo in beats per minute (BPM)
* time_signature: estimated number of beats per bar
* key: key the track is in
* mode: major or minor
* duration: duration of the song in seconds
* vect_1 ... vect_148: 148 columns containing pre-computed audio features of each song. These features were pre-extracted from the 30 or 60 second snippets, and capture timbre, chroma, and mfcc aspects of the audio
 
