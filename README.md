//# Let-Us-C-chapter2_question2
//finding the reverse of a number
#include<stdio.h>
int main()
{
int num,digit,reverse=0;
printf("Enter a five digit number:");
scanf("%d",&num);
digit=num/10000;
reverse=reverse*10+digit;
num%=10000;
digit=num/1000;
reverse=reverse*10+digit;
num%=1000;
digit=num/100;
reverse=reverse*10+digit;
num%=100;
digit=num/10;
reverse=reverse*10+digit;
num%=10;
reverse=reverse*10+num;
return 0;
}
