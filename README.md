# fuzzy-dollop
In the “old days” measurements used to be expresses in yards, feet and inches (12 inches = 1 foot, 3 feet = 1 yard). Show how to convert from inches into yards, feet and inches. Write a program to demonstrate the use of new and delete operators to declare the variable in this statement.  

#include<iostream>
using namespace std;
inline void conversion()
{
/* declaring float variable*/
    float inch, yard, feet ;
    cout<<"enter the value in inches"<<endl;
    cin>>inch;
// Length conversion
    yard= inch/36;
    feet=inch/12;
    cout<<"yards:"<<yard<<endl;
    cout<<"feet:"<<feet<<endl;
}
int main()
{
    conversion();
}
