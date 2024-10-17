 I used the CHB MIT Dataset.The dataset composed of long-term scalp EEG data for 22 pediatric subjects with intractable seizures and one recording with missing data. The sampling rate of the acquired EEG signals is 256 samples per second with 16-bit resolution.

For the implementation, out of the 22 subjects in the dataset now, I have only used one subject for seeing the authenticity of the code.
I implemented using two methods, ResNet and Rocket Classifier. In our experiments, the preictal duration was chosen to be 30 minutes before the seizure onset and interictal duration was chosen to be at least four hours before or after any seizure.The window size for segment extraction is set to 2 seconds.
