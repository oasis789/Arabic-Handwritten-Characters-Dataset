# Arabic Handwritten Characters Dataset

### Content

The data-set is composed of **16,800** characters written by 60 participants, the age range is between 19 to 40 years, and 90% of participants are right-hand. Each participant wrote each character (from ’alef’ to ’yeh’) ten times on two forms as shown in Fig. 7(a) & 7(b). The forms were scanned at the resolution of 300 dpi. Each block is segmented automatically using Matlab 2016a to determining the coordinates for each block. The database is partitioned into two sets: a training set (13,440 characters to 480 images per class) and a test set (3,360 characters to 120 images per class). Writers of training set and test set are exclusive. Ordering of including writers to test set are randomized to make sure that writers of test set are not from a single institution (to ensure variability of the test set).

## Results

The previous SoTA was an accuracy rate of **94.1%**. Using the fastai library, I was able to achieve an accuracy rate of **96.9%** with some fine tuning. 

### Acknowledgements

Ahmed El-Sawy, **Mohamed Loey**, Hazem EL-Bakry, **Arabic Handwritten Characters Recognition using Convolutional Neural Network**, WSEAS, 2017
