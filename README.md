#include <iostream>
using namespace std;

 int main(){
   int arr[] = {3,5,4,1,9};
   int n = sizeof(arr)/sizeof(int);
   int max = arr[0];
   int min = arr[0];
   for ( int i=0; i<n; i++){
      if (arr[i] > max){
      max = arr[i];
      }
         if (arr[i]<min){
            arr[i] = min;
         }
   }
   cout << max << "\n";
    cout << min << "\n";
    return 0;
   }
