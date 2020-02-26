# Geographic Feature Engineering

_Geography_ is the study of places and the relationships between people and their environment. - [National Geographic](https://www.nationalgeographic.org/education/what-is-geography)

## Why Machine Learning?

* Data Driven 
	* Using data to learn the variables
	* Trying to learn a model from some variable
	* If you cannot write down what that model is, then machine learning can help
* 11 Factors (normally seven) - [Science Alert](https://www.sciencealert.com/science-discovers-human-brain-works-up-to-11-dimensions)
* All models are wrong, but some are useful. - [George Box](https://en.wikipedia.org/wiki/All_models_are_wrong)

## What is a Feature?

### GIS

> A representation of a real-world object on a map. - [Esri GIS Dictionary](https://support.esri.com/en/other-resources/gis-dictionary/term/dcc335be-78ae-4bd2-b254-b44c37343f75)

### Data Science

> A machine learning _feature_ is an individual measurable property or characteristic of a phenomenon being observed. The concept of _feature_ is related to that of explanatory variable. - [Wikipedia](https://en.wikipedia.org/wiki/Feature_(machine_learning))

## Feature Engineering

> _Feature engineering_ is the process of using domain knowledge to extract features from raw data via data mining techniques...to improve the performance of machine learning algorithms. - [Wikipedia](https://en.wikipedia.org/wiki/Feature_engineering)

Using GIS and data science tools and methodologies to create quantitative measures of geographic relationships and phenomena used for machine learning model development.

## Feature Contemplation

How far is the the Esri campus?

- destination
	- "Esri campus"
	- Building Q - 380 New York Street, Redlands, CA
- Proximity Measurement
	- drive distance
	- drive time
	- morning rush hour drive time
	- evening rush hour drive time
	- weekend drive time

How far away is _your_ home?

- straight line distance
- drive distance
- travel time
	- total travel time
	- flight time

Does the sun affect driving safety?

- azimuth delta between driving direction and sun direction
- azimuth above horizon
- slope affecting azimuth above horizon
- cloud cover
- vegetation density

Tracking Animals

- bird flight
- migration

Hiking

- trails
- off trail

## Topics and Use Cases

### Accident Prediction
 
- Question or Problem
- Features

### Customer-Centric Analysis

- Question or Problem
	- Assessing and Forecasting Physical Retail Store Location Value
- Features
