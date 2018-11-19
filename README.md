# Neuron Network

This project is a simulation of a neuron network.  
The inputs are:
* N: the amount of neurons
* pE: the proportion of excitating neurons ( the amount of inhibitors is 1-pE)
* T: the duration of a simulaton in term of steps
* λ: the average of links 

Neurons are simulated following Izhikevich's theory and are randomly linked to each other following a poisson(λ) law.
They interact in two ways: inhibition or excitation which determines whether a neuron is spiking or not. The output is a matrix filled with 1 if the neuron spiked at time T or 0 if it didn't spike.

## Getting Started


### Prerequisites

TCLAP is necessary to run the code.
Gtest is necessary to run the tests.

CMAKE **version 3.5** is necessary to compile.

### Installing prerequisites

Install Tclap and Gtest libraries in a folder named extra.

## Running the tests

Open the terminal in the build and type : **make test** or **./testNetwork**

### Tests 
* Network test :


## Built With

* CMAKE **version 3.5** 



## Authors
* **Luster Alexandre** - [Lustea0201](https://github.com/lustea0201)
* **Mohbat Julie** - [Juliemohbat1](https://github.com/juliemohbat1)
* **Nass Theo** - [TheoNass](https://github.com/theonass)
* **Rembert Nicolas** - [Renicolas](https://github.com/Renicolas)
* **Zablocki Thelma** - [thelmazablocki](https://github.com/thelmazablocki)


## Version

This simulation is at the moment only using 1 kind of neurons for each behavior



## Acknowledgments

* Based on Izhikevich's work
