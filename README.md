# Emerging-Technologies - Mateusz Pawlowski - G00361162
This is my solution to all 4 tasks that we were given by our lecturer throughout the year. All the tasks have been completed in jupyter notebook (python language). The tasks were as follow:
* **Square root of number 2** - We needed to get the square root of the number 2 and made sure it goes to 100 decimal points. The trick to it was we were no allowed to use any imports during this task. Even though it sounds easy, it took me some time in order to get it properly working. Most of the problem was that, it would only print out aronund 50 numbers after the decimal (after that it would be 0's). However, after doing my research I found a solution.
* **Chi Square Test** - Chi Square Test is a statistical hypothesis test. Used in order to analyse wheter to categorical variables are independent. In this task, we had to find the p-value and the chi squared value from the data we have recieved (also can be found on wikipedia). From doing the test we get 4 values. The p-value, chi square value, degrees of freedom and expected frequencies. I had to do some research first to understand the test itselft but after some time, I proceeded with coding and got my answers.
* **Standard Deviation** - This task was more about research than coding itself, we were supoosed to see why sample standard deviation is a better estimate for the standard
deviation of a population when performed on a sample data. The code was actually given to us and in order to find population standard deviation you use: using *numpy* as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) and for sample standard deviation it was the same except the division is done by len(x) -1. 
* **Iris Data Set** - The iris data set consists of three different types of irises, Setosa, Versicolour, Virginica. From these types, four features were measured from each sample, the length and width of sepals and petals. This tasks made us find the iris data set then plot it, and later on explain how our model could be used to make predictions of species of iris. I found this task very interesting and challenging at the same time. I first plotted the iris data set and showing off each cluster with a different colour. Then I created a dummy data and plotted those points on to the graph and showed how each dummy data is predicted to be in a particular cluster.

## Instalation
* Go to the official anaconda website: https://www.anaconda.com/ (very handy way to install python packages.)
* At the top of the website, there is a bar and hover over products and press "individual edition".
* Press the download button or go to the very bottom of the site to see all your ways to donwlad.
* Choose which option suits you and download it. (If you have anaconda alread I recommend to remove it before installing a new version.)
* When installing anaconda I recommend to tick the box saying "Add anaconda to my PATH enviroment variable".
* This should also install jupyter on your device.
<br>

* Create a folder on your desktop.
* Open up your cmd (Command Prompt) and direct yourslef to that directory.
* Type in git clone https://github.com/MateuszPawlowski/Emerging-Technologies
* Go into the new folder and type in "jupyter notebook".
* Press the "Tasks.ipynb" file.
* From there in order to run everything press "kernel" located at the top bar.
* Press "restart and run all", this will bring up a pop up. Press "restart and run all cells" again on the pop up.
