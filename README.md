
## Content 

* [x] 00 - Introduction to real-time DA from a Bayesian perspective, and state estimation on the Van der Pol oscillator
* [x] 01 - Augmented formulation for combined state and parameter estimation on the Van der Pol oscillator
* [x] 02 - Real-time DA and Chaos: combined state and parameter estimation on the Lorenz 63 model
* [x] 03 - Time-delayed longitudinal thermoacoustics: the Rijke tube  
* [x] 04 - Real-time DA and time-delays: combined state and parameter estimation on the Rijke tube ([Nóvoa & Magri 2022](https://doi.org/10.1017/jfm.2022.653))


***


## Getting started

From the terminal:

1. Clone repository: ```git clone https://github.com/andreanovoa/Real-time-DA-tutorials```
2. Access the repository: ```cd path-to-repo ```
3. Create virtual environment with anaconda and activate environment:
   ```
   conda create --yes --name da-env python=3.9
   conda activate da-env
   ```
4. Install the required packages for the repository:
   ```
   pip install -r requirements.txt
   ```
5. Access the tutorials folder and launch the jupyter notebooks:
   ```
   cd tutorials
   jupyter lab
   ```
Note: if the environment ```da-env``` is not listed in jupyter lab run the following in the terminal and restart the notebook:
```
ipython kernel install --user --name=<da-env>
```



****
*Last updated May 2025. Please don't hesitate to submit issues or pull requests if you find any errors!*














