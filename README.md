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

/To display our name.
#include<stdio.h>
int main()
{
printf("My name is panda");
printf("Welcome to SIMATS");
return 0;
}
