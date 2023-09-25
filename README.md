# DecimalToBinary
#include<stdio.h>
#include<stdlib.h>
int main()
{
	int num=0,bit=0;
	system("clear");
	printf("Enter the decimal number:");
	scanf("%d",&num);
	printf("Binary Equivalent....");
	if (num==0) 
	printf("\n0");
	while(num!=0)
	{
		bit=num%2;
		printf("%d",bit);
		num=num/2;
		
	}
	printf("\n\n");
	return 0;
}
