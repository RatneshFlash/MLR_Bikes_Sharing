# Linear Regression model for bike-sharing system
> multiple linear regression model for the prediction of demand for shared bikes.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- We are building a multiple linear regression model for the prediction of demand for shared bikes.

- A bike-sharing system is a service in which bikes are made available for shared use 
to individuals on a short term basis for a price or free. Many bike share systems 
allow people to borrow a bike from a "dock" which is usually computer-controlled 
wherein the user enters the payment information, and the system unlocks it.
This bike can then be returned to another dock belonging to the same system.

- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their 
revenues due to the ongoing Corona pandemic. The company is finding it very difficult 
to sustain in the current market scenario. So, it has decided to come up with a mindful 
business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes 
to an end, and the economy restores to a healthy state. 

- Dataset Details:
=========================================
License
=========================================
Use of this dataset in publications must be cited to the following publication:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}

## Conclusions
- Final model matches have R-squared = *0.80%* on test data set
- The shared bikes "cnt" target variable can be explained by below independent variables.
=> 'yr', 'temp', 'hum', 'windspeed', 'summer', 'winter', 'Cloudy','Light Rain', 'July', 'Sep', 'Sunday'

## Technologies Used
- Pandas library - version 1.4.2
- Numpy library - version 1.21.5
- scikit-learn - version 1.0.2
- matplotlib - version 3.5.1
- Seaborn - version 0.11.2

## Acknowledgements
This project is done for study purose.
Thanks for dataset !! :-)


## Contact
Created by [@ratneshflash] - feel free to contact me!
https://ratneshflash.github.io/portfolio/


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->