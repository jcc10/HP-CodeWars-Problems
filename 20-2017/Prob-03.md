# Time of Flight Sensor

**Points: 3**

## Summary
You probably already know that light travels really, really fast. Really. However, you may not know that you can use light to measure distances by timing how long it takes a pulse of light to reflect from a surface. A working TOF sensor requires really high speed electronics because light travels 0.299792 millimetres per picosecond. The most amazing part is you can buy a Time-of-Flight sensor online for less than $20. It's true. No, really. It's pretty cool, to. Look it up after the contest.

So, anyway, given a number of picoseconds elapsed for a reflection, you can calculate the distance to the reflecting object and back (in millimetres) by simple multiplication. Write a program to calculate distances for a Time of Flight sensor.

```
distance = time * 0.299792
```

## Input
The program input consists of three positive integers, each on a separate line. These numbers are reflection times ranging from 100 picoseconds to 1,000,000 picoseconds.  
```
150
917203
32767
```

## Output
The program must print the calculated distances, in millimetres, for each input value. The result must be accurate to within +/-1 millimetre.  
```
44.9688
274970.121776
9823.284464
```


---  

**The Cut.**  

---

## Problem
Multiply a number by a fixed number. (and do it for two other numbers.)

## Data / Equations / Notes
### Equations
```
distance = time * 0.299792
```
### Notes
Remember that input is fully separated from output, this means that you can print before receiving the next line of input.

## Formatting
### Input
Three numbers (100 <= INT <= 1,000,000) separated by line breaks.
### Output
The n'th number multiplied by `0.299792`.

## Test Cases

### Case 1:
#### Input
```
150
917203
32767
```
#### Output
```
44.9688
274970.121776
9823.284464
```
