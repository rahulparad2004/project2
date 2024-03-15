# project2
#include<iostream>
using namespace std;
int main(){
    int a,b;
    cout<<"Enter First Value: ";
    cin>>a;
    cout<<"Enter Second Value: ";
    cin>>b; 
    cout<<endl;
    cout<<"1: Addition"<<endl;
    cout<<"2: Substraction"<<endl;
    cout<<"3: Multiplication"<<endl;
    cout<<"4: Divition"<<endl;
    int ch;
    cout<<"Enter your choice: ";
    cin>>ch;
    switch (ch)
    {
    case 1:
        cout<<"Addition of the given numbers: "<<a+b;
        break;
    case 2:
        cout<<"Substraction of the given numbers: "<<a-b;
        break;
    case 3:
        cout<<"Multiplication of the given numbers: "<<a*b;
        break;
    case 4:
        cout<<"Divition of the given numbers: "<<a/b;
        break;
    
    default:
        cout<<"Invalid Choice"<<endl;
        break;
    }
}
