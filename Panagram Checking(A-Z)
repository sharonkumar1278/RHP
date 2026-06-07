#include <iostream>
#include <string>
using namespace std;

int main() {
    string str;
    getline(cin, str);

    int upper = 0;
    int lower = 0;

    for (char ch : str) {
        if (ch >= 'A' && ch <= 'Z') {
            upper |= (1 << (ch - 'A'));
        }
        else if (ch >= 'a' && ch <= 'z') {
            lower |= (1 << (ch - 'a'));
        }
    }

    int allLetters = (1 << 26) - 1;

    if (upper == allLetters && lower == allLetters)
        cout << "True";
    else
        cout << "False";

    return 0;
}
