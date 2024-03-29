

# Gaussian and Binomial distributions package 'distributions_dirkkadijk'




## 1. Installation

 The code should run with no issues using Python versions 3.6 and 3.7.
 
 Matplotlib package must be installed.



## 2. Project motivations

Purpose of this Udacity Data Science Nanodegree project is to learn how to built a multi-class (and multi-module) package based on Object Oriented programming.

And to upload a self built 'distributions_dirkkadijk' package to PyPi (pypi.org) which is now available on:

https://pypi.org/project/distributions-dirkkadijk/0.1/#files



## 3. Data source

You can find the lessons, functionality and used data files in the data scientist nanodegree term 2 GitHub repo:
https://github.com/udacity/DSND_Term2/tree/master/lessons/ObjectOrientedProgramming.



## 4. Summary of the results


In folder you'll find three files:

- `Generaldistribution.py`: Generic distribution class for calculating and visualizing a probability distribution.

- `Gaussiandistribution.py`: Gaussian distribution class for calculating and visualizing a Gaussian distribution.

- `Binomialdistribution.py`: The 3rd package in the distributions_dirkkadijk package is with a new class called Binomial distribution class for calculating and visualizing a Binomial distribution.

You can click on the package py-files to look at how the 'Distribution class' and 'Gaussian class' are modularized into different files. 
E.g. the Gaussiandistribution.py imports Distribution class from the Generaldistribution.py file. The line of code:

>from Generaldistribution import Distribution


essentially pastes the Distribution code to the top of the Gaussiandistribution file when you run the code.


## 5. Licensing, Authors, Acknowledgements


 <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. Please refer to [Udacity Terms of Service](https://www.udacity.com/legal) for further information.
