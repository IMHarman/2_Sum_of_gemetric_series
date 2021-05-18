#include <stdio.h>
#include <stdlib.h>
#include <math.h>

int main()
{
    int a, r, n, i, sum=0;
    printf("Enter the first number of the series: ");
    scanf("%d",&a);
    printf("Enter the common ratio of the series: ");
    scanf("%d",&r);
    if(r == 1)
    {
        printf("Common ratio can't be 1.");
        return 0;
    }
    printf("Enter the number of terms to be shown: ");
    scanf("%d",&n);
    printf("Series: ");

    for(i=0; i<n; i++)
    {
        sum+= a*(pow(r,i));
        printf("%d",sum);
        printf(" ");
    }
    return 0;
}
