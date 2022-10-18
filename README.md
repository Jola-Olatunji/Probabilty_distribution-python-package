# probability-distributions package
probability_distributions is a python package for calculating gaussian 
and binomial statical distribution. It can also be used for adding two 
gaussian distribution  distributions together aswell as two binomial 
distributions with the same P values. and can help to visualize the distributions.

# Files
The python package has two major python modules.
## Binomialdistribution:
performs statistical calculations and visualization for Binomial distributions such as:

- Read in dataset
- Calculate mean
- Calculate standard deviation
- Plot histogram
- Plot probability density function

## Gaussiandistributions:
Performs statistical calculatons and visualization for Gaussian distributions such as:

- Read in dataset
- Calculate mean
- Calculate standard deviation
- Plot histogram
- Plot probability density function


#Installation
The python package has been uploaded to Pypi.org you can pip install.

Usage:
here is an example usage

**instantiating a class object**
gaussian_one = Gaussian(5,2)

**reading in a file**
gaussian_one.read_data_file('number.txt')

**calculate mean and standard deviation of the distribution**
gaussian_one.calculate_mean()
gaussian_one.calculate_stdev()

**Add two gaussian**
gaussian_two = Gaussian(10,1)

gaussian_new = gaussian_one + gaussian_two
