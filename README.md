## Digital attendance system 
A simple attendance management impplemented in C++
## Development environment 
vs code 
c++ complier

## Your name  
Frimpong charles 01243416D
#include <iostream>
#include <vector>
#include <string>
#include <iostream>
using namespace std;

int main() {
    float celsius;
    float fahrenheit;

    // Ask user for temperature
    cout << "Enter temperature in Celsius: ";
    cin >> celsius;

    // Convert to Fahrenheit
    fahrenheit = (celsius * 1.8) + 32;

    // Output result
    cout << "Temperature in Fahrenheit: " << fahrenheit << endl;

    // Bonus conditions
    if (celsius < 0) {
        cout << "Freezing!" << endl;
    }
    else if (celsius > 30) {
        cout << "Hot!" << endl;
    }

    return 0;
}


