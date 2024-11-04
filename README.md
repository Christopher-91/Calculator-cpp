//1st Project in cpp
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    double a;
    double b;
    double c;
    double d;
    int num;
    
    cout<<"1.for Addition"<<endl;
    cout<<"2.for subtraction"<<endl;
    cout<<"3.for multiplication"<<endl;
    cout<<"4.for division"<<endl;
    cout<<"5.for square"<<endl;
    cout<<"6.for Square root"<<endl;
    cout<<"7.for Cube"<<endl;
    
    
    cout<<"Enter A: "<<endl;
    cin>>a;
    
    cout<<"Enter B: "<<endl;
    cin>>b;
    
    cout<<"Enter the number for the type of operation to be performed: "<<endl;
    cin>>num;
    
    switch(num){
        case 1:
              c = a+b;
              cout<<"Addition"<<c;
              break;
        case 2:
              c = a-b;
              cout<<"Subtraction"<<c;
              break;
        case 3:
              c = a*b;
              cout<<"Multiplication"<<c;
              break;
        case 4:
              c = a/b;
              cout<<"Division"<<c;
              break;
        case 5:
              c = pow(a,2);
              d = pow(b,2);
              cout<<"Square of A is: "<<c<<'\n';
              cout<<"Square of B is: "<<d;
              break;
        case 6:
              c = sqrt(a);
              d = sqrt(b);
              cout<<"Square root of A: "<<c<<'\n';
              cout<<"Square root of B: "<<d;
              break;
        case 7:
              c = pow(a,3);
              d = pow(b,3);
              cout<<"Cube of A: "<<c<<'\n';
              cout<<"cube of B: "<<d;
              break;
    }
    return 0;
    }
