# CDS-experiment-4

AIM :- to study and implement cpp bitwise operator <br>

Theory:- <br>
In C++, bitwise operators work with discrete bits of integral types. {&} (AND), {|} (OR), {^{ (XOR), {~} (NOT), {<<} (left shift), and {>>} (right shift) are examples of common operators. They carry out bit-level operations, making low-level programming and data manipulation effective.  <br>

Code:-
// Vandan Gupte 23070123147 ENTC B3 
#include<iostream>
using namespace std;
int main(){
    int a,b,a1,a2,a3,a4,a5,a6;

    cout<<"Enter the value for A"<<endl;
    cin>>a;
    cout<<"Enter the value for B"<<endl;
    cin>>b;
    a1=a&b;    //------BITWISE OPERATOR
    a2=a|b;    //------BITWISE OPERATOR
    a3=a^b;    //------BITWISE OPERATOR
    a4=~b;     //------BITWISE OPERATOR
    a5=a<<2;   //------BITWISE OPERATOR
    a6=a>>2;   //------BITWISE OPERATOR

    cout<<"AND of the entered value is "<<a1<<endl<<endl;
    cout<<"OR of the entered value is "<<a2<<endl<<endl;
    cout<<"XOR of the entered value is "<<a3<<endl<<endl;
    cout<<"NOT of B is "<<a4<<endl<<endl;
    cout<<"LEFT SHIFT of A by 2 is "<<a5<<endl<<endl;
    cout<<"RIGHT SHIFT of A by 2 is "<<a6<<endl<<endl;

    return 0;
}

Conclusion:- in this experiment we learnt to use the bitwise operator in cpp <br>
