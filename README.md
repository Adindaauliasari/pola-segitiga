#include "iostream"

using namespace std;
 
int main()
{	
    int rows, i, j, k, l = 1;
    cout << "--------------------------\n";
    cout << "-- Segitiga Sama Sisi   --\n";
    cout << "-- Balog18.blogspot.com --\n";
    cout << "--------------------------\n";
    cout << "Masukkan Tinggi :";
    cin >> rows;
    for (i = 1; i <= rows; i++) {
        for (j = 1; j <= rows - i; j++) {
            cout << " ";
        }
        for (k = 1; k <= i; k++) {
            cout << k; 
            cout << " ";
        }
        cout << "\n";
        k = k - 1;
    }
    return 0;
}
