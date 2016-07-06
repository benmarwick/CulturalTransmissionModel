# CulturalTransmissionModel
Source codes for the paper "The effect of equilibrium assumptions on reconstructing patterns of cultural transmission from frequency data". 

## Paper Reference 
Crema,E.R, Kandler, A., Shennan, S.J. "The effect of equilibrium assumptions on reconstructing patterns of cultural transmission from frequency data"

## Author of the Repository:
Enrico R. Crema (enrico.crema@gmail.com)

## Contents
* ./src/ ... contains core simulation model for the equilibrium, variable population, and variable population/transmission versions as well as a general utility function.
* ./data/observedFrequencies.csv ... frequencies of different decorative motifs (coded BT1, BT2, ...) for phases VIII to XIV in the Merzbach assemblage
* ./logEquilibrium.R, ./logNonEquilibrium.R, ./logVarPop.R ... sample script for executing the ABC framework. 

## Licences
Text: CC-BY (http://creativecommons.org/licenses/by/4.0/)

Code: MIT (http://opensource.org/licenses/MIT year: 2014, copyright holder: Enrico R. Crema)

Data: CC0 (http://creativecommons.org/publicdomain/zero/1.0/) attribution requested in reuse

## Dependencies
R version 3.3.0 (2016-05-03)
Platform: x86_64-apple-darwin13.4.0 (64-bit)

attached base packages:
* stats
* graphics
* grDevices
* utils
* datasets
* methods
* base    

other attached packages:
* LaplacesDemon_15.03.19

loaded via a namespace (and not attached):
* parallel_3.3.0
