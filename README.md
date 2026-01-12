#include<iostream>
using namespace std:
int main()

{

int a,b,c,choice;
cout<<"Enter the value of a: "<<endl;
cin>>a;
cout<<"Emter the value of b: "<<endl;
cin>>b;
cout<<"enter your choice: "<<endl;

switch(choice)
{
case 1:
c=a+b;
cout<<"Sum of a and b = " <<c<<endl;
break;

case 2:
c=a-b;
cout<<" Difference of a and b = "<<c<<endl;
break;

case 3:
c=a*b;
cout<<"Product of a and b = "<<c<<endl;
break;

case 4:
c=a/b;
cout<<"Quotient of a and b = "<<c<<endl;
break;

case 5:
c=a%b;
cout<<"Remainder of a and b = "<<c<<endl;
break;

default
cout<<"Wrong Choice!"<<endl;

}
}