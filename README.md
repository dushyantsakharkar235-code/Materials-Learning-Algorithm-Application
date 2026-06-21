The above project has taken inspiration from the work of authors of paper "L. Fiedler, N. A. Modine, S. Schmerler, D. J. Vogel, G. A. Popoola, A. P. Thompson, S. Rajamanickam, and A. Cangi, “Predicting electronic structures at any length scale with machine learning,”npj Comput. Mater., vol. 9, p. 115, 2023." and has been done as a side project for a course to prove that Neural Networks can reeduce the computation cost for real world systems that DFT just cannot compute due to its computation costs.



The project 1.ipynb contains the code base for the NN. The NN used is MALA(Materials Learning Algorithm), of which can be downloaded from git.com\mala-project 

I have also uploaded the project Report that I submtted for grading during the course; it contains all the mathematical framwork of the and background of the project for which extensive work was put in for it to actully work outide of the given paper that i mentioned above. If anyone is intrested they can read it



Lastly I have also committed an working model that i have saved if you want to directly work with the model and predict on your berilium system. the accuracy is good enough as in the range of 100 meV.

What makes this beautifull that if you have a large dataset of any other material that you are working on you csn simply change the input files for the training and the model will train accordingly to your given input files and validation data. Since MALA is an Leaky Relu network it learns the properties of materials very easily and predicts a good LDOS on very minimum data althought having a large data set and a good validation data set is recomeneded. The minimum can be achieved with just one trainigndataset and one validation data set 
