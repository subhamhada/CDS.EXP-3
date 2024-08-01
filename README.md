# Experiment 3
## Aim -
To study and implement operators in c++

## Theory - 
Operators are special symbols used to perform operations on variables and values. 
Understanding how to use different operators is fundamental to performing calculations, assigning values, decision making, performing logical computations and making comparisons in programming.

### Arithmetic Operators:

These include +(addition), -(subtraction), *(multiplication), /(division), and % (modulus). 

They are used to perform basic mathematical operations in C++.

### Assignment Operators:

 The basic assignment operator = assigns a value to a variable, while operators like +=, -=, *=, and /= combine the particular arithmetic operation with assignment.
 
 These operators are used to assign values to variables.

### Logical operators:

These includes AND(&& or AND), OR(|| or OR), NOT(! or NOT), XOR(exclusive OR).

These operators are used fot decision making and performing logical computations. 

### Comparison Operators:

These include ==(equal to), !=(not equal to), >(greater than), <(less than), >=(greater than or equal to), and <=(less than or equal to). 

They are used to compare values and give the result as a boolean value either true or false.

## Code -
### 1.
```
//subham
//23070123132
//entc b2
//experiment 3
#include<iostream>
using namespace std;
int main()
{
    //arithmetic operators
    int a,b;
    int sum,subtraction,multiplication,division;
    cout<<"enter the number-";
    cin>>a>>b;
    sum=a+b;
    subtraction=a-b;
    multiplication=a*b;
    division=a/b;
    cout<<"sum="<<sum<< endl;
    cout<<"subtraction="<<subtraction<< endl;
    cout<<"multiplication="<<multiplication<< endl;
    cout<<"division="<<division<< endl;
    return 0;
}
```

### 2.
```
//subham
//23070123132
//entc b2
//experiment 3
#include<iostream>
using namespace std;
int main()
{
    //assignment operators
    int a,b,c,d;
    cout<<"enter the value of a,b,c,d";
    cin>>a>>b>>c>>d;
    a-=3;
    b*=3;
    c/=3;
    d&=3;
    cout<<"a="<<a<<endl;
    cout<<"b="<<b<<endl;
    cout<<"c=<<"<<c<<endl;
    cout<<"d="<<d<<endl;
    return 0;
}
```

### 3.
```

//subham
//23070123132
//entc b2
//experiment 3
#include<iostream>
using namespace std;
int main()
{
    //logical operators
     int a,b,c,d,e;
    cout<<"\nenter the first number:";
    cin>>a;
    cout<<"\nenter the second number:";
    cin>>b;
    cout<<"\n" << (a > 1 && b < 10)<<endl;
    cout<<"\n" << (a > 1 || b < 10)<<endl;
    cout <<"\n"<<(!(a >1 && b <10))<<endl;
    return 0;
}
```

### 4.
```
//subham
//23070123132
//entc b2
//experiment 3
#include<iostream>
using namespace std;
int main()
{
    //comparison operators
    int a,b;
    cout<<"enter the values of a,b";
    cin>>a>>b;
    if(a==b)
    {
        cout<<"a==b"<<endl;
    }
   else if(a!=b)
    {
        cout<<"a!=b"<<endl;
    }
    if(a>b)
    {
        cout<<"a>b"<<endl;
    }
   else if(a<b)
    {
        cout<<"a<b"<<endl;
    }
    return 0;
}
```

## Explanation -
Arithmetic Operators: Demonstrate basic mathematical operations such as addition, subtraction, multiplication, division, and modulus.

Assignment Operators: Show how to assign values to variables using =, +=, -=, *=, /=, and %=.

logical operators: show how to perform logical computations && AND, || OR, ! NOT, exclusive OR.

Comparison Operators: Illustrate how to compare values using ==, !=, <, >, <=, and >=.

## Output -
### 1. arithmetic operators
![Screenshot 2024-07-30 234524](https://github.com/user-attachments/assets/ce64d805-3f2c-4ace-a678-3934daaff9cf)
### 2. assignment operators
![Screenshot 2024-07-30 234312](https://github.com/user-attachments/assets/ae4b1137-cd20-4b86-91ad-c878c1bdd6cf)
### 3. logical operators
![Screenshot 2024-07-30 234449](https://github.com/user-attachments/assets/ac56fd4c-d21f-4cc1-8984-0b54c2108fff)
### 4. comparison operators
![Screenshot 2024-07-30 234356](https://github.com/user-attachments/assets/8035b75b-0768-4b92-a9c1-7af9d4509b3a)

## Conclusion -
These programs provide a clear understanding of how to use various operators in C++.
Mastery of operators is essential for performing mathematical calculations, making decisions, assigning values,comparing values and controlling the flow of a program.
