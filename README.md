# Quiz-10
#include <iostream>
using namespace std;

int findThrees(int num1) {
  int array[num1], division, acum1=0;

  for(int i=0; i<=(num1-1); i++){
    cout<<"Give me the number in the position  " <<i<< " ";
    cout<<endl;
    cin>>array[i];

    division=array[i]%3;
    if(division==0){
      acum1=acum1+array[i];
    }
  }
return acum1;
}


int main () {

  int num1;
  cout<<"Tell me how many numbers you want to enter "; cin >>num1;

  cout<<findThrees(num1);

  return 0;
}
