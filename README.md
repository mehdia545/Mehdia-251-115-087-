solution 3 :
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
sulution 4:
```c
#include<stdio.h>
int main()
{int M,K;
scanf("%d %d",&M,&K);
int r = M%K;
printf("%d\n",r);

return 0;


}
```
problem 1:

#include<stdio.h>
int main()
{
   int A,B,sum;
   scanf("%d %d",&A &B);
   sum = A + B;
   Printf( "%d", sum);

   return 0;
}
```
problem 2:
```c
#include<stdio.h>
int main()
{
int a;
scanf("%d",&a);
for(int i=1;i<=a;i++){
    if(a%i == 0)
    printf("%d\n",i);
}
return 0;
}

```



