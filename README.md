# Practical-4-2-
#include <iostream>
using namespace std;

inline int mult(int a, int b) {
    return a*b;
}
int main() {
    int num1, num2;
    cout << "Enter the first number: " << endl;
    cin >> num1;
    cout << "Enter the second number: " << endl;
    cin >> num2;
    int result = mult(num1, num2);
    cout << "Multiplication is: " << result << endl;
    return 0;
}
