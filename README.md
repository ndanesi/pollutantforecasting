# pollutantforecasting
Code used in the thesis 'Short term forecasting of atmospheric air pollutants using Long Short-Term Memory'
The code was developed by Nicholas Danesi and Mayank Jain. Inside each of the files, there are instructions on downloading the data and running it; if you require more help, please email me at nick.danesi@ucdconnect.ie . Each of the models will require a little tweaking and input to get working.

The code is split into three files:
1. The webscraper (which takes meteorological and pollutant data from Queensland monitoring stations)
2. The Holt Winters triple exponential smoothing model (predicts concentrations using Holt Winters and data from Queensland monitoring stations)
3. The Long Short-term memory model predictor (predicits concentrations using LSTM and data from Queensland monitoring stations)
