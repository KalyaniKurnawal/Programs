# Programs
#include<stdio.h>
int main ()
{
int i=10,j=20;
printf("%d\n",func(i,j));
}
func(int a,int b)
{
a=a-5;
b++;
printf("%d\n",(!a+--b));
	return (!a+--b);
}
########################
Done.
###################
