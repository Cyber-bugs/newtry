#include<stdio.h>
main()
{
    int n,i=1;
    long sum=0;
    scanf("%d",&n);
    while(i<n)
    {
        printf("%d*%d+",i,i);
        sum+=i*i;
        i++;
    }
    sum+=i*i;
    printf("%d*%d=%ld",i,i,sum);
    return 0;
}
