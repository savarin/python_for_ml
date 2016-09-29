# Python for ML

## Installation Notes
This tutorial requires *pandas*, *scikit-learn* and *IPython* with the IPython
Notebook. These can be installed with *pip* by typing the following in terminal:

    pip install --upgrade pip
    pip install scipy
    pip install numpy pandas sklearn ipython
    pip install jupyter

Next, clone the material in this tutorial using git as follows:

    git clone git://github.com/savarin/python_for_ml.git

We will be reviewing the materials with the IPython Notebook. You should be able
to type

    jupyter notebook

in your terminal window and see the notebook panel load in your web browser.


## Presentation Format

The tutorial will start with data manipulation using pandas - loading and 
cleaning data. We'll then use scikit-learn to make predictions. By the end of 
the session, we would have worked on the 
[Kaggle Titanic data](https://www.kaggle.com/c/titanic)
from start to finish, through a number of iterations in an increasing order of
sophistication. Time-permitting, we’ll also have a brief discussion on 
cross-validation.
- [1-0_First_Cut.ipynb](http://nbviewer.ipython.org/github/savarin/python_for_ml/blob/master/1-0_First_Cut.ipynb)
- [1-1_Missing_Values.ipynb](http://nbviewer.ipython.org/github/savarin/python_for_ml/blob/master/1-1_Missing_Values.ipynb)
- [1-2_Dummy_Variables.ipynb](http://nbviewer.ipython.org/github/savarin/python_for_ml/blob/master/1-2_Dummy_Variables.ipynb)
- [1-3_Parameter_Tuning.ipynb](http://nbviewer.ipython.org/github/savarin/python_for_ml/blob/master/1-3_Parameter_Tuning.ipynb)
- [Appendix_Cross-Validation.ipynb](http://nbviewer.ipython.org/github/savarin/python_for_ml/blob/master/Appendix_Cross-Validation.ipynb)