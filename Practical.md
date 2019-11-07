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

Enter The First Value: 15

Enter The Second Value: 8

Maximum value is: 15


# 8. Program of Sum of two Constants

#include<stdio.h>

int main()

{

int a=100,b=120,c;

c = a+b;

printf("\na=100\nb=120\nSum of a and b is :%d",c);

return 0;

}

## Output of the program

a=100

b=120

Sum of a and b is :220

# 9. Program To find Minimum

#include<stdio.h>

int min(float x,float y);

int main()

{

float x,y,z;

printf("\nEnter The First Value: ");

scanf("%f",&x);

printf("\nEnter The SecondValue: ");

scanf("%f",&y);

z = min(x,y);

printf("\nMinimum value is: %.2f\n", z);

return 0;

}

int min(float x,float y)

{

float result;

if(x<y)

result = x;

else

result = y;

return result;

}

## Output of the program

Enter The First Value: 5

Enter The SecondValue: 3

Minimum value is: 3.00

# 10. Program to print Bio Data of Students

#include<stdio.h>

int main()

{

int n,R;

char name[25];

printf("\nEnter The Number of Students: ");

scanf("%d",&n);

for(int i=1; i<=n;i++)

{

printf("\nEnter The Name of The Student : ");

scanf("%s", name);

printf("Enter The Roll No. of Students: ");

scanf("%d",&R);

printf("\nName = %s\nRoll No. = %d\n", name,R);

}

return 0;

}

## Output of the program

Enter The Number of Students: 3

Enter The Name of The Student : Rupesh

Enter The Roll No. of Students: 1914093

Name = Rupesh

Roll No. = 1914093

Enter The Name of The Student : Sharan

Enter The Roll No. of Students: 1914103

Name = Sharan

Roll No. = 1914103

Enter The Name of The Student : Ritik

Enter The Roll No. of Students: 1914087

Name = Ritik

Roll No. = 1914087

# 11. Program to use Arithmetic Operators

#include<stdio.h>

int main()

{

float x,y,a;

printf("\nEnter The Value of x: ");

scanf("%f",&x);

printf("\nEnter The Value of y: ");

scanf("%f",&y);

a = x+y;

printf("x + y = %.3f\n",a);

a = x-y;

printf("x - y = %.3f\n",a);

a = y-x;

printf("y - x = %.3f\n",a);

a = x*y;

printf("x * y = %.3f\n",a);

a = x/y;

printf("x/y = %.3f\n",a);

a = y/x;

printf("y/x = %.3f\n",a);

return 0;

}

## Output of the program

Enter The Value of x: 45

Enter The Value of y: 31

x + y = 76.000

x - y = 14.000

y - x = -14.000

x * y = 1395.000

x/y = 1.452

y/x = 0.689

# 12. Program to use Assignment Operators

#include<stdio.h>

int main()

{

float x,a;

printf("\nEnter The Value of x: ");

scanf("%f",&x);

a = x;

printf("Answer is a = x %.3f\n",a);

a +=x; //answer is a+x

printf("Answer is a+x = %.3f\n",a);

a -=x; //answer is a-x

printf("Answer is a-x = %.3f\n",a);

a *=x; //answer is a*x

printf("Answer is a*x = %.3f\n",a);

a /=x; //answer is a/x

printf("Answer is a/x= %.3f\n",a);

return 0;

}

## Output of the program

Enter The Value of x: 45

Answer is a = x 45.000

Answer is a+x = 90.000

Answer is a-x = 45.000

Answer is a*x = 2025.000

Answer is a/x= 45.000

# 13. Program to use Operator Precedence




