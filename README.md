# Fundamentals_of_Programming - Lab 2: C++ Sum and Miles Per Gallon — Build, Test, and Explain with AI

# Course Section
## CIS-165-B030

## Initial Plans for Sum and Miles Per Gallon Programs
### sum.cpp
I plan to make 2 separate integer variables to store the values 50 & 100. I will then add the 2 variables together and then store the result in an integer variable called total. Finally, I will show the result.

### mpg.cpp
I plan to make 2 separate double variables to store the values 312 & 16. I will then divide the miles by the gallons and then store the result in a double variable called miles_per_gallon. Finally, I will show the result.

## Testing the Programs
| Program and test | Values used | Expected results | Actual results | Match or correction |
|---|---|---|---|---|
| Sum — assigned values | 50 & 100 | Total = 150 | Total = 150 | Match |
| Sum — changed values | 25 & 75 | Total = 100 | Total = 100 | Match |
| MPG — assigned values | 312 miles & 16 gallons | 19.5 MPG | 19.5 MPG | Match |
| MPG — changed values | 250 miles & 12 gallons | 20.8333 MPG | 20.8333 MPG | Match |

## Explaining my code
### Sum — How do the starting values move through the calculation into total and then to the output?
The starting values are 50 and 100 and the program stores both values in variables & then adds them together. The result is stored in a variable called "total", which contains the value 150. Finally, the program displays the total.

### Sum — Why store the calculation in total before printing?
The calculation is stored in the variables called "total" before printing because it separates the calculation from the output and helps in making the code easier to both read & understand.

### MPG — What is the formula?
The formula is the number of miles divided by the number of gallons. For the values that were assigned, the calculation is 312 / 16, which equals 19.5 MPG.

### MPG — What data types did you choose?
I chose the double data type for the miles, gallons, and miles_per_gallon variables since the result of MPG can contain a decimal value and should remain precise and exact. Using the double data type in this scenerio keeps the fractional result.

### MPG — What can happen if C++ performs division using two integer operands?
If C++ performs division using two integer operands, the fractional part of the result would be removed. For example, 250 / 12 using integers would produce 20 instead of ~20.8333 since it cuts off the decimal digits.

### MPG — Trace your changed-value test from the values through the result.
For my changed-value test, I used the values 250 miles and 12 gallons. The program divides 250 by 12 and then after the this, it stores the result in the variable called "miles_per_gallon". The result is ~20.8333 MPG.

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

# I restored the originally assigned values in both .cpp files before my final upload, and ran both files again. 
