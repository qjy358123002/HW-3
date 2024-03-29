# HW-3
Model Construction
====================

> Put up with a conceptual model

> Simplify the model

Data process
---------------------

> Get the all the data from sensor and make a dataframe for the model

> Get the low pass signal for temperature, soil moisture and humidity

> Establish a linear relationship and get a coefficient between saturation and soil moisture reading

Parameter Calculation
---------------------

> water volume = area * sensor_length * porosity * water_coefficient

> Evaporation term relating humidity and temperature

> Set the time Index

Model Test
---------------------

> Results plot

Discussion
====================

> For sensor side, intially to prevent the situation that data from only one set is not reliable, meanwhile, if we can have multiple sets of sensors, we can compare each set to get a reliable range of data and normalize the data if needed. However, three sets of sensor turn out to have three trends. Apparently, the bottom line can be ignored since we have rain during the collection period, but it does not show any fluctuation and the fluctuation in the end was becasue we took out the sensor from soil. The green trend can be assumed that after the rain fall, water accumulated in the soil layers, at least the area around the sensor, and did not decrease by plantuptake infiltraton or drainage. The blue trend can be assumed a water cycle around the sensor area so we see soil moisture fluctuates two times, or becasue of some other reason.

> For model side, firstly, only a single and linear term is apparently not enough to simulate the actual situation and we spent lots of time in sensor setup at the beginning period but without a nice feedback. In the future work, more complex and differential term should be taken into consideraion for the model and better sensor should be selected.

> Finally, I really appreciate my teamates and they did a fantastic job on the project. During the discussion, I learned a bunch of hands on code skills and get to know sensor setup step by step, moreover, the tools learned in the class are really helpful and the knowlege learned in the class not only give me a glimpse into a new field for me, but also enlight my path in future study and see other possibilites.
