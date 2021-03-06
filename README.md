# Newton's Method

Polynomial equation solver, using Newton's Method, written in C++

## Build

Compiling the program should be straightforward. Make sure you compile with C++17 or higher as this program uses `std::optional`

`g++ src/*.cpp -std=c++17 <other options> -o newtonmethod`

## Usage

Here is an example.

```
./newtonmethod
Enter the degree of polynomial: 3
Enter 3 coefficients and a constant.
2 -1 -3 1
Enter starting value: 1.5
Solving 2x^3-x^2-3x+1=0 using Newton's method starting at x0 = 1.5
Result
x = 1.34067
```
