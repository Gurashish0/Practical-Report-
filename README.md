# PROGRAMMING FOR PROBLEM SOLVING 

### NAME - GURASHISH SINGH 

### ROLL NO - 1915022

### BRANCH - COMPUTER SCIENCE 

### SECTION - CSE (A1)



# PROGRAM NO 1 : PROGRAM TO PRINT WELCOME MESSAGE 
```C
  #include <stdio.h>  
   void main ()  
   {  
     puts ("Welcome Budding Engineers");  
   }  
   ```
   ## OUTPUT
   
   `Welcome Budding Engineers `
   
   
   
   # PROGRAM NO : 2 PROGRAM TO PRINT THE ADDRESS
 ```C  
   
   include <stdio.h>  
void main ()  
{  
puts ("House Number : 111");  
puts ("Street Number : 2");    
puts ("XYZ Nagar ");  
puts ("Patiala");  
}  
```
## OUTPUT

`House Number : 111`  
`Street Number : 2`  
`XYZ Nagar`   
`Patiala`  

# PROGRAM NO 3 : PROGRAM TO FIND THE SUM OF TWO NUMBERS 
```C
#include <stdio.h>  
int main ()  
{  
int a,b,c;  
printf ("Enter first variable : ");  
scanf ("%d",&a);  
printf("Enter second variable : ");  
scanf ("%d",&b);  
c = a+b;                                                 
printf("Sum of two variables is : %d\n",c);  
return 0;                                                      
}  
```
## OUTPUT 

`Enter first variable : 10`  
`Enter second variable : 20`  
`Sum of two variables is : 30`  

# PROGRAM NO 4 : PROGRAM TO CONVERT TEMPERATURE FROM CELCIUS TO FAHRENHEIT
```C
#include <stdio.h>  
void main ()                                                   
{  
float num1,num2;  
printf ("\nEnter value in centigrade:\n");  
scanf ("%f",&num1);  
num2 = (num1*9/5)+32;  
printf ("\nValue in farenheit is :%.2f\n",num2 );  
}  
```
## OUTPUT

`Enter value in centigrade:`  
`100`  

`Value in farenheit is :212.00`  

# PROGRAM NO 5 : PROGRAM TO FIND AREA AND PERIMETER OF A CIRCLE

```C
#include <stdio.h>  
int main ()  
{  
float radius,area, peri,pi=3.14 ;  
printf("Enter radius of circle :");  
scanf ("%f",&radius);  
area=pi*radius*radius;  
peri=2*pi*radius;  
printf("Area of circle : %f,",area);  
printf("Perimeter of circle : %f",peri);  
return 0;  
}  
```
## OUTPUT 

`Enter radius of circle :5`  
`Area of circle : 78.500000,Perimeter of circle : 31.400002`  

# PROGRAM NO 6 : PROGRAM TO SWAP TWO NUMBERS WITHOUT USING THIRD VARIABLE 

```C
#include <stdio.h>  
int main ()  
{                                                                   
int a,b;  
printf ("\nEnter the  value of a :");  
scanf ("%d",&a);  
printf ("\nEnter the value of b :");  
scanf ("%d",&b);  
a=a+b;   
b=a-b;  
a=a-b;  
printf ("\nThe swaped values of a : %d\n",a);  
printf ("\nThe swaped value of b : %d \n",b);  
return 0;  
}  
```
## OUTPUT 
`Enter the  value of a :10`  

`Enter the value of b :20`  

`The swaped values of a : 20`  

`The swaped value of b : 10 `    

# PROGRAM NO 7 : PROGRAM TO CHECK WHETHER THE NUMBER IS EVEN OR ODD
```C
#include <stdio.h>  
int oddeven(int num1);  
int main ()  
{  
int s ;  
printf ("Enter the integer:");  
scanf ("%d",&s);  
oddeven (s);  
return 0;  
}  
int oddeven(int num1)  
{  
if (num1%2==0)  
printf ("The number is even")  
else  
printf ("The number is odd:");  
return 0;  
}  
```
## OUTPUT 

