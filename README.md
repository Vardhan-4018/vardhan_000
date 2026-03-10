#include<stdio.h>
int main ()
{
    int p=10,t=10,r=5;
    float simple_interest;
    scanf("%d%d%d",p,t,r);
    simple_interest=p*t*r/100.0;
    printf("the simple interest is %d",simple_interest);
    return 0;
}

#include<stdio.h>
int main ()
{
    float f,c;
    scanf("%d",&f);
    c=f*0.5-32*0.5;
    printf("the celsius is %f",c);
    return 0;
}

int main ()
{
    int l,b,perimeter,area;
    scanf("%d%d",&l,&b);
    perimeter=2*l+2*b;
    area=l*b;
    printf("the perimeter is %d",perimeter);
    printf("the area is %d",area);
    return 0;
}

int main ()
{
    int a,area;
    scanf("%d",&a);
    area=a*a;
    printf("the area of the square is %d",area);
    return 0;
}

int main ()
{
    int r;
    float area;
    scanf("%d",&r);
    area=3.14*r*r
    printf("the area is %d",area);
    return 0;
}

int main ()
{
    int a,b;
    float area;
    scanf("%d%d",&a,&b);
    area=1/2.0*a*b;
    printf("the area of the triangle is %f",area);
    return 0;
}

int main ()
{
    float f,c;
    scanf("%d",&c);
    f=c*1.8+32;
    printf("the farenheit is %f",f);
    return 0;
}

int main ()
{
    float a,b,sum;
    scanf("%f%f",&a,&b);
    sum=a+b;
    printf("the sum of floating points is %f",sum);
    return 0;
}

int main ()
{
    int a,b,sum;
    scanf("%d%d",&a,&b);
    sum=a+b;
    printf("the sum of two integers is %d",sum);
    return 0;
}

//To display our name.
#include<stdio.h>
int main()
{
printf("My name is panda");
printf("Welcome to SIMATS");
return 0;
}

//Find the area of circle
#include<stdio.h>
void main()
{
constant float pi=3.14;
float r=10,area;
area=pi*r*r;
printf("%.2f",area);
}

//FInd the area of circle using define
#include<stdio.h>
#define pi 3.14
void main()
{
int r;
float area;
area=pi*r*r;
printf(".2f",area);
}

//decimal to octal
#include<stdio.h>
void main()
{
int a=20;
printf("Octal number=%o",a);
}

//decimal to hexa
#include<stdio.h>
void main()
{
int a=20;
printf("Hexadecimal=%x",a);
}

//Octal to decimal
#include<stdio.h>
void main()
{
int a=010;
printf("Decimal=%d",a);
}

//Hexadecimal to decimal
#include<stdio.h>
void main()
{
int a=0x15;
printf("Decimal=%d",a);
}

//Print character and find ASCII value
#include<stdio.h>
void main()
{
char ch='g';
printf("ch=%c\n",ch);
printf("ch=%d,hence an integer\n",ch);
printf("ch1=%c\n,ch+1);
printf("ch1=%d,hence an integer",ch+1);
}

//To find quotient and ramainder
#include<stdio.h>
int main()
{
int a=5;
int q,r;
q=a/2;
r=a%2;
printf("Quotient=%d\n",q);
print("Remainder=%d",r);
return 0;
}

//Area of traingle
#include<stdio.h>
int main()
{
int b=3,h=3;
float area;
area= (1/2.0)*b*h;
printf("Area=%.2f",area);
return
}

//To swap two integers using third variable
#include<stdio.h>
int main()
{
int a=10,b=20,t;
printf("a=%d\tb=%d\n",a,b);
t=a;
a=b;
b=t;
print("a=%d\tb=%d",a,b);
return 0;
}

//Swapping without third variable
#include<stdio.h>
int main()
{
int a=10,b=20;
printf("a=%d\tb=%d\n",a,b);
a=b;
b=a/2;
printf("a=%d\tb=%d",a,b);
return 0;
}

//To dispaly a number if it is negative
#include<stdio.h>
int main()
{
int number;
scanf("%d",&number);
if (number<0){
printf("You entered %d\n",number);
}
printf("The if statement is easy");
return 0;
}

//To find whether a integer is odd or even
#include<stdio.h>
int main()
{
int n;
printf("Enter the number= ");
scanf("%d",&number);
if (n%2==0){
printf("%d is even",n);
}
else{
printf("%d is odd",n);
}
return 0;
}

//Eligible to vote or not
#include<stdio.h>
int main()
{
int age;
printf("Enter the age =");
scanf("%d",&age);
if (age>18)
{
print("%d is eligible to vote",age);
}
else{
printf("%d is not elligible to vote",age);
}
return 0;
}

//To find a student pass or fail
#include<stdio.h>
int main()
{
int n;
printf("Enter the n= ");
scanf("%d",&n);
if (n>=35)
{
printf("%dis pass",n);
}
else
{
printf("%d is fail",n);
}
return 0;
}
