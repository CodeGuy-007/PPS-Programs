``				Project File				``
----------------------------------------------------------------------
``			Programming for Problem Solving			``
----------------------------------------------------------------------	
	Name: Akshat Saluja
  	Branch: IT-A1
  	Roll No: 1921007
  	Submitted To: Prof. Ranjodh Kaur
------------------------------------------------------------------	


////////////////////// Displaying College Address  /////////////////////
```
#include<stdio.h>
int main()
{
    printf("Guru Nanak Dev Engineering College,\nGill Road,\nLudhiana, Punjab");
    return 0;
}

Output:
Guru Nanak Dev Engineering College,
Gill Road,
Ludhiana, Punjab
```

////////////////////// Fahrenheit to Centigrade /////////////////////////
```
#include <stdio.h>
float temp_f;     /* degrees fahrenheit */
float temp_c;     /* degrees centigrade */

int main() {
printf("Input a temperature (in Centigrade): ");
scanf(line_text, "%f", &temp_c);

temp_f = ((9.0 / 5.0) * temp_c) + 32.0;
printf("%f degrees Fahrenheit\n", temp_f);

return(0);
}


Output:
Input a temperature (in Centigrade): 45                                                                       
113.000000 degrees Fahrenheit

```

///////////////////////////  Function Calling  ///////////////////////////////////
```
#include<stdio.h>
int akshat();            //function declaration ,different from variable declaration (like int a)//
int main()              //a function is always declared before starting the main program//
{
int akshat()
{

printf(" hi Akshat");

}
akshat();
return 0;
}

output:
hi Akshat
```


///////////////////////////////  Even-Odd  /////////////////////////
```
#include<stdio.h>
int main()
{
     int a;
     printf("\nEnter the  number:");
     scanf("%d", &a);
     if(a%2==0)
     printf("\n\nThe number you entered is EVEN\n\n");
     else
     printf("\n\nThe number you entered is ODD\n\n");

     return 0;
}
                                                                                                           
Output:
Enter the  number:8


The number you entered is EVEN
```

////////////////////////// The Fizz Buzz Game /////////////////////////
              
```			  
#include<stdio.h>
int main()
{                                                                                                                                     int a,b,c,d;
        printf("\n So lets start the game");
        printf("\n Enter the number:");
        scanf("%d", &a);                                                                                                               			b=a%3;c=a%5;
        d=a%15;
        if (d==0)       
		{                                         
		printf("\n\nfizzbuzz\n\n");
        	}
        else if (b==0)
        {
                printf("\n\nfizz\n\n");
        }
        else if (c==0)
        {        
		printf("\n\nbuzz\n\n");                                        
        }
        else
        {
        printf("\n\n %d \n\n", a);
        }
}                                                                                                                                                                                                                                                      

Output:
 So lets start the game
 Enter the number:45


fizzbuzz
```

/////////////////////////////Sum and Average of 5 Numbers//////////////////

```
#include <stdio.h>
 
void main(){
	int n, i, sum = 0;
    float avg; 
	for(i = 0; i < 5; i++){
		printf("enter the %d number:",i+1)
		scanf("%d", &n);
		sum += n;
	}
	avg = sum / 5;
	printf("Sum of numbers is %d and average is %d",sum,avg)
}

Output:
enter the 1 number:5
enter the 2 number:6
enter the 3 number:7
enter the 4 number:8
enter the 5 number:9
Sum of numbers is 35 and average is 7
```

//////////////////////////////  Table of any Whole Number /////////////////////////// 

```
#include<stdio.h>
int main()
{
   int i,j,k;
   printf("Kindly enter the number whose table is required :");
   scanf("%d",&i);
   for(j=0;j<11;j++)
    {
      i*j;
      printf("%d multiplied by %d gives %d\n",i,j,i*j);
    }
 return 0;
}

Output:
Kindly enter the number whose table is required :19
19 multiplied by 0 gives 0
19 multiplied by 1 gives 19
19 multiplied by 2 gives 38
19 multiplied by 3 gives 57
19 multiplied by 4 gives 76
19 multiplied by 5 gives 95
19 multiplied by 6 gives 114
19 multiplied by 7 gives 133
19 multiplied by 8 gives 152
19 multiplied by 9 gives 171
19 multiplied by 10 gives 190
```

////////////////////////////////////  Tables in Range  //////////////////////////

