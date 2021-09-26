# Exercise1
c++ Basix exercise 
#include <iostream>
#include <string>
using namespace std;

int main()
{
 double x;
    double y;
    cout << "Enter the temperature in Fahrenheit to be converted into celcius\n";
    cin >> x;
    y = (x - 32) * 0.5556;
    cout << "The temperature in Celcius is: " << y << endl;
}

