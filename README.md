# Speech-Recognition -- To be Updated
This is a first draft. In README file, I will be updating how the sampling rates were set, how hop length was calculated for an audio file of length of 2-4 sec. How start and finish sampling rates were calculated and what role MFCC plays when extracting the audio features in addition to how to reduce noise and increase accuracy. In upcoming versions, I will look into how to handle files of larger and varied lengths. Currently, this accuracy is quite low due to limited audio data and will be looking into different hyper parameters that can reduce over fitting. In this model, I only used regularization to reduce overfitting to certain extent. 

(Update) - Adding the second version of the same audio data set in which achieved accuracy of 98% on train data and 94% on test data after carrying out some manipulation at data preprocessing level - the stage at which one-hot encoding was used for target labels/classes.
