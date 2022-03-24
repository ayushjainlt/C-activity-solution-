#include<stdio.h>
int sum()int a,int b)
{
return a+b;
}
int main()
{
int num1,num2,num3;
printf("Enter First Number: ");
scanf("%d",&num1);
printf("Enter Second Number: ");
scanf("%d",&num2);
num3 = sum(num1,num2);
printf("Sum of the entered numbers: %d",num3);
return 0;
}
