# Alternate Route

**Points: 3**

## Summary
A large truck carrying bismuth subsalicylate (a common antacid medication sold as a pink liquid) has collided with a passenger vehicle. Both drivers escaped unharmed, but the vehicles caught fire and the freeway has been closed while the fire is extinguished and the roadway is cleared. The cleaning is expected to take a long time because bismuth subsalicylate leaves behind a shiny metal oxide slag after being burnt. Think about that the next time you have heartburn.

Meanwhile, freeway traffic has been diverted to an alternate route for about 40 miles. Unfortunately for the motorists, the alternate route is under construction and all traffic must merge into a single lane. As you might imagine, the congestion behind this merger is causing several hours of delay for travelers. Vehicles alternate between being Vehicles alternate between being fully stopped and driving forward at very slow speeds. As the day progresses, more and more vehicles enter this mess and those coming at the end spend more time caught in the diversion than those at the beginning.

Wrtie a program to calculate the average speed of a vehicle given a number of miles traveled and the number of minutes elapsed.

## Input
The first line of input indicates how many vehicle records the program must read (up to a maximum of ten). Each vehicle record appears on a separate line and includes the number of miles traveled and the number of minutes elapsed.  
```
4
12.7 258
8.6 162
9.9 176
6.5 98
```

## Output
For each vehicle record the program must print the average speed in miles per hour. Answers must be accurate to within +/- 0.01 miles per hour.  
```
2.953488372
3.185185185
3.375
3.979591837
```


---  

**The Cut.**  

---

## Problem
For N sets of numbers (where N<= 10), calculate the average (mean not median) speed in MPH.

## Data / Equations / Notes
### Equations
```
average speed = distance / ( time in minutes / 60 )
```
### Notes
If you ask for input when there is no more input waiting, the program will hang on the test computer and will be considered a failure.

## Formatting
### Input
A single number N ( 1 <= N <= 10 )
N more lines with two numbers, separated by spaces, the first is a distance, the second is the time took in minutes.
### Output
The result of calculating the input from the N'th line.

## Test Cases

### Case 1:
#### Input
```
4
12.7 258
8.6 162
9.9 176
6.5 98
```
#### Output
```
2.953488372
3.185185185
3.375
3.979591837
```
