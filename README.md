# EX-06 - Looping
## AIM:
Write a C program to print even numbers ranging from M to N (including M and N values).

## ALGORITHM:
1.	Declare two integer variables to store the values of M and N.
2.	Use the printf function to prompt the user to enter the values of M and N.
3.	Use the scanf function to read the values of M and N from the user.
4.	Use a loop (for or while) to iterate from M to N.
5.	Inside the loop, check if the current number is even.
6.	If the current number is even, print it.
7.	Continue the loop until you have iterated through all numbers from M to N.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,b;
    scanf("%d %d",&a,&b);
    for(int i=a;i<=b;i++)
    {
        if(i%2==0)
        {
            printf("%d ",i);
        }
    }
 
    return 0;
}
```

## OUTPUT:
<img width="763" height="221" alt="image" src="https://github.com/user-attachments/assets/fc077902-f706-40f4-b8bd-ed8ce72e9407" />











## RESULT:
Thus the program to print even numbers ranging from M to N (including M and N values) has been executed successfully
 
 


# EX-07-Nested-loop

## AIM:

Write a C program to print the given triangular pattern using loop.

## ALGORITHM:

1.	Declare a variable to store the number of rows in the triangle.
2.	Use the printf function to prompt the user to enter the number of rows.
3.	Use a loop (for or while) to iterate through each row.
4.	Inside the loop, use another loop to print the desired number of asterisks for each row.
5.	Continue the loop until you have printed the entire triangular pattern.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    for(int i=a;i>=1;i--)
    {
        for(int j=i;j>=1;j--)
        {
            printf("$");
        }
        printf("\n");
    }
}
```


## OUTPUT:
<img width="609" height="330" alt="image" src="https://github.com/user-attachments/assets/ba4f97bb-38d1-4dd4-ad53-ccf5ac6603a3" />






## RESULT:

Thus the program to print the given triangular pattern using loop has been executed successfully
 
 


# EX-08-Functions

## AIM:

Write a C program to perform addition and subtraction of two numbers using functions (with argument and without return type).

## ALGORITHM:

1.	Declare two functions, one for addition and one for subtraction. Both functions should take two integer arguments.
2.	Inside the addition & subtraction function, add & subtract the two numbers and print the result.
3.	In the main function, declare two integer variables and read their values from the user.
4.	Call the addition and subtraction functions, passing the two numbers as arguments.

## PROGRAM:
```
#include <stdio.h>
void add(int a, int b) {
    int sum = a + b;
    printf("Addition: %d\n", sum);
}


void subtract(int a, int b) {
    int difference = a - b;
    printf("Subtraction: %d\n", difference);
}

int main() {
    int num1, num2;
    scanf("%d %d", &num1, &num2);
    add(num1, num2);
    subtract(num1, num2);

    return 0;
}
```


## OUTPUT:

<img width="811" height="234" alt="image" src="https://github.com/user-attachments/assets/19a7fa89-b475-4dfa-bcae-e0585a23be56" />





## RESULT:

Thus the program to perform addition and subtraction of two numbers using functions has been executed successfully
 
 


# EX-09-Use For Loop

## AIM:

Write a c program to find the sum of odd digits using for loop

## ALGORITHM:

1.	Declare variables to store the input number and the sum of odd digits.
2.	Initialize the sum of odd digits to 0.
3.	Use a for loop to iterate through each digit of the input number.
4.	Inside the loop, extract the rightmost digit of the number (using the modulo operator % and division by 10).
5.	If the digit is odd, add it to the sum of odd digits.
6.	Print the sum of odd digits.

## PROGRAM:#include <stdio.h>
```
int main()
{
   int a;
   scanf("%d",&a);
   int sum=0;
   for(int i=0;i<2*a;i++)
   {
       if(i%2!=0)
       {
           printf("%d ",i);
           sum=sum+i;
       }
   }
   printf("\n");
   printf("%d",sum);
}
   
```



## OUTPUT:
<img width="813" height="278" alt="image" src="https://github.com/user-attachments/assets/7f95b60a-d7b6-4c14-88a8-5788ee52de8d" />





## RESULT:

Thus the program to find the sum of odd digits using for loop has been executed successfully.




# EX – 10 - Factorial of a Number Using a Function
## AIM:
To write a C program that calculates the factorial of a given number using a user-defined function.
## ALGORITHM:
1.	Start
2.	Declare the function fact().
3.	In the main() function, call the fact() function.
4.	In fact() function:
a.	Declare variables i, N, and fact (initialized to 1).
b.	Read an integer N from the user.
c.	Use a for loop from 1 to N:
i.	Multiply fact by i in each iteration.
d.	After the loop, print the factorial value.
5.	End

## PROGRAM:
```
#include<stdio.h>
void fact()
{
    int a;
    scanf("%d",&a);
    long int fact=1;
    for(int i=2;i<=a;i++)
    {
        fact = fact*i;
    }
    printf("Factorial value is: %ld",fact);
}
int main()
{
    fact();
}
```

## OUTPUT:
<img width="810" height="138" alt="image" src="https://github.com/user-attachments/assets/c02e11cb-6240-421e-8dbb-98bccde7d038" />


## RESULT:
The program correctly computes the factorial of a given number using a separate function and displays the result.
The program correctly computes the factorial of a given number using a separate function and displays the result.
 
