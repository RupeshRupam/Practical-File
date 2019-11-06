# **PRACTICAL REPORT**

### ![LOGO](https://raw.githubusercontent.com/RupeshRupam/Practical-File/master/13012761_10154107361704814_2752296351724321795_n.jpg)


## SUBMITTED BY

### NAME-RUPESH KUMAR
### ROLL NO-1914093
### BRANCH-CE
### SECTION-B2

# 1. Program to print Hello World   

#include<stdio.h>

voide main()

{ 
   puts("\nHello World\n");
}
## Output of the program 

Hello World


## 2. Program to find Sum

#include<stdio.h>
int main()
{

  float x,y,z;

  printf("\nEnter The First Number:");
  scanf("%f", &x);
  
  printf("\nEnter The Second Number:");
  scanf("%f", &y);
  
  z=x+y;
  
  printf("\nAnswer is: = %.3f",z);
  return 0;
}

## 
 Output of the program

Enter The First Numder: 45.26

Enter The Second Numder: 78.2648

Answer is: = 123.525

# 3.. Program to print a Table

#include<stdio.h>
int main()
{

   float x;
   int n;

   printf("\nEnter The Table: ");
   scanf("%f",&x);

    printf("\nEnter No. Times: ");
    scanf("%d",&n);
   
    for(int y=1; y<=n; y++)
  {
    printf("\n%.2f x %d = %.3f",x,y,x*y);
   }
    return 0;
}

## Output of the program

25.00 x 1 = 25.000

25.00 x 2 = 50.000

25.00 x 3 = 75.000

25.00 x 4 = 100.000

25.00 x 5 = 125.000

25.00 x 6 = 150.000

25.00 x 7 = 175.000


# 4. Program to find Area, Perieter, Volume of a Circle


#include<stdio.h>

int main()

{

  float r,P,A,V;

  float pi = 22/7.0;

  printf("\nEnter The Radius of Circle: ");
  
  scanf("%f",&r);

  P = 2*pi*r;

  A = pi*r*r;

  V = 4*pi*r*r*r/3.0;


  printf("\nPerimeter of Circle is: = %.2f",P);

  printf("\nArea of Circle is: = %.2f",A);

printf("\nVolume of Circle is: = %.2f",V);


return 0;

}
## Output of the program

Enter The Radius of Circle: 4.5
Perimeter of Circle is: = 28.29
Area of Circle is: = 63.64
Volume of Circle is: = 381.86


# 5. Program to find Area, Perimeter of a Rectangle

#include<stdio.h>

int main()

{

float h,b,A,P;

printf("\nEnter Height: ");

scanf("%f",&h);

printf("\nEnter Bredth: ");

scanf("%f",&b);

A = h*b;

P = 2*(h+b);

printf("\nArea of Sqare (or) Rectangle: = %.3f",A);

printf("\nPerimeter of Sqare (or) Rectangle: = %.3f",P);

return 0;

}

## Output of the program#

Enter Height: 24

Enter Bredth: 60

Area of Sqare (or) Rectangle: = 1440.000

Perimeter of Sqare (or) Rectangle: = 168.000

# 6. Program to find Interest

#include<stdio.h>

int main()

{

float P,R,T,Interest;

printf("\nEnter The Principal Amount: ");

scanf("%f", &P);

printf("\nEnter The Interest Rate: ");

scanf("%f", &R);

printf("\nEnter The Time (in months): ");


scanf("%f", &T);

Interest = P*T*R/100;

printf("\nSimple Intesest is: = %.2f", Interest);

return Interest;

}

## Output of the program

Enter The Principal Amount: 4000

Enter The Interest Rate: 4

Enter The Time (in months): 3

Simple Intesest is: = 480.00

# 7. Program to find Maximum

#include<stdio.h>

int max(float x,float y);

int main()

{

float x,y,z;

printf("\nEnter The First Va
lue: ");

scanf("%f",&x);

printf("\nEnter The Second Value: ");

scanf("%f",&y);

z = max(x,y);

printf("\nMaximum value is: %.2f\n", z);

return 0;

}

int max(float x,float y)

{

float result;

if(x<y)

result = y;

else

result = x;

return result;

}
## Output of the program

Enter The First Value: 10
Enter The Second Value: 6
Maximum value is: 10
