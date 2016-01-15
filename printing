#include<stdio.h>
void main()
{
	int value,n,i,j,first,c,a[100],x,y;
	printf("Entre the total values ");
	scanf("%d",&value);
	printf("Enter the subset values");
	for(i=0;i<value;i++)
	scanf("%d",&a[i]);
	printf("The subsets are :\n");
	for(j=1;j<=value;j++)
	{
        for(first=0;first<=(value-j);first++)
        {
            if(j==1)
            {
                printf("%d\n",a[first]);
            }
            else
            {
                c=first+(j-1);
                for(y=c;y<value;y++)
                {
                    for(x=first;x<c;x++)
                    {
                        printf("%d\t",a[x]);
                    }
                    printf("%d\n",a[y]);

                }
            }
        }
	}

}
