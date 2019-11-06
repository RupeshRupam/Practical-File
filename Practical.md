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



