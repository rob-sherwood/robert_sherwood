# Project Proposal

__Name__: Robert Sherwood<br/>
__Semester__: Spring 2020<br/>
__Project Area__: Geotechnical Engineering

## Background

The K-State Civil Engineering Department is currently conducting research on rialroad ballast: characterizing the suction properties of fouled ballast using soil water characteristic curves (SWCC). A transient water release and imbibition method (TRIM, Wayllace and Lu 2012) is in use. The TRIM measures the two-step outflow of an unsaturated sample (such as fouled ballast) and then models the SWCC using an inverse method. Three to five hours of data processing are typically required for production of premium SWCC modles using this method. Processing includes extracting and formatiting model ouput, and creating fugures of results. Much of this work is being exicuted manually in Excel. Characterization of fouled ballast will outlast the academic careers of several master's students; therefore, a thoughtfully-designed autimated-process would help productivity throughout the course of the project especially as new students beging to work on it. 

## Objective

The objective of this coding project is to autimate as much of the aformentioned processes as posible. It should facilitate faster data processing and faster creation of figures. It should also increase the itegrity and repetability of results by cutting out manually performed steps in each category. 

## Outcomes
* Open the out.txt file of the inverse modeling sofware.
* Read the imortant data from the out.txt file and save it to a table in python: SWCC data, the route mean squared error (RMSE) and regression coefficient (R^2).
* Return a plot of the SWCC and a .csv file with the SWCC data, and the RMSE and R^2 information.

## Sketch: conceptual layout of code.
<img src="Flow diagram3.png" alt="Flow diagram3" width="800"/>

## References
Wayllace, A., & Lu, N. (2012). A transient water release and imbibitions method for rapidly measuring wetting and drying soil water retention and hydraulic conductivity functions. Geotechnical Testing Journal, 35(1), 103-117.