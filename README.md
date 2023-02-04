//# positive_null_negative.c//
#include<stdio.h>
int main()
{
    int n;
    printf("Enter number:");
    scanf("%d",&n);
    if(n>0)
    {
        printf("Entered number is positive.\n");
    }
    else if(n=0)
    {
        printf("Entered number is null.\n");
    }
    else if(n<0)
    {
        printf("Entered number is negative.\n");
    }
    else
    {
        printf("invalid input.");
    }
}
