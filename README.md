# Spatiotemporal pRF demo
Demo for spatiotemporal pRF mapping 

Scripts were developed and validated using MATLAB 2020b (Mac OS/Linux). 
Contact: Insub Kim (insubkim@stanford.edu)

## Dependencies
- SpatiotemporalpRF [Link](https://example.com)
- PRFmodels [Link](https://github.com/vistalab/PRFmodel)
- Vistasoft [Link](https://example.com)

## Overview
To generate and solve spatiotemporal pRF, there are three pRF models currently implemented:

- Spatial (Dumoulin & Wandell, 2008)
- Delayed Normalization spatiotemporal (DN-ST)
- Compressive spatiotemporal (CST)


---------------------------------------------
The demo follows three steps:

1. Synthetic timecourse generation.
It takes stimulus information and a JSON file as input and generates synthetic timecourses for the three different pRF models (spatial, DN-ST, and CST).

2. Solve
Solve the parameters for each model. Synthetic timecourses generated for each model are solved by the same model.

3. Check performance
Compare the ground truth and predicted timecourses for each model, and plot the results.

---------------------------------------------

References
Dumoulin, S. O., & Wandell, B. A. (2008). Population receptive field estimates in human visual cortex. Neuroimage, 39(2), 647-660.

Lerma-Usabiaga, G., Benson, N., Winawer, J., & Wandell, B. A. (2020). A validation framework for neuroimaging software: The case of population receptive fields. PLoS computational biology, 16(6), e1007924.

Zhou, J., Benson, N. C., Kay, K., & Winawer, J. (2019). Predicting neuronal dynamics with a delayed gain control model. PLoS computational biology, 15(11), e1007484.

Stigliani, A., Jeska, B., & Grill-Spector, K. (2019). Differential sustained and transient temporal processing across visual streams. PLoS computational biology, 15(5), e1007011.
