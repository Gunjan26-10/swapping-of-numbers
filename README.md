# swapping-of-numbers
Developed by Gunjan Narkhede
#include<stdio.h>
int main()
{
	int a,b;
	printf("enter two numbers:");
	scanf("%d %d",&a,&b);
	a=a+b;
	b=a-b;
	/* is independant of a>b or a<b*/
	a=a-b;
	printf("%d %d",a,b);
}
