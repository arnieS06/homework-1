#include <iostream>
using namespace std;

// returns binary result of positive integer

int main() {
    int positiveInt = 0;
    int remainder;
    int storeBinary[32];
    int index = 0;

    cout << "please give me a positive integer -> ";
    cin >> positiveInt;

    if (positiveInt == 0) {
        cout << "\nBinary: 0" << endl;
    }

    else {
        while (positiveInt > 0) {
            remainder = positiveInt % 2;
            storeBinary[index] = remainder;
            positiveInt = positiveInt/2;
            index++;
        }

        cout << "Binary conversion is: ";
        for (int n = index - 1; n >= 0; n--) {
            cout << storeBinary[n];
        }
        cout << endl;

    }

    return 0;

    
}
