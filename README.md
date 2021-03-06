# The SeFiRe field recording dataset

The repository contains the *SeFiRe dataset* - a dataset of annotated field recording samples that can be used for training audio labelling algorithms. The dataset contains 5 second long clips extracted from a variety of field recordings. Each clip is labelled with one label describing its contents as:
* s: speech
* 1: solo singing (one voice)
* 2: choir singing (more than one voice, can also be unison)
* i: instrumental (vocals may also be present)
* x: (background) noise or a very noisy clip belonging to one of the above categories.

You will find two folders in the repository. *Samples* contains five second audio samples, their annotations are given in _sample labels.txt_, which is a tab-delimited text file. *External samples* contains annotations of five second clips extracted from a number of online sources. We can't include the clips in the dataset, but we provide links to audio files with the location of each extracted clip and its label in _external sources.txt_. 

Feel free to use the dataset for your research, if you use it, please cite the following paper:
* M. Marolt, C. Bohak, A. Kavčič, and M. Pesek, [Automatic segmentation of ethnomusicological field recordings](https://www.mdpi.com/2076-3417/9/3/439/pdf), Applied sciences, vol. 9, iss. 3, pp. 1-12, 2019, [https://doi.org/10.3390/app9030439](https://doi.org/10.3390/app9030439)



