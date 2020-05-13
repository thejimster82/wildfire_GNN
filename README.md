# A Graph Neural Network Approach to Wildfire Cause Prediction
This project was a collaboration between James Howerton and Mark Tenzer for the class 'UVA CS6501 Graph Mining' in the 2020 Spring semester.
## Abstract
As a means to aid those who will be tasked with investigating the
wildfires of tomorrow, we propose a new methodology for analyzing
wildfire data and predicting wildfire cause. Previous attempts to
predict wildfires’ causes have largely ignored information from
recent fires in the area. Our novel approach applies various graphneural-network (GNN) techniques involving information about
each individual fire, in addition to fires close to it spatially and
temporally, to predict the cause of any given wildfire. We utilize
24 years of geo-referenced wildfire data augmented with global
population center data and NOAA GSOD weather data. For more details, please see [our final document](.\documents\A_Graph_Neural_Network_Approach_to_Wildfire_Cause_Prediction.pdf).
## Tools
This project was developed in Python using [Tensorflow, Keras](https://www.tensorflow.org/guide/keras), and [Spektral](https://spektral.graphneural.network/). The data used to generate our results is available upon request.