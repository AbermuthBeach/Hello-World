#include <stdio.h>
#include <iostream>
using namespace std;

int main()//does it need to be called main?
{
    int Var1,Var2,Var3;// these variables are all integers
    
    int max;
   
    cin>>Var1; //cin is to make the computer ask for a user input
    cin>>Var2; 
    cin>>Var3;
    
    max=Var1;// firt assumes the first input is the largest
    
    if (Var2>max)
    max=Var2;
                    // checking to see what variable is the largest
    if (Var3>max)
    max=Var3;
    
    
cout << "WoW""\n";// testing the \n manipulator
if (Var3<max)// this for if and else learning 
cout << "You got"  <<--max<<endl;// learning about -- and ++
cout << "Nope";
else
cout<<"Now we are getting it";


    


    return 0;
}