`Enter the integer:177`  
`The number is odd`  

# PROGRAM NO 8 : PROGRAM TO FIND FACTORIAL OF A NUMBER 
```C
#include <stdio.h>  
void main()  
{  
int a,n=1,i;  
printf("enter i : ");  
scanf("%d",&i);  
for(a=1;a<=i;a++)  
n=n*a;  
printf("factorial of i is %d \n",n);  
}  
```
## OUTPUT 

`enter i : 5`  
`factorial of i is 120`  

# PROGRAM NO 9 : PROGRAM TO REVERSE A NUMBER 
```C
#include <stdio.h>  
int main ()  
{  
int n , reverse =0;  
printf ("Enter the number to be reversed:\n");  
scanf ("%d",&n);  

while(n!=0)  
{  
reverse = reverse*10;  
reverse = reverse + n%10;  
n=n/10;  
}  
printf ("Reverse number is:%d\n",reverse);  
return 0;  
}  
```

## OUTPUT 

`Enter the number to be reversed:`  
`1598`  
`Reverse number is:8951`   

# PROGRAM NO 10 : PROGRAM TO PRINT FIZZBUZZ
```C
#include <stdio.h>  
void main()  
{  
int a,i;  
printf("enter the number ");  
scanf("%d",&a);  
for(i=1;i<=a;i++)  
{ if (i%15==0)  
printf("fizzbuzz\n");  
else if(i%5==0)  
printf("buzz\n");  
else if(i%3==0)  
printf("fizz\n");  
else  
printf("%d\n",i);  
}  
return 0;  
}  
```
## OUTPUT 

`enter number 30`  
`1`  
`2`  
`fizz`  
`4`  
`buzz`  
`fizz`  
`7`  
`8`  
`fizz`  
`buzz`  
`11`  
`fizz`  
`13`   
`14`  
`fizzbuzz`  
`16`  
`17`  
`fizz`  
`19`  
`buzz`  
`fizz`  
`22`  
`23`  
`fizz`  
`buzz`  
`26`  
`fizz`  
`28`  
`29`  
`fizzbuzz`  

# PROGRAM NO 11 : PROGRAM TO PRINT DAYS OF A WEEK 
```C
#include <stdio.h>  
int main ()  
{  
int day;  
printf ("Enter the number of day (Consider Monday = 1 and Sunday = 7) : ");  
scanf ("%d",&day);  
switch (day)  
{  
case 1:  
printf ("\nToday is Monday\n ");  
break;  
case 2:  
printf  ("\nToday is Tuesday\n");  
break;  
case 3:  
printf ("\nToday is Wednesday\n");  
break;              
case 4:  
printf("\nToday is Thursday\n");   
break;  
case 5:  
printf ("\nToday is Friday\n");  
break ;  
case 6:  
printf ("\nToday is Saturday\n");  
break;  
case 7:  
printf("\nToday is Sunday\n");  
break;  
default :  
printf ("Please Enter a valid number ");  
}  
return 0;  
}  
```
## OUTPUT 

`Enter the number of day (Consider Monday = 1 and Sunday = 7) : 3`  

`Today is Wednesday`  

# PROGRAM NO 12 : PROGRAM TO MAKE A CALCULATOR 
```C
#include <stdio.h>  
int main ()  
{  
int num1,num2;  
char ch;  
float result;  
printf ("Enter the first number:");  
scanf ("%d",&num1);  
printf ("Enter the second number:");  
scanf ("%d",&num2);  
printf ("Choose the operation to perform(+,-,*,/):");  
scanf ("%c",&ch);  
result=0;  
switch(ch)  
{  
case '+':  
result = num1+num2;   
break; 
case '-':  
result = num1-num2;  
break;  
case'*':  
result = num1*num2;  
break;  
case '/':  
result = num1/num2;  
break;  
default:  
printf ("Invalid operation.\n");  
}  
printf ("Result: %d %c %d = %f\n",num1,ch,num2,result);  
return 0;  
}  
```
## OUTPUT 

