# Beijing-Air-Quality-Analysis
The official report states that the annual concentration of PM2.5(atmospheric particulate
matter with diameter less than 2.5mm) in 2016 has declined by 9.9% relative to the 2015
level. Here, we analyze the data from 12 different locations in and near Beijing. We have
420768 samples and 17 features in this dataset. 15 of those are numerical variables which
include hourly data from 1st March, 2013 to 28th February 2017 of various pollutant
levels (PM2.5, PM10, SO2, NO2, CO and O3)
1
. Apart from that information, we also
have the temperature, pressure, precipitation, wind direction and wind speed of the data
all of which are recorded in accordance to the station where the data was measured.
A substantial part of China is experiencing chronic air pollution with severe fine particulate matter (PM) concentration and PM2.5 in particular. The north China Plain
(NCP) that surrounds Beijing endures the most severe air pollution in the country with
excessive PM2.5 concentration. In a move to clear up the smog, China’s State Council
has set a 25% PM2.5 reduction target for the NCP by 2017 relative to the 2012 level, and
a specific target of no more than 60µgm−3
for Beijing’s annual average. Our target here
in this project is to find out how all the efforts at reducing air pollution in the Beijing
airspace is effecting the pollutants in the air. We aim to create a time series model which
can predict the various pollutant levels for the later months of 2017. We use the instances
from 1st March 2013 to 31st December 2016 as training data, and the rest as test data.
