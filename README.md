# gift
This is a program for gift distribution among scholars in c programming.
#include<stdio.h>
#include<conio.h>
void main()
{
	int a;
	printf("Press 1 for maths");
	printf("\nPress 2 for science");
	printf("\nPress 3 for both");
	printf("\nEnter how many exams you have passed in a:");
	scanf("%d",&a);
	if(a==1||a==2)
	{
		printf("You are awarded with Rs 15");
	}
	else if(a==3)
	{
		printf("You are awarded with Rs 45");
	}
	else
	{
		printf("Sorry");
	}
}
