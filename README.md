/*a largest of three variables calculator 
that also knows if variable 3 is largest
and prints 3 statments 
"the max result +1" 
"if variable wasnt the max"
"if variable 3 was max"*/

#include <stdio.h>
#include <iostream>
using namespace std;

int main()
{
    int tool,rule,Consent;
    
    int max;
   
    cin>>tool;
    cin>>rule;
    cin>>Consent;
    
    max=tool;
    if (rule>max)
    max=rule;
    
    if (Consent>max)
    max=Consent;
    
    

cout << "Hiring chance of " <<++max<<endl;
if (Consent<max)
cout << "we need to work out a better deal";
else
cout<<"Thats a Solid Deal";


    


    return 0;
}
