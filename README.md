# Eligibilty-of-voting-system-
#include<stdio.h>
#include<conio.h>
void main()
{
 int age;
 clrscr();
 printf(" Please Enter  the Age :");
 scanf("%d",&age);
 if(age>=18 && age<100)
 {
  printf(" you are Eligible For Vote ");
 }
 else if(age<18 && age>0)
 {
  printf(" you are Not Eligible For Vote ");
 }
 else
 {
  printf("Invalid Age !");
 }

 getch();
}
