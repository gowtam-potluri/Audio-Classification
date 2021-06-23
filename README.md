# Audio-Classification

## Motivation:
Snoring, a form of sleep-disordered breathing interferes with sleep quality and quantity, both for 
the person who snores and often for the person who sleeps with the snorer. Poor sleep caused by 
snoring can create significant physical, and mental problems. There are many ways people can 
avoid this snoring if they are aware of it. This project aims to use a publicly available dataset that 
consists of 500 samples of each snoring and non-snoring sound and use different data science tools 
to classify sounds as either of the class to help alert the user. I Have built a CNN model and SVM classifier trained on the extracted MFCC features. I have also used transfer learning techniques like VGG-19 to dircetly classify on the intial dataset of the Mel Spectograms

## Impact:

Using the various feature extraction techniques like log MFCC and Mel Spectrogram, the trained 
SVM and CNN models would be able to classify the sounds as either snore or non-snore. The 
transfer learning methods would also help classify the Mel Spectrogram images to detect snore 
sounds. These methods can help bring awareness to the person with the snoring problem and could 
possibly reduce physical and mental strain leading to a better sleep cycle.
