#BAYESIAN INFERENCING OF DEATH RATES IN NETHERLANDS - COVID 19 PANDEMIC

A implementation for Bayesian Forecasting for the evolution of Covid 19 cases in the Netherlands. Reference: 1) https://arxiv.org/pdf/2004.02386.pdf - Modelling death rates due to COVID-19: A Bayesian approach by Cristian Bayes, Giancarlo Sal y Rosas, and Luis Valdivieso Departamento de Ciencias, Pontificia Universidad Cat´olica del Per´u 2) Data source : https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide (As of 13-April-2020) 3) Probabilistic Programming in Python using PyMC by John Salvatier, Thomas V. Wiecki, Christopher Fonnesbeck. August 3, 2015

Outstanding issues: - The posterior sampling using Hamiltonian Monte Carlo (NUTS stepper), yields an alpha that is negative to the 'seemingly' correct prediction of alpha. This has to be investigated. Possibly, try a different optimization algorithm for the estimation of the initial (start) values of the pymc3 model.
