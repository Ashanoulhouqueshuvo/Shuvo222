# Shuvo222
1 to n number sum (dynamic)
#include<stdio.h>
void main()
{

int n,i,sum;
printf("Enter The number you want to calculate:");
scanf("%d",&n);
for(int i=1;i<=n;i++)
{

sum=sum+i;

printf("%d\n",sum);
}
}
