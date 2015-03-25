# q2.cpp
#include <iostream>
using namespace std;

int triangles(int size){
  for(int i=1;i<=size;++i){
    for(int start=1 ;start<=i;++start){
        cout<<"T";
      }
      cout<<endl;
    }
  for(int i=(size-1);i>=1;--i){
    for(int start=1;start<=i;++start){
      cout<<"T";
    }
    cout<<endl;
  }
}

int main(){
  cout<<"Please introduce the size of the triangle: ";
  unsigned int size;
  cin>>size;
  cout<<endl;
  triangles(size);
  return 0;
}
