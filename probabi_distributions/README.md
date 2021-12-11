## Description of Project

<p>This project was made under the guidance of an online course.
The prob_distributions package is used to calculate and plot Gaussian/ Normal and Binomial distributions.</p>

### Instructions

Import prob_distributions and it contains following classes:

1. Gaussian class

   Gaussian distribution class for calculating and visualizing a Gaussian distribution.
	
	Attributes:
		mean (float) representing the mean value of the distribution
		stdev (float) representing the standard deviation of the distribution
		data_list (list of floats) a list of floats extracted from the data file
    
    Syntax: Gaussian(mean, stdev)

    Methods available:
    1. calculate_mean() : it calculates mean
    2. calculate_stdev(sample=True) : calculates standard deviation (if passing population then sample=False)
    3. plot_histogram() : plots histogram
    4. pdf(x) : probabilty density function
    5. plot_histogram_pdf(n_spaces = 50) : plots graph for probability density function
    6. add(gaussian1, gaussian2) : it adds two gaussians
    7. repr() : output the characteristics of the Gaussian instance

2. Binomial class

    <p>Binomial distribution class for calculating and visualizing a Binomial distribution.</p>
    
    Attributes:
        mean (float) representing the mean value of the distribution
        stdev (float) representing the standard deviation of the distribution
        data_list (list of floats) a list of floats to be extracted from the data file
        p (float) representing the probability of an event occurring
        n (int) number of trials
    
    Syntax: Binomial(mean, stdev, prob, size)

    Methods available:
    1. calculate_mean() : it calculates mean
    2. calculate_stdev(sample=True) : calculates standard deviation (if passing population then sample=False)
    3. replace_stats_with_data() : Function to calculate p and n from the data set
    3. plot_bar() : plots bar graph
    4. pdf(k) : probabilty density function
    5. plot_bar_pdf() : plots graph for probability density function
    6. add(binomial1, binomial2) : it adds two binomial distributions
    7. repr() : output the characteristics of the binomial instance