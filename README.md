# Fundamentals_of_Programming - Lab 2: C++ Sum and Miles Per Gallon — Build, Test, and Explain with AI

## Plans for Sum and Miles Per Gallon Programs
### sum.cpp
My plan is to create two separate int variables to store the values 50 and 100. I will then add the two variables together and store the result in an int variable called total. Finally, I will display total.

### mpg.cpp
My plan is to create two separate double variables to store the values 312 miles and 16 gallons. I will then divide the miles by the gallons and store the result in a double variable called miles_per_gallon. Finally, I will display the result with the MPG units.

## Testing my Programs
| Program and test | Values used | Expected results | Actual results | Match or correction |
|---|---|---|---|---|
| Sum — assigned values | 50, 100 | Total = 150 | Total = 150 | Match |
| Sum — changed values | 25, 75 | Total = 100 | Total = 100 | Match |
| MPG — assigned values | 312 miles, 16 gallons | 19.5 MPG | 19.5 MPG | Match |
| MPG — changed values | 250 miles, 12 gallons | 20.8333 MPG | 20.8333 MPG | Match |

## Explaining my code
### Sum — How do the starting values move through the calculation into total and then to the output?
The starting values are 50 and 100. The program stores these values in variables and then adds them together. The result is stored in the variable "total", which has a value of 150. The program then displays total using cout.

### Sum — Why store the calculation in total before printing?
The calculation is stored in total before printing because it separates the calculation from the output. This makes the code easier to read and understand.

### MPG — What is the formula?
The formula for miles per gallon is the number of miles divided by the number of gallons. For the assigned values, the calculation is 312 / 16, which equals 19.5 MPG.

### MPG — What data types did you choose?
I chose the double data type for the miles, gallons, and miles_per_gallon variables because the result can contain a decimal value. Using double preserves the fractional result.

### MPG — What can happen if C++ performs division using two integer operands?
If C++ performs division using two integer operands, the fractional part of the result can be removed. For example, 250 / 12 using integers would produce 20 instead of approximately 20.8333.

### MPG — Trace your changed-value test from the values through the result.
For my changed-value test, I used 250 miles and 12 gallons. The program divides 250 by 12 and stores the result in the variable "miles_per_gallon". The result is approximately 20.8333 MPG.

## Compiling & Running Both Programs
### sum.cpp

#### to compile
g++ -std=c++17 -Wall -Wextra sum.cpp -o sum

#### to run
./sum

### mpg.cpp

#### to compile
g++ -std=c++17 -Wall -Wextra mpg.cpp -o mpg

#### to run
./mpg
