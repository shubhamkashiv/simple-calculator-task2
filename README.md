 simple-calculator-task2
/*develop a calculator program that performs basic information arithmatic
 operations such as addition ,substraction,multification and division . 
 allow the user to inout two numbers and choose and operation to perform.*/
 #include<iostream>
 using namespace std;
 int main(){
           double num1,num2;
           char op;
           cout<<"enter the operator (+,-,*,/):     "<<endl;
           cin>>op;
           cout<<"enter the two number :      "<<endl; 
           cin>>num1>>num2;
           switch(op)
           {
                    case '+':
                    cout<<num1+num2<<endl;
                    break;

                    case '-':
                    cout<<num1-num2<<endl;
                    break;

                    case '*':
                    cout<<num1*num2<<endl;
                    break;

                    case '/':
                    cout<<num1/num2<<endl;
                    break;

                    default:
                    cout<<"invalid operator"<<endl;
           }
           return 0;
 }
