solution 2 :
```c
#include<stdio.h>
int main()
{
    int N,i;
    scanf("%d",&N);
    int a[N];
    for(i= 0; i<N;i++)
    {
        scanf("%d",&a[i]);

    }
    int p = a[0],f=0;
    for(i=1;i<N;i++)

        if(a[i]<p)
        {
            f=1;
    }
    p = a[i];
    if (f == 0){
        printf("yes\n");}
        else
        {
            printf("no\n");
        }
        return 0;
    }
```
