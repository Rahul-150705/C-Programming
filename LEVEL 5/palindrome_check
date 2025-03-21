#include<stdio.h>
#include<string.h>
int palindrom_e(char a[100],int f)
{
    char b[100];
    for (int i=strlen(a)-1;i>=0;i--)
{
    b[f]=a[i];
    f++;
}
if(strcmp(a,b)==0)
{
    return 1;
}
return 0;
}
int main()
{
char a[100];
scanf("%[^\n]",a);
char b[100];
int v=0;
int g=palindrom_e(a,v);
if (g==1)
{
    printf("Its A Palindrome");
}
else
{
    printf("Its Not A Palindrome");
}
}
