# PROGRAMMING FOR PROBLEM SOLVING 

### NAME - GURASHISH SINGH 

### ROLL NO - 1915022

### BRANCH - COMPUTER SCIENCE 

### SECTION - CSE (A1)



# PROGRAM NO 1 : PROGRAM TO PRINT WELCOME MESSAGE 

 ` #include <stdio.h>`  
   `void main ()`  
  ` {`  
     `puts ("Welcome Budding Engineers");`  
   `}`  
   
   ## OUTPUT
   
   `Welcome Budding Engineers `
   
   
   
   # PROGRAM NO : 2 PROGRAM TO PRINT THE ADDRESS
   
  ` include <stdio.h>`  
`void main ()`  
`{`  
`puts ("House Number : 111");`  
`puts ("Street Number : 2");`  
`puts ("XYZ Nagar ");`  
`puts ("Patiala");`  
`}`  

## OUTPUT

`House Number : 111`  
`Street Number : 2`  
`XYZ Nagar`   
`Patiala`  

# PROGRAM NO 3 : PROGRAM TO FIND THE SUM OF TWO NUMBERS 

`#include <stdio.h>`  
`int main ()`  
`{`  
`int a,b,c;`  
`printf ("Enter first variable : ");`  
`scanf ("%d",&a);`  
`printf("Enter second variable : ");`  
`scanf ("%d",&b);`  
`c = a+b; `                                                
`printf("Sum of two variables is : %d\n",c);`  
`return 0;`                                                      
`}`  

## OUTPUT 

`Enter first variable : 10`  
`Enter second variable : 20`  
`Sum of two variables is : 30`  

# PROGRAM NO 4 : PROGRAM TO CONVERT TEMPERATURE FROM CELCIUS TO FAHRENHEIT

`#include <stdio.h>`  
`void main ()`                                                   
`{`  
`float num1,num2;`  
`printf ("\nEnter value in centigrade:\n");`  
`scanf ("%f",&num1);`  
`num2 = (num1*9/5)+32;`  
`printf ("\nValue in farenheit is :%.2f\n",num2 );`  
`}`  

## OUTPUT

`Enter value in centigrade:`  
`100`  

`Value in farenheit is :212.00`  

# PROGRAM NO 5 : PROGRAM TO FIND AREA AND PERIMETER OF A CIRCLE

`#include <stdio.h>`  
`int main ()`  
`{`  
`float radius,area, peri,pi=3.14 ;`  
`printf("Enter radius of circle :");`  
`scanf ("%f",&radius);`  
`area=pi*radius*radius;`  
`peri=2*pi*radius;`  
`printf("Area of circle : %f,",area);`  
`printf("Perimeter of circle : %f",peri);`  
`return 0;`  
`}`  

## OUTPUT 

`Enter radius of circle :5`  
`Area of circle : 78.500000,Perimeter of circle : 31.400002`  

# PROGRAM NO 6 : PROGRAM TO SWAP TWO NUMBERS WITHOUT USING THIRD VARIABLE 

`#include <stdio.h>`  
`int main ()`  
`{ `                                                                  
`int a,b;`  
`printf ("\nEnter the  value of a :");`  
`scanf ("%d",&a);`  
`printf ("\nEnter the value of b :");`  
`scanf ("%d",&b);`  
`a=a+b;`   
`b=a-b;`  
`a=a-b;`  
`printf ("\nThe swaped values of a : %d\n",a);`  
`printf ("\nThe swaped value of b : %d \n",b);`  
`return 0;`  
`}`  

## OUTPUT 
`Enter the  value of a :10`  

`Enter the value of b :20`  

`The swaped values of a : 20`  

`The swaped value of b : 10 `    

# PROGRAM NO 7 : PROGRAM TO CHECK WHETHER THE NUMBER IS EVEN OR ODD

`#include <stdio.h>`  
`int oddeven(int num1);`  
`int main ()`  
`{`  
`int s ;`  
`printf ("Enter the integer:");`  
`scanf ("%d",&s);`  
`oddeven (s);`  
`return 0;`  
`}`  
`int oddeven(int num1)`  
`{`  
`if (num1%2==0)`  
`printf ("The number is even");`  
`else`  
`printf ("The number is odd:");`  
`return 0;`  
`}`  

## OUTPUT 

`Enter the integer:177`  
`The number is odd`  

# PROGRAM NO 8 : PROGRAM TO FIND FACTORIAL OF A NUMBER 

`#include <stdio.h>`  
`void main()`  
`{`  
`int a,n=1,i;`  
`printf("enter i : ");`  
`scanf("%d",&i);`  
`for(a=1;a<=i;a++)`  
`n=n*a;`  
`printf("factorial of i is %d \n",n);`  
`}`  

## OUTPUT 

`enter i : 5`  
`factorial of i is 120`  

# PROGRAM NO 9 : PROGRAM TO REVERSE A NUMBER 

`#include <stdio.h>`  
`int main ()`  
`{`  
`int n , reverse =0;`  
`printf ("Enter the number to be reversed:\n");`  
`scanf ("%d",&n);`  
 
`while(n!=0)`  
`{`  
`reverse = reverse*10;`  
`reverse = reverse + n%10;`  
`n=n/10;`  
`}`  
`printf ("Reverse number is:%d\n",reverse);`  
`return 0;`  
`}`  

## OUTPUT 

`Enter the number to be reversed:`  
`1598`  
`Reverse number is:8951`   

# PROGRAM NO 10 : PROGRAM TO PRINT FIZZBUZZ