```

#include<stdio.h>
int main()
{
   int h,i,j,k;
   printf("Kindly enter the first number of the range :");
   scanf("%d",&h);
   printf("Kindly enter the last  number of the range :");
   scanf("%d",&i);
  for(h=h;h<=i;h++)
    {
      for(j=0;j<11;j++)
        {
          h*j;
          printf("%d multiplied by %d gives %d\n",h,j,h*j);
        }
    }
 return 0;
}

Output:
Kindly enter the first number of the range :12
Kindly enter the last  number of the range :14
12 multiplied by 0 gives 0
12 multiplied by 1 gives 12
12 multiplied by 2 gives 24
12 multiplied by 3 gives 36
12 multiplied by 4 gives 48
12 multiplied by 5 gives 60
12 multiplied by 6 gives 72
12 multiplied by 7 gives 84
12 multiplied by 8 gives 96
12 multiplied by 9 gives 108
12 multiplied by 10 gives 120
13 multiplied by 0 gives 0
13 multiplied by 1 gives 13
13 multiplied by 2 gives 26
13 multiplied by 3 gives 39
13 multiplied by 4 gives 52
13 multiplied by 5 gives 65
13 multiplied by 6 gives 78
13 multiplied by 7 gives 91
13 multiplied by 8 gives 104
13 multiplied by 9 gives 117
13 multiplied by 10 gives 130
14 multiplied by 0 gives 0
14 multiplied by 1 gives 14
14 multiplied by 2 gives 28
14 multiplied by 3 gives 42
14 multiplied by 4 gives 56
14 multiplied by 5 gives 70
14 multiplied by 6 gives 84
14 multiplied by 7 gives 98
14 multiplied by 8 gives 112
14 multiplied by 9 gives 126
14 multiplied by 10 gives 140

```

/////////////////////////////////  Even  tables in Range  ///////////////////////////////

```
#include<stdio.h>
int main()
{
   int h,i,j,k;
   printf("Kindly enter the first number of the range :");
   scanf("%d",&h);
   printf("Kindly enter the last  number of the range :");
   scanf("%d",&i);
  for(h=h;h<=i;h++)
    {
     if(h%2==0)
      {
        for(j=0;j<11;j++)
                {
                        h*j;
                        printf("%d multiplied by %d gives %d\n",h,j,h*j);
                }
      }
    }
 return 0;
}

Output:
Kindly enter the first number of the range :21
Kindly enter the last  number of the range :25
22 multiplied by 0 gives 0
22 multiplied by 1 gives 22
22 multiplied by 2 gives 44
22 multiplied by 3 gives 66
22 multiplied by 4 gives 88
22 multiplied by 5 gives 110
22 multiplied by 6 gives 132
22 multiplied by 7 gives 154
22 multiplied by 8 gives 176
22 multiplied by 9 gives 198
22 multiplied by 10 gives 220
24 multiplied by 0 gives 0
24 multiplied by 1 gives 24
24 multiplied by 2 gives 48
24 multiplied by 3 gives 72
24 multiplied by 4 gives 96
24 multiplied by 5 gives 120
24 multiplied by 6 gives 144
24 multiplied by 7 gives 168
24 multiplied by 8 gives 192
24 multiplied by 9 gives 216
24 multiplied by 10 gives 240
```

////////////////////////////  Star Pattern ///////////////////////////  

```
#include<stdio.h>
int main()
{
    int i, j;
    for (i=0 ; i<5 ; i++)
    {   
		for (j=0 ; j<i ; j++)
      {
       printf(" * ");
      }
     printf("\n");
    }

}


Output:
*
**
***
****
```

///////////////////////////  Storing and Displaying data in Array  //////////////////////////


```
#include<stdio.h>
int main()
{
	int i,j,k;
	char name[6];
for(i=1;i<6;i++)
	{
		printf("Enter the name of patient number %d :,i");
		scanf("%c,&name[i]");
	}

for(k=1;k<6;k++)
	{
		printf("Enter the Patient No. Whose name you want to display :");
		scanf("%d,&j");
		i=j;
		printf(" The patient name is %c",name[j]);
	}
return 0;
}

```


////////////////////////////// Prime Number ////////////////////////////////////

