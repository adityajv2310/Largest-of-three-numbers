# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

## Program:
~~~c#
using System;
namespace hello
{
class large
{
    static void Main(string[] args)
    { 
        int num1,num2,num3;
        Console.WriteLine ("Enter Three integers:");
        num1=Convert.ToInt32(Console.ReadLine());
        num2=Convert.ToInt32(Console.ReadLine());
        num3=Convert.ToInt32(Console.ReadLine());
        if(num1>num2)
        {
            if(num1>num3)
            {
                Console.WriteLine(Num 1 + " is Greater");
            }
            else
            {
               Console.WriteLine(Num 3 + " is Greater");  
            }
        }
        else
        { 
            if(num2>num3)
            {
                Console.WriteLine(Num 2 + " is Greater");
            }
            else
            {
                Console.WriteLine(Num 3 + " is Greater");
            }
        }

    }
}
}
~~~

## Output:
![Exp1](https://user-images.githubusercontent.com/75235386/163832721-44574f95-1a0f-4a39-b2a7-5f8cfdc62eb0.png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully
