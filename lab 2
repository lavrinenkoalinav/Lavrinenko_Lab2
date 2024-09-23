#include <iostream>
#include <Windows.h>
using namespace std;

int main()
{
    SetConsoleCP(1251);
    SetConsoleOutputCP(1251);

    int number;
    int factorial = 1;
    cout << "Введіть значення: " << "" << endl;
    cin >> number;


    if (number < 0) {
        cout << "Факторіал від'ємного числа не визначено." << endl;
    }
    else {
        for (int i = 1; i <= number; ++i) {
            factorial *= i;
        }
        cout << "Факторіал числа"<< " " << number << " " << "=" << " " << factorial << endl;
    }

    return 0;
}
