# Face-Recognition
A pose aware recognition system based on eigen faces built on python. I have used publically available ["Labelled faces in Wild"](http://vis-www.cs.umass.edu/lfw/) dataset to train and test the system.  
###Prerequisites  
1. Python 2.7 and libraries listed below  
	-[Scikit-learn](http://scikit-learn.org/stable/)  
	-[NumPy](http://www.numpy.org/)  
	-[SciPy](https://www.scipy.org/)  
	-[MatPlotLib](http://matplotlib.org/)  
2. [LFW](http://vis-www.cs.umass.edu/lfw/) database.  

###How to run  
The driver code is a python code which can be run using terminal. The code has been tested on a system with Ubuntu 16.10 with 4Gb RAM.
On Ubuntu make sure the funneled version of LFW dataset is present in ~/scikit_learn_data/lfw_home. The location may vary according to platform but should not matter if sklearn.datasets imports without error.  
To run the code follow these steps:  
	1. Open terminal and navigate to folder containing "face_recognition.py" file.  
	2. Run the file using the command "python face_recognition.py".  
###Author
Anmol Singhal  
2015A7PS069P  
BITS Pilani.
