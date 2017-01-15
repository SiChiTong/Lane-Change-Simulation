# autonomous-driving-decision-making
This is an C++ implementation of lane change decision making in simulated autonomous driving, path planning and markov decision process as well as particle filters are considered for vehicle intention prediction.

The hybrid A* search algorithm not only use the graph based A* search algorithm but alos includes the veicle dynamic constraint in path planning. A possible search path to avoid static and dynamic object is:
![](img/path0.png)

In order to make right decision making, it is possible to search for multiple path and then select the best path:
![](img/path1.png)


The color changes reflect the driver intention changes when observing the lane change signal.
![](img/noncoop.gif)
