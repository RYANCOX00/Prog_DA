# Steps for running the code

<br>

1. To run this code a user will require Python 3 and the below listed packages to be installed.  It is recommended that a user downloads Anaconda as these particular packages are already pre-installed.  You can find a link to Anaconda [here](https://www.anaconda.com/products/individual).  Alternatively, Python 3 can be installed [here](https://www.python.org/downloads/). 

<br>

2. Should the user decide not to use Anaconda. He/ she can install the below the packages by calling the below on their command line:  

- pip install pandas
- pip install matplotlib
- pip install numpy 

<br>

3. Installing cmder is recommended for users on Windows machines. cmder can be downloaded [here](https://cmder.net/). The command line on Linux and Mac is suitable.   The code is public and therefore can be pulled from GitHub by anyone. 

<br>

4. A user can interact with the code by running _jupyter lab_ in the command line from the local directory that this repository is pulled to. Jupyter will launch in their default browser. 

<br>

5. Sometimes Github does not render Jupyter Notebooks correctly.  If this occurs, you can view a static version of the Notebook on nbviewer by clicking this icon below.   [![nbviewer](https://user-images.githubusercontent.com/2791223/29387450-e5654c72-8294-11e7-95e4-090419520edb.png)](https://nbviewer.org/github/RYANCOX00/Prog_DA/blob/main/Numpy_Random.ipynb). 

***

# Sumary ofthe Assignment

<br>

The purpose of the assignment is to discuss and demonstrate the use of the Numpy Random package in Python.  The assignment has four distinct tasks.  

<br>

## 1. Explain the overall purpose of the package.

Here I introduced the Numpy package before delving into the Random sub-package.  A reader can expect an introduction to the 3 categories of function and their relevance and use in data analysis. 

<br>

## 2. Explain the use of the “Simple random data” and “Permutations” functions.

<br>

The user can expect to learn the how to generate Random numbers without complexed algorithms. These include obtaining random integers, floats, and outputting random choices from a set range.  In relation to the former 2, numbers within the range have an equal probability of being generated.  In relation to the choice function numbers have equal probability of being chosen by default, however their probability of being chosen can be set.  I have demonstrated this by running a programme based on a rigged raffle.  

For Permutations, this relates to items of an array can be shuffled.  I have demonstrated this by shuffling up 10 individuals to create two teams of 5 individuals for 5-aside soccer. 

<br>

## 3. Explain the use and purpose of at least five “Distributions” functions.

The reader can expect to a brief introduction of the 5 statistical distributions below and the associated Numpy random function.  Real world examples were used when appropriate.  

1. Normal Distribution
2. Poisson Distribution
3. Uniform Distribution
4. Weibull Distribution 
5. Biomial Distribution

## 4. Explain the use of seeds in generating pseudorandom numbers.

The reader can expect to learn about pseudorandom number generators and how random the Numpy random function is not truly random.  The concept of seeding is discussed, and a demonstration is given on how to seed on the new default PRNG - PCG64, and the older PRNG - Mersenne Twister.  I have also discussed how the new PRNG is far superior to its predecessor Mersenne Twister. 