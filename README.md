
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int a,b,c,max,min;
    printf("enter value of a: ");
    scanf("%d",&a);
    printf("enter value of b: ");
    scanf("%d",&b);
    printf("enter value of c: ");
    scanf("%d",&c);

    if (a>b && a>c);
    {
    printf("\n%d is maximum",a);
    max= a;
    }

    else if (b>a && b>c);
    {
    printf("\n%d is maximum",b);
    max= b;
    }
    else if (c>a && c>b);
    {
    printf("\n%d is maximum",c);
    max= c;
    }
    if (a<b && a<c);
   {
    printf("\n%d is minimum",a);
    min= a;
   }

    else if (b<a && b<c);
    {
    printf("\n%d is minimum",b);
    min= b;
    }

    else if (c<b && c<a);
    {
    printf("\n%d is minimum",c);
    min= c;
    }

    max= max+min;
    min= max-min;
    max= max-min;

    printf("\nvalues after swapping are given as follow: ");
    printf("\n\nmaximum value: %d",max);
    printf("\n\nminimum value: %d",min);
    return 0;




}