`Enter the first number:106`  
`Enter the second number:67-`  
`Choose the operation to perform(+,-,*,/):Result: 106 - 67 = 39.000000`  

# PROGRAM NO 13 : PROGRAM TO CHECK WHETHER A YEAR IS LEAP YEAR OR NOT 
```C
#include <stdio.h>  
 int main ()  
{  
int year;  
printf("Enter the year : ");  
scanf ("%d",&year);  

if (year%4==0)  
  {  
     if (year%100==0)  
        
        {    
           if (year%400==0)  
             printf ("%d is a leap year");   
           else   
             printf ("%d is not a leap year");  
             }  
            
             else   
                printf ("%d is not a leap year");  
              }  
             else   
                printf ("%d is a leap year");   
       return 0;  
}  
```
## OUTPUT 

`Enter the year : 2019`  
`2019 is not a leap year`  

# PROGRAM NO 14 : PROGRAM TO CHECK WHETHER A NUMBER IS PRIME OR NOT 
```C
#include <stdio.h>  
int main () 
{  
int n,i,flag=0;  
printf ("Enter the number : ");  
scanf ("%d",&n);  
for (i=2 ; i<=n/2 ; i++)   
{              
if (n%i == 0)  
  {  
    flag = 1;  
        break;    
    }           
}              
if (n==1)         
{  
  printf ("1 is neither a prime nor a composite number ");  
}  
else   
{  
  if (flag ==0) 
printf ("%d is a prime number.",n);  
  else   
 printf ("%d is not a prime number.",n);  
}  
return 0;  
}  
```
## OUTPUT 

`Enter the number : 235`  
`235 is not a prime number`  

# PROGRAM NO 15 : PROGRAM TO CHECK WHETHER A NUMBER IS PALLINDROME OR NOT 
```C
#include <stdio.h>  
int main ()  
{  
    int n, reverse=0,t;  
    printf("Enter a number to check if it is a palindrome or not\n");  
    scanf("%d",&n);  
    t=n;  
    while (t!=0)  
    {  
     reverse = reverse*10;  
     reverse = reverse + t % 10;  
     t = t/10;  
     }  
if (n==reverse)  
printf ("%d is a palindrome number.\n",n);  
else   
printf ("%d is not a palindrome number.\n",n);  
return 0;  
}  
```
## OUTPUT 

`Enter a number to check if it is a palindrome or not`  
`1221`  
`1221 is a palindrome number.`

# PROGRAM NO 16 : PROGRAM TO PRINT FIBONACCI SERIES 
```C
#include <stdio.h>  
int main ()  

{  
int i,n,t1=0,t2=1,next;  
printf("Enter the number of terms :");  
scanf ("%d",&n);  
printf ("Fibonacci Series ");  
for (i=1;i<=n;i++)  
{  
printf ("\t%d\t",t1);  
next = t1+t2;  
t1=t2;  
t2=next;  
}  
return 0;  
}   
```
## OUTPUT 

`Enter the number of terms :9`  
`Fibonacci Series        0  1  1  2  3  5  8  13  21`   

# PROGRAM NO 17 : PROGRAM TO ENTER AND PRINT ELEMENTS USING 1-D ARRAY 
```C
#include <stdio.h>  
int main ()  
{  
int values [10],i;  
for (i=0;i<10;i++)  
{  
printf ("Enter [%d] :",i);  
scanf ("%d",&values[i]);  
}  
printf ("\n Printing elements of the array : \n");  
for (i=0;i<10;i++)  
{  
printf ("%d\n",values[i]);  
}  
return 0;  
}  
```         
## OUTPUT

`Enter [0] :12`  
`Enter [1] :33`  
`Enter [2] :54`  
`Enter [3] :76`  
`Enter [4] :123`  
`Enter [5] :33`  
`Enter [6] :98`  
`Enter [7] :45`  
`Enter [8] :66`  
`Enter [9] :75`  
  
