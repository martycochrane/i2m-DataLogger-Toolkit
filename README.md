# i2m DataLogger Toolkit

The i2m software can be a bit tricky to do fast and effective analysis to solve advanced problems.

This toolkit is a very early version of something similar to what you can find in my BMW M1000RR Toolkit [here](https://github.com/martycochrane/BMW-M1000RR-Electronics-Analytics)

## Bikes Used to Collect data

|MPC Racing Yamaha R1           |Triple M Racing Ducati V4R     |
|-------------------------------|-------------------------------|
| ![Yamaha](/img/yamaha.JPG) | ![Ducati](/img/ducati.jpg) |


## Getting Started with the toolkit

### Export Data From i2m

Make sure you export the data for the lap or session you want to analyis using a csv format like below. Don't use the "filled version"

![Export Data](/img/export.png) 

### Set correct variable names in code

It's important to set the variable names to the same as the file name you've exported and also the name of the sensors you use for the front and rear suspesnion

![Variable Names](/img/variableNames.png) 

### The circuits JSON file

Here you will find GPS co-ordinates for the finish line at different circuits around the world. If yours is missing then please add it and create a pull request to this repository so we can keep it updated

![Circuits](/img/circuitsJSON.png) 

### Fastest Lap Circuit Trace

Unfortunately i2m only let's you export a full session and not individual laps. You will see in some of the examples a filtering of each lap and then removing everything but a certain lap. In the speed trace case it's the fastest lap shown

![Fastest Lap](/img/fastestLap.png) 

### Histograms

This is still in it's early version as some more data filtering and cleaning will be needed to make it more meaningful but for now here's the overview

![Histograms](/img/histogram.png) 