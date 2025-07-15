# Experiment-3
Aim:To study and implement Operators in C++

Theory:Operators are symbols used to perform operations on data.
C++ supports the following types:

Arithmetic Operators – +, -, *, /, %
➤ Used for mathematical calculations.

Relational Operators – ==, !=, <, >, <=, >=
➤ Used for comparing two values.

Logical Operators – &&, ||, !
➤ Used in conditional expressions.

Assignment Operators – =, +=, -=, *=, /=
➤ Used to assign or update values.

Increment/Decrement – ++, --
➤ Used to increase or decrease value by 1.

Bitwise Operators – &, |, ^, ~, <<, >>
➤ Used for bit-level operations.


Code: 1.#include<iostream>
using namespace std;
int main()
{
    int a;
    cout<<"Enter a number"<<endl;
    cin>>a;
    if (a==0)
    {
    cout<<"The number is zero"<<endl;
    }
    else if (a>0)
    {
    cout<<"positive"<<endl;
    }
    else
    {
        cout<<"negative"<<endl;
    }
}
Output: PS C:\Users\Rishu Raj\New folder\c programme> cd "c:\Users\Rishu Raj\New folder\c programme\" ; if ($?) { g++ a.cpp -o a } ; if ($?) { .\a }
Enter a number
12
positive

2. #include<iostream>
using namespace std;
int main()
{
    int m1,m2,m3,m4,m5;
    cout<<"Enter a marks of subject 1"<<endl;
    cin>>m1;
    cout<<"Enter a marks of subject 2"<<endl;
    cin>>m2;
    cout<<"Enter a marks of subject 3"<<endl;
    cin>>m3;
    cout<<"Enter a marks of subject 4"<<endl;
    cin>>m4;
    cout<<"Enter a marks of subject 5"<<endl;
    cin>>m5;
    double avg;
    avg=(m1+m2+m3+m4+m5)/5;
    cout<<"Pecentage: "<<avg<<"%"<<endl;
    if (avg>90)
    {
        cout<<"O"<<endl;
    }
     else if (avg>85)
    {
        cout<<"A"<<endl;
    }
    else if (avg>75)
    {
        cout<<"B"<<endl;
    }
     else if (avg>65)
    {
        cout<<"C"<<endl;
    }
    else
    {
        cout<<"Fail"<<endl;
    }
}
Output: PS C:\Users\Rishu Raj\New folder\c programme> cd "c:\Users\Rishu Raj\New folder\c programme\" ; if ($?) { g++ a.cpp -o a } ; if ($?) { .\a }
Enter a marks of subject 1
24
Enter a marks of subject 2
12
Enter a marks of subject 3
45
Enter a marks of subject 4
15
Enter a marks of subject 5
23
Pecentage: 23%
Fail
