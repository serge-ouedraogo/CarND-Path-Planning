### Path Planning for a Self-Driving Car

#### Goals
In this project the goal is to safely navigate around a virtual highway with other traffic that is driving +-10 MPH of the 50 MPH speed limit. The car goes as close as possible to the 50 MPH speed limit, which means passing slower traffic when possible, while other cars try to change lanes too. The car avoids hitting other cars at all cost as well as driving inside of the marked road lanes at all times, unless going from one lane to another. The car makes one complete loop around the 6946m highway going at 50 MPH max
The car localization and sensor fusion data are provided, together with a sparse map list of waypoints around the highway. 

#### The project contains the following files:
1. **BehaviorPlanner.cpp**: The actual implementation of the path planner is done here.
2. **GenPath.cpp**: This file contains classes to generate a path by converting waypoints coordinates from cartesian to Fresnet coordinate system
3. **JMT.cpp**: This file contains classes to smooth the trajectory by implementing a Jerk minimization algorithm
4. **Vehicle.cpp**: This file contains classes that represent the ego vehicle and any other vehicle that is detected by sensor fusion.
5. **main.cpp**:  This file implements communication with the simulator.

#### Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./path_planning`.

