#include<string.h>
#include<stdio.h>
#include<conio.h>
void main()
{
char str[50],str2[50];
printf("Enter the string -> ");
gets(str);
strcpy(str2,str);
(strcmp(strrev(str),str2)==0)?printf("Pallindrome"):printf("Not Pallindrome");
getch();
}
// corrected second time Pallingdrome to pallindrome
