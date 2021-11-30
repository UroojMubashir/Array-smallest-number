#include <iostream>
using namespace std;


int arr[10], mn;


int main()
{
    for (int i = 0; i < 10; i++) {
        cin >> arr[i];
    }
    mn = arr[0];
    for (int i = 0; i < 10; i++) {
        if (arr[i] < mn) {
            mn = arr[i];
        }
        
    }
    cout << "Smallest Integer is : " << mn;
    return 0;
}
