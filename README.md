# ML Linear Regression Assignment Bikes Sharing:
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Provide general information about your project here. <br>
	A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is 	finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to 		accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
	
- What is the background of your project? <br>
	BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to 	Covid- 19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from 	other service providers and make huge profits.
	
- What is the business probem that your project is trying to solve? <br>
	They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to 
  	understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
  		a. Which variables are significant in predicting the demand for shared bikes.
  		b. How well those variables describe the bike demands
	
- What is the dataset that is being used?<br>
	 The day.csv dataset and the readme.txt files are used as the datasets.


## Conclusions

The R-squared value for both test and training datasets is withing **10 %** of each other. <br>
The R-squared of the Test data set is  **0.805** and the The R-squared of the Training data set is **0.841**. The difference is **4%**.<br>


For the test and training dataset the difference between the R-squared and R-squared adjusted is within **1 - 5%**. 
    Training : 
    The R-squared of the Training data set is **0.841** and the Adjusted R-squared of the Training data set is **0.837**.
    The difference is **0.4%**
    Test : 
    The R-squared of the Training data set is **0.805** and the Adjusted R-squared of the Training data set is **0.793**.
    The difference is **1.2%**.

The Rsquare and Adjusted Rsquare of the test set are 0.805 and 0.792. Which is a good enough measure.

The demand of bikes depends on factors like<br>

1. Year
2. Working Day
3. Temperature
4. Windspeed
5. Light Rain/Snow
6. Mist
7. January
8. July
9. September
10. Saturday
11. Spring
12. Summer
13. Winter

We can derive the equation as

The demand for bikes = 0.165 + (2.346 x Year) + (0.054 x Working Day) + (0.472 x Temperature ) - (0.157 x Wind Speed) 
                       - (0.289 x Light Rain/Snow) - (0.080 x Mist + Cloud) - (0.039 x January) - (0.046 x July) + (0.073 x September) 
                       + (0.066 x Saturday) - (0.060 x Spring) + (0.044 x Summer) + (0.077 x Winter)



## Technologies Used
- pandas version 1.5.3
- numpy version 1.24.3
- matplotlib version 3.7.1
- seaborn version 0.12.2
- python version 3.11.4
- sklearn version 1.3.0
- statsmodels version 0.14.0


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the EDA module, Data Visualization module and the Linear Regression module tutorials and the  of the Upgrad AI and ML program.

- This project was based on Linear Regression module of the Upgrad AI and ML program.


## Contact
Created by @siddharthr193 - feel free to contact me!