` Printing elements of the array :` 
`12`
`33`
`54`
`76`
`123`
`33`
`98`
`45`
`66`
`75`


# PROGRAM NO 18:-PROGRAM TO PRINT A MATRIX
```C
#include <stdio.h>  
int main ()  
{  
int i,j,m,n;  
int matrix[10][20];  
printf ("Enter the number of rows:");  
scanf ("%d",&m);  
printf ("Enter the number of columns:");  
scanf ("%d",&n);  
 
for (i=0;i<m;i++)  
{   
for (j=0;j<n;j++)  
 {  
printf ("Enter data in [%d][%d]:",i,j);  
scanf ("%d",&matrix [i][j]);  
     }  
}  

for (i=0;i<m;i++)  
 {  
  for (j=0;j<n;j++)  
    { printf ("%d\t",matrix[i][j]);  
     
    }  
printf  ("\n");  
}  
return 0;  
}  
```
## OUTPUT

`Enter the number of rows:2`  
`Enter the number of columns:2`  
`Enter data in [0][0]:12`  
`Enter data in [0][1]:34`  
`Enter data in [1][0]:65`  
`Enter data in [1][1]:77`  
`12      34`  
`65      77`  

# PROGRAM NO 19:-PROGRAM TO ADD TWO MATRIX
```C
#include <stdio.h>  
int main ()  
{  
int i,j,a[10][10],b[10][10],sum[10][10],m,n;  
printf ("Enter the number of Rows\n Enter the number of Columns:");  
scanf ("%d %d",&m,&n);  
for (i=0;i<m;i++)  
{  
for (j=0;j<n;j++)  
{  
printf ("Enter value of first matrix (%d %d) : ",i,j);  
scanf ("%d",&a[i][j]);  
}  
  }  
for (i=0;i<m;i++)  
{  
for (j=0;j<n;j++)       
{  
printf ("Enter value of second matrix (%d %d) : ",i,j);  
scanf ("%d",&b[i][j]);  
}  
 }  
printf ("Sum of entered matrices :\n");  
for (i=0;i<m;i++)  
{  
for(j=0;j<n;j++)  
{  
sum [i][j]=a[i][j] + b[i][j];  
printf ("%d\t",sum [i][j]);  
}  
printf ("\n");  
}  
return 0;  
}   
```
## OUTPUT 

`Enter the number of Rows`  
` Enter the number of Columns:2 2 `  
`Enter value of first matrix (0 0) : 12`  
`Enter value of first matrix (0 1) : 66`  
`Enter value of first matrix (1 0) : 34`  
`Enter value of first matrix (1 1) : 25`  
`Enter value of second matrix (0 0) : 22`  
`Enter value of second matrix (0 1) : 34`  
`Enter value of second matrix (1 0) : 97`  
`Enter value of second matrix (1 1) : 4`  
`Sum of entered matrices :`  
`34      100`  
`131     29`  

# PROGRAM NO 20:-PROGRAM TO TRANSPOSE A MATRIX
```C
#include <stdio.h>  
 
void main()  
{  
    static int array[10][10];  
    int i, j, m, n;  
 
    printf("Enter the order of the matrix \n");  
    scanf("%d %d", &m, &n);  
    printf("Enter the coefiicients of the matrix\n");  
    for (i = 0; i < m; ++i)  
    {  
        for (j = 0; j < n; ++j)  
        {  
            scanf("%d", &array[i][j]);  
       }  
    }  
    printf("The given matrix is \n");  
    for (i = 0; i < m; ++i)  
    {  
        for (j = 0; j < n; ++j)  
        {  
            printf(" %d", array[i][j]);  
        }  
        printf("\n");  
    }  
    printf("Transpose of matrix is \n");  
    for (j = 0; j < n; ++j)  
    {  
       for (i = 0; i < m; ++i)  
        {    
           printf(" %d", array[i][j]);    
        }    
        printf("\n");    
    }   
  }    
```
## OUTPUT

