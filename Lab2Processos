#include <iostream>
#include <unistd.h> 
using namespace std;

int main(){
  int num;
  pid_t j;
  pid_t i;
  
  cout << "Enter the number: ";
  cin >> num;
  j = num;
  
  fork();
  
  for (i=1; j > 1; j = j -1) {       
        i=i*j;
  }
   
  cout << "The factorial of " << num << " is " << i << endl;
  return 0;
  
}
