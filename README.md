# COS201-ODD----EVEN
C++ program to check whether a number is odd or even

#include <iostream>
using namespace std;
int main() {
int number = 17;
cout << "Number: " << number << endl;
if (number % 2 == 0) {
 cout << number << " is an Even number.";
    }
else {
cout << number << " is an Odd number.";
    }
return 0;
}