`Enter the order of the matrix`  
`3 3`  
`Enter the coefiicients of the matrix`  
`3 7 9`  
`2 7 5`  
`6 3 4`  
`The given matrix is`  
` 3 7 9`  
` 2 7 5`  
` 6 3 4`  
`Transpose of matrix is`  
 `3 2 6`  
 `7 7 3`  
` 9 5 4`  

# PROGRAM NO 21:-PROGRAM TO SUBTRACT TWO MATRIX
```C
#include <stdio.h>  
int main ()  
{  
int i,j,a[10][10],b[10][10],minus[10][10],m,n;  
printf("Enter the number of Rows :");  
scanf ("%d",&m);  
printf ("Enter the number of columns :");  
scanf ("%d",&n);  
for (i=0 ; i<m ; i++)  
{  
for (j=0 ; j<n ;j++)  
{  
printf("Enter value of first matrix(%d %d) : ",i,j);  
scanf ("%d",&a[i][j]);  
}  
 }  
for(i=0;i<m;i++)        
{  
for (j=0;j<n;j++)  
{  
printf ("Enter value of second matrix (%d %d) : ",i,j);  
scanf ("%d",&b[i][j]);  
}  
 }  
for (i=0;i<m;i++)  
{  
for (j=0;j<n;j++)  
{  
minus [i][j] = a[i][j] - b[i][j] ;  
printf ("%d\t",minus[i][j] );  
}  
printf ("\n");  
}  
return 0;  
```
## OUTPUT

`Enter the number of Rows :2`  
`Enter the number of columns :2`  
`Enter value of first matrix(0 0) : 143`  
`Enter value of first matrix(0 1) : 32`  
`Enter value of first matrix(1 0) : 56`  
`Enter value of first matrix(1 1) : 78`  
`Enter value of second matrix (0 0) : 22`  
`Enter value of second matrix (0 1) : 9 `  
`Enter value of second matrix (1 0) : 19`  
`Enter value of second matrix (1 1) : 56`  
`121     23`  
`37      22`  

# PROGRAM NO 22:- PROGRAM TO MULTIPLY TWO MATRIX  
```C
#include<stdio.h>  
void main()  
{  
    int a[10][10],b[10][10],c[10][10],i,j,k,r1,c1,r2,c2;  
    int sum=0;  
    printf("Enter number of rows and columns of first matrix (MAX 10)\n");  
    scanf("%d%d",&r1,&c1);  
    printf("Enter number of rows and columns of second matrix MAX 10)\n");  
    scanf("%d%d",&r2,&c2);  
    if(r2==c1)  
    {  
 
        printf("\n Enter First Matrix:");  
        for(i=0; i<r1; i++)  
        {  
            for(j=0; j<c1; j++)  
                scanf("%d",&a[i][j]);  
        }  
        printf("\n Enter Second Matrix: ");  
        for(i=0; i<r2; i++)  
        {  
            for(j=0; j<c2; j++)  
                scanf("%d",&b[i][j]);  
        }  
        printf("The First Matrix Is: \n");  
        for(i=0; i<r1; i++)  
        {  
            for(j=0; j<c1; j++)  
                printf(" %d ",a[i][j]);  
            printf("\n");  
        }  
        printf("The Second Matrix Is:\n");  
        for(i=0; i<r2; i++)  
        {  
            for(j=0; j<c2; j++)  
                printf(" %d ",b[i][j]);  
            printf("\n");  
        }  
        printf("Multiplication of the Matrices:\n");  
        for(i=0; i<r1; i++)  
        {  
            for(j=0; j<c2; j++)  
            {  
                c[i][j]=0;  
                for(k=0; k<r1; k++)  
                    c[i][j]+=a[i][k]*b[k][j];  
                printf("%d  ",c[i][j]);  
            }  
            printf("\n");  
        }  
 
    }   
    else  
    {  
       printf("Matrix Multiplication is Not Possible");  
      }  
    }  
```
## OUTPUT 

