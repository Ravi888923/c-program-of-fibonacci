# c-program-of-fibonacci
fibonacci series in non recursion form
#include<stdio.h>
#include<conio.h>
void main()
{
   int a,b,c,n,i;
   a=b=1;
   printf("Enter the no of element that you want to print fibonacci number:")
   scanf("%d",&n);
   for(i=1;i<=n;i++)
   {
      printf(""+a);
      c=a+b;
      a=b;
      b=c;
    }
  getch();
 }
