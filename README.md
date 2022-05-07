# PSG-HACKATHON-2022

The model we proposed is based on the graph model. All the crime , place and people type are nodes and the edges between each node represents the probabilty of that particular crime happening to the asssociated nodes.
The travel details is collected via a form, the user input is located on the graph model to make the prediction.
All the neighbouring nodes would represent the crime associated with the person class and travel destination.
The edges correspondinds to the probability of the crime happening associated with those nodes.

WHY GRAPH MODEL?
* Easy to relate districts, crimes and people class
* Easy to traverse
* Can be extended to find the nearby safe locations

Things Implemented:
* Getting the user input via form
* Modelling of the pre-processed data(given data set) using Networkx
* Fitting of the given input to the graph model
* Prediction of the crime happening to a given person class

Things Not Implemented:
* Hosting the End Product
* Calculating the Travel Safe Score using Prediction Model
* Hotline Number Recommendation
* Safe accomadation recommendation
