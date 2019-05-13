# H1-B-Visa-Prevailing-Wage-Prediction
The objective of this project is to predict the prevailing wage that is at optimum.

![alt text](https://github.com/shreyaswankhede/H1-B-Visa-Prevailing-Wage-Prediction/blob/master/H1B-01.png
 "Correlation between features")
***

<h3>What’s H-1B Visa ? & what’s the problem.</h3>
<p>The U.S. Department of Labor’s Office of Foreign Labor Certification releases annual data on various visa applications, including the H-1B. The H-1B is a non-immigrant visa that allows U.S. companies and organizations to temporarily employ foreign workers in specialty occupations.</p> 
<h5> Problem </h5>

* One of the biggest things to consider, when somebody applies for Labor Condition Application ( LCA ) to file H1B visa is to look at the minimum wage or prevailing wage in the area you plan to work on H1B visa.

* For employer setting up wage could be tedious since it depends upon multiple factors like location, job title, No. of workers etc. setting up wage lower than minimum could lead to H1-B rejection and even setting higher wage could result to the loss for a company.
 ***
 
<h5>End-user:</h5>  Employer

<h5>Dataset:</h5>

* The H-1B Visa Application dataset include fields like Visa Class, Status, Employer location, 	Prevailing Wage, Total number of workers, employment start and end date etc. which are the 	applications for  the H-1B visa lottery who was accepted into the lottery but not who won a visa.The dataset contains 624,650 rows and 53 fields.

* Sources: https://public.enigma.com/datasets/h-1-b-visa-applications-2017/e1ee0ae8-13f4-444f-804e-9a429b32f424
***

* <h5>Data Loading and Cleaning</h5>
* <p>Checking missing values in data. 
* <p>Imputing values.
* <p>Checking the outliers using boxplot.
* <p>Removing extreme outliers of features</p>

***

 <h4>Data Analysis and Visualization</h4
 
 * Checking Correlations between different features.

![alt text](https://github.com/shreyaswankhede/H1-B-Visa-Prevailing-Wage-Prediction/blob/master/H1B-02.png
 "Correlation between features")
 
***

* Checking Distributions in different features.

![alt text](https://github.com/shreyaswankhede/H1-B-Visa-Prevailing-Wage-Prediction/blob/master/H1B-05.PNG
 "Correlation between features")

***

 <h5> Feature Enginnering & Feature Selection</h5>	
 
 * After the several iteration over selecting features, checking co-relation and going back and forth while cleaning the data, we came about selecting few features which can good for our model
 
 * Performing One Hot Encoding on categorical columns
 
 *** 
 
 <h5> Model Building & Result </h5>
 
* Performing Linear Regression Model and Regularization.

 ![alt text](https://github.com/shreyaswankhede/H1-B-Visa-Prevailing-Wage-Prediction/blob/master/H1B-04.PNG
 "Correlation between features")
 
***

<br>Thank You!	
<p><!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/shreyaswankhede" aria-label="Follow @shreyaswankhede on GitHub">Follow @shreyaswankhede</a>