`#include <stdio.h>`  
`void main()`  
`{`  
`int a,i;`  
`printf("enter the number ");`  
`scanf("%d",&a);`  
`for(i=1;i<=a;i++)`  
`{ if (i%15==0)`  
`printf("fizzbuzz\n");`  
`else if(i%5==0)`  
`printf("buzz\n");`  
`else if(i%3==0)`  
`printf("fizz\n");`  
`else`  
`printf("%d\n",i);`  
`}`  
`return 0;`  
`}`  

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

`#include <stdio.h>`  
`int main ()`  
`{`  
`int day;`  
`printf ("Enter the number of day (Consider Monday = 1 and Sunday = 7) : ");`  
`scanf ("%d",&day);`  
`switch (day)`  
`{`  
`case 1:`  
`printf ("\nToday is Monday\n ");`  
`break;`  
`case 2:`  
`printf  ("\nToday is Tuesday\n");`  
`break;`  
`case 3:`  
`printf ("\nToday is Wednesday\n");`  
`break;`              
`case 4:`  
`printf("\nToday is Thursday\n");`   
`break;`  
`case 5:`  
`printf ("\nToday is Friday\n");`  
`break ;`  
`case 6:`  
`printf ("\nToday is Saturday\n");`  
`break;`  
`case 7:`  
`printf("\nToday is Sunday\n");`  
`break;`  
`default :`  
`printf ("Please Enter a valid number ");`  
`}`  
`return 0;`  
`}`  

## OUTPUT 

`Enter the number of day (Consider Monday = 1 and Sunday = 7) : 3`  

`Today is Wednesday`  

# PROGRAM NO 12 : PROGRAM TO MAKE A CALCULATOR 

`#include <stdio.h>`  
`int main ()`  
`{`  
`int num1,num2;`  
`char ch;`  
`float result;`  
`printf ("Enter the first number:");`  
`scanf ("%d",&num1);`  
`printf ("Enter the second number:");`  
`scanf ("%d",&num2);`  
`printf ("Choose the operation to perform(+,-,*,/):");`  
`scanf ("%c",&ch);`  
`result=0;`  
`switch(ch)`  
`{`  
`case '+':`  
`result = num1+num2;`   
`break;` 
`case '-':`  
`result = num1-num2;`  
`break;`  
`case'*':`  
`result = num1*num2;`  
`break;`  
`case '/':`  
`result = num1/num2;`  
`break;`  
`default:`  
`printf ("Invalid operation.\n");`  
`}`  
`printf ("Result: %d %c %d = %f\n",num1,ch,num2,result);`  
`return 0;`  
`}`  

## OUTPUT 

`Enter the first number:106`  
`Enter the second number:67-`  
`Choose the operation to perform(+,-,*,/):Result: 106 - 67 = 39.000000`  

# PROGRAM NO 13 : PROGRAM TO CHECK WHETHER A YEAR IS LEAP YEAR OR NOT 

`#include <stdio.h>`  
 `int main ()`  
`{`  
`int year;`  
`printf("Enter the year : ");`  
`scanf ("%d",&year);`  

`if (year%4==0)`  
  `{`  
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

## OUTPUT 

`Enter the year : 2019`  
`2019 is not a leap year`  

# PROGRAM NO 14 : PROGRAM TO CHECK WHETHER A NUMBER IS PRIME OR NOT 

`#include <stdio.h>`  
`int main ()` 
`{`  
`int n,i,flag=0;`  
`printf ("Enter the number : ");`  
`scanf ("%d",&n);`  
`for (i=2 ; i<=n/2 ; i++)`   
`{`              
`if (n%i == 0)`  
  `{`  
   ` flag = 1;`  
        `break;`    
   ` }`           
`}`              
`if (n==1)`         
`{`  
  `printf ("1 is neither a prime nor a composite number ");`  
`}`  
`else `  
`{`  
  `if (flag ==0)` 
`printf ("%d is a prime number.",n);`  
  `else`   
`printf ("%d is not a prime number.",n);`  
`}`  
`return 0;`  
`}`  

## OUTPUT 

`Enter the number : 235`  
`235 is not a prime number`  

# PROGRAM NO 15 : PROGRAM TO CHECK WHETHER A NUMBER IS PALLINDROME OR NOT 

`#include <stdio.h>`  
`int main ()`  
`{`  
   ` int n, reverse=0,t;`  
    `printf("Enter a number to check if it is a palindrome or not\n");`  
    `scanf("%d",&n);`  
   ` t=n;`  
    `while (t!=0)`  
    `{`  
     `reverse = reverse*10;`  
     `reverse = reverse + t % 10;`  
     `t = t/10;`  
     `}`  
`if (n==reverse)`  
`printf ("%d is a palindrome number.\n",n);`  
`else`   
`printf ("%d is not a palindrome number.\n",n);`  
`return 0;`  
`}`  

## OUTPUT 

`Enter a number to check if it is a palindrome or not`  
`1221`  
`1221 is a palindrome number.`

# PROGRAM NO 16 : PROGRAM TO PRINT FIBONACCI SERIES 

`#include <stdio.h>`  
`int main ()`  

`{`  
`int i,n,t1=0,t2=1,next;`  
`printf("Enter the number of terms :");`  
`scanf ("%d",&n);`  
`printf ("Fibonacci Series ");`  
`for (i=1;i<=n;i++)`  
`{`  
`printf ("\t%d\t",t1);`  
`next = t1+t2;`  
`t1=t2;`  
`t2=next; ` 
`}`  
`return 0;`  
`} `  

## OUTPUT 

`Enter the number of terms :9`  
`Fibonacci Series        0  1  1  2  3  5  8  13  21`   