`Enter number of rows and columns of first matrix (MAX 10)`  
`3`  
`3`  
`Enter number of rows and columns of second matrix MAX 10)`  
`3`  
`3`  
 
 `Enter First Matrix:2 2 2 2 2 2 2 2 2`  
 `Enter Second Matrix: 3 3 3 3 3 3 3 3 3`  
`The First Matrix Is:`  
 `2  2  2`  
` 2  2  2`  
 `2  2  2`  
`The Second Matrix Is:`  
 `3  3  3`  
 `3  3  3`  
` 3  3  3`  
`Multiplication of the Matrices:`  
`18  18  18`  
`18  18  18`  
`18  18  18`  


# PROGRAM NO 23:-PROGRAM TO SQUARE A NUMBER USING FUNCTIONS
```C
#include <stdio.h>  
int square (int num1);  
int main ()  
{  
   int a;  
    printf ("Enter the number :");  
    scanf ("%d",&a);  
    square (a);  
}  
int square (int num1)  
{  
int b;  
b=num1*num1;  
printf ("Square number is : %d\n",b);  
return 0;  
}  
  ```
## OUTPUT

`Enter the number :20`  
`Square number is : 400`  

# PROGRAM NO 24:-PROGRAM TO SWAP A NUMBER BY CALLING FUNCTION BY VALUE
```C
#include <stdio.h>    
int swapcbv(int num1,int num2);    
int main ()    
{    
int a,b;    
printf ("Enter the first integer:");    
scanf ("%d",&a);    
printf ("Enter the second integer:");    
scanf("%d",&b);    
printf ("\n Before Calling the Function");    
printf("Value of a=%d, Value of b =%d",a,b );     
swapcbv(a,b);    
printf ("\nAfter Calling the Function");    
printf("Value of a=%d,Value of b=%d",a,b);    
return 0;    
}    
```
## OUTPUT


`Enter the first integer:23`  
`Enter the second integer:45`  

` Before Calling the FunctionValue of a=23, Value of b =45`  
`After Calling the FunctionValue of a=23,Value of b=45`  


# PROGRAM NO 25:-PROGRAM TO SWAP TWO NUMBERS BY CALLING FUNCTION BY REFRENCE
```C
#include <stdio.h>  
int swapcbr (int *num1, int *num2);  
int main ()  
{  
int a,b; 
printf ("Enter first Integer:");  
scanf ("%d",&a);                                            
printf ("Enter second Integer:");                               
scanf ("%d",&b);                                                
printf ("\nBefore Calling Function");  
printf ("Value of a = %d, Value of b = %d", a,b);               
swapcbr(&a,&b);  
printf ("\nAfter Calling Function");  
printf ("Value of a = %d, Value of b = %d", a,b);  
return 0;  
}  
```
## OUTPUT

`Enter first Integer:100`  
`Enter second Integer:200`  

`Before Calling FunctionValue of a = 100, Value of b = 200`  
`After Calling FunctionValue of a = 200, Value of b = 100`  

# PROGRAM No 26:-PROGRAM TO FIND FACTORIAL USING RECURSION
```C
#include <stdio.h>
int multiplyNumbers(int n);
int main()
{
    int n;
    printf("Enter a positive integer: ");
    scanf("%d", &n);
    printf("Factorial of %d = %ld", n, multiplyNumbers(n));
    return 0;
}
long int multiplyNumbers(int n)
{
    if (n >= 1)
        return n*multiplyNumbers(n-1);
    else
        return 1;
}
```

## OUTPUT

`Enter a positive integer: 6`  
`Factorial of 6 = 720`  

# PROGRAM No 27:-PROGRAM TO PRINT FIBBONACCI SERIES USING RECURSSION

```C
#include<stdio.h>
 
int Fibonacci(int);
 
int main()
{
   int n, i = 0, c;
   printf ("Enter the number of terms : ");
   scanf("%d",&n);
 
   printf("Fibonacci series\n");
 
   for ( c = 1 ; c <= n ; c++ )
   {
      printf("%d\n", Fibonacci(i));
      i++; 
   }
 
   return 0;
}
 
int Fibonacci(int n)
{
   if ( n == 0 )
      return 0;
   else if ( n == 1 )
      return 1;
   else
      return ( Fibonacci(n-1) + Fibonacci(n-2) );
}
```

