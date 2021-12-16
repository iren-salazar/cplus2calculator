# cplus2calculator
trying to use %*+- in cal.

#include <iostream>
using namespace std;

int main()
{
    int num1, num2;
    char op;
    
    cout<<"enter first number:";
    cin>>num1;
    cout<<"enter operator:";
    cin>>op;
    cout<<"enter second number:";
    cin>>num2;
    
    int result;
    
    if (op=='+'){
         result=num1+num2;
    }else if(op=='-'){
         result=num1-num2;
    }else if(op=='*'){
         result=num1*num2;
    }else if(op=='/'){
         result=num1/num2;
    }else if(op=='%'){
         result=num1%num2;
    }else{
         cout<<" Invalid Operator ";
    }
    cout<< result;
    
    return 0;
}
output: 
  enter first number:10     /13
  enter operator:+     /%
  enter second number:10    /2
  20     /1