```

#include<stdio.h>
int main()
{
        int i,j,k,l;
        printf("\nEnter the number to check whether it is prime or not :");
        scanf("%d",&i);l=3;
        for(j=2;j<i;j++)
                {
                if(l!=0){
                                k=i%j;
                        if(k==0)
                                {
                                        printf("\nthe number you entered is not a prime number\n\n");l=0;
                                }
                        }
                }
        if(l!=0)
                        {
                                printf("\nthe number you entered is a prime number\n\n");
                        }
        return 0;
}

Output:
Enter the number to check whether it is prime or not :17

the number you entered is a prime number

```

//////////////////////////////  Operator Operand  //////////////////////////

```
#include<stdio.h>
int main()
{
float a,b;
 char c;
printf("enter first  number:");
scanf("%f",&a);
printf("enter operator[+ - % / *]:");
scanf(" %c",&c);
printf("enter second number:");
scanf("%f",&b);
int d,r;
d=(int) a;
r=(int) b;
switch(c)
{
case '+': printf("The result is:%.2f\n",a+b); break;
case '-':printf("The result is:%.2f\n",a-b); break;
case '*':printf("The result is:%.2f\n",a*b); break;
case '%':printf("The result is:%d\n",d%r); break;
case '/':printf("The result is:%.2f\n",a/b); break;
default : printf("Enter correct operator ");
}
return 0;
}

Output:
enter first  number:20
enter operator[+ - % / *]: *
enter second number:10
The result is:200.00
```

///////////////////////////////  Calculator  /////////////////////////////

``` 
#include<stdio.h>
void main()

{ 
puts(" _______________");
puts("|               |");
puts("|_______________|");
puts("| 1 | 2 | 3 |   |");
puts("|___|___|___|   |");
puts("| 4 | 5 | 6 | + |");
puts("|___|___|___|___|");
puts("| 7 | 8 | 9 | - |");
puts("|___|___|___|___|");
puts("|     0     | * |");
puts("|___________|___|");
}

Output:
_______________
|               |
|_______________|
| 1 | 2 | 3 |   |
|___|___|___|   |
| 4 | 5 | 6 | + |
|___|___|___|___|
| 7 | 8 | 9 | - |
|___|___|___|___|
|     0     | * |
|___________|___|

```

///////////////////////////  Greteast of Two Numbers  //////////////////////

```
#include<stdio.h>
int main()
{
    int num1, num2;
    printf("Enter the first number: ");
    scanf("%d", &num1);
    printf("Enter the second number: ");
    scanf("%d", &num2);
    if (num1 > num2)
    printf("First Number is Greatest i.e %d", num1);
    else
    printf("Second Number is Greatest i.e %d", num2); 
    return 0;
}

Output:
Enter the first number: 189
Enter the second number: 222
Second Number is Greatest i.e 222
```

///////////////////////////////  Area and Volume of Rectangle  ///////////////////////

```
#include<stdio.h>
int main()
{
 int l,b,h;
 printf("Enter length of rectangle:");
 scanf("%d",&l);
 printf("\nEnter breadth of rectangle:");
 scanf("%d",&b);
 printf("\nEnter height of rectangle:");
 scanf("%d",&h);
 printf("\nThe area of rectangle is:%d",l*b);
 printf("\nThe volume is :%d\n",l*b*h);
 return 0;
 }
 
 Output:
 Enter length of rectangle:4 

Enter breadth of rectangle:3 

Enter height of rectangle:4

The area of rectangle is:12
The volume is :48

```

////////////////////////////////////  Area,Diameter,Circumference of Circle  //////////////////////////////

```
 #include<stdio.h>
 int main()
  {
   float a;   
   const float pi=3.14;
   printf("Enter radius of circle:");
    scanf("%f\n",&a);
  printf("diameter of circle is:%f\n",2*a);
  printf("circumference of circle:%f\n",2*pi*a);
  printf("Area of circle:%f\n",pi*a*a);
return 0;
 } 
 
Output:
Enter radius of circle:6
diameter of circle is:12.000000
circumference of circle:37.680000
Area of circle:113.040001
```

//////////////////////////////  Factorial of any Number  ////////////////////////////////

```
#include<stdio.h>
int main()
{
int a,result=1;
printf("Enter the factorial of:");
scanf("%d",&a);
for(int i=a;i>=1;i--)
{
printf("%d X ",i);
result=result*i;
}
printf("= %d\n",result);
return 0;
}

Output:
Enter the factorial of:5
5 X 4 X 3 X 2 X 1 X = 120
```