## OUTPUT

`Enter the number of terms :9`  
 `Fibonacci series` 
 `0`    
 `1 `   
 `1  `  
 `2  `  
 `3  `  
 `5  `  
 `8  `  
 `13  `  
 `21`  
  
 # PROGRAM No 28:-PROGRAM TO DISPLAY A STUCTURE
 ```C
 #include <stdio.h>
struct student
{
    char name[50];
    int roll;
    float marks;
} s;
int main()
{
    printf("Enter information:\n");
    printf("Enter name: ");
    scanf("%s", s.name);
    printf("Enter roll number: ");
    scanf("%d", &s.roll);
    printf("Enter marks: ");
    scanf("%f", &s.marks);
    printf("Displaying Information:\n");
    printf("Name: ");
    puts(s.name);
    printf("Roll number: %d\n",s.roll);
    printf("Marks: %.1f\n", s.marks);
    return 0;
}
```

## OUTPUT

`Enter information:`  
`Enter name: Jack`  
`Enter roll number: 23`  
`Enter marks: 34.5`  
`Displaying Information:`  
`Name: Jack`  
`Roll number: 23`  
`Marks: 34.5`  

# PROGRAM No 29:-PROGRAM TO DISPLAY ADDRESS OF A VARIABLE USING POINTERS
```C
#include <stdio.h>
void main()
{
        int n,*p;
        p=&n;
        n=100;
        printf("using variable n:\n");
        printf("value of n:%d\n address of n %u\n",n,&n);
        printf("using pointer n: \n");
        printf("value of n:%d\n address of n %u\n",*p,p);
}```

## OUTPUT
`using variable n:`  
`value of n:100`  
 `address of n 804324724`  
`using pointer n:`   
`value of n:100`  
 `address of n 804324724`  
 
# PROGRAM No 30:-PROGRAM TO PRINT ADDRESS OF A VARIABLE USING POINTERS
```C
#include <stdio.h>
void main()
{                                                                                       
       int a[10],*p,i;
       p=&a[0];
       printf("enter the elements of array\n");
       for(i=0;i<=9;i++)
       {
               printf("enter elements %02d:",i+1);
               scanf("%d",p+i);
       }
       printf("entered elements are:\n");
       printf("address:\t \t value\n");
       for (i=0;i<=9;i++)
       printf("%08x\t %03d\n",(p+i),*(p+i));
}
```

## OUTPUT

`enter the elements of array`  
`enter elements 01:12`  
`enter elements 02:13`  
`enter elements 03:1615`  
`enter elements 04:16`  
`enter elements 05:19 `  
`enter elements 06:18`  
`enter elements 07:14`  
`enter elements 08:12`  
`enter elements 09:17`  
`enter elements 10:16`  
`entered elements are:`  
`address:         value`  
`85c17510         012`  
`85c17514         013`  
`85c17518         1615`  
`85c1751c         016`  
`85c17520         019`  
`85c17524         018`  
`85c17528         014`  
`85c1752c         012`  
`85c17530         017`  
`85c17534         016`  
  
# PROGRAM No 31:-PROGRAM TO PRINT THE MULTIPLICATION TABLE OF 5
```C
#include <stdio.h>
void main()
{
        int i;
        int a=5;
        printf("table of 5\n");
        for(i=1;i<=10;i++)
        {
                printf(" %d * %d = %d \n",a,i,a*i);
        }
}
```

## OUTPUT

`table of 5`  
 `5 * 1 = 5 `  
 `5 * 2 = 10 `  
 `5 * 3 = 15 `  
 `5 * 4 = 20 `  
 `5 * 5 = 25 `  
 `5 * 6 = 30 `  
 `5 * 7 = 35 `  
 `5 * 8 = 40 `  
 `5 * 9 = 45 `  
 `5 * 10 = 50`   
