# matrix-addition
#include <stdio.h>

int main()
{
    int a[5][5],b[5][5],rows,columns;
    printf("enter the rows and columns:");
    scanf("%d%d",&rows,&columns);
    printf("enter first array:\n");
    for(i=0;i<rows;i++)
    {
        for(j=0;j<columns;j++)
        {
            scanf("%d",&a[i][j]);
        }
    }
    printf("enter the second array:\n");
    for(i=0;i<rows;i++)
    {
        for(j=0;j<columns;j++)
        {
            scanf("%d",&b[i][j]);
        }
    }
    int c[i][j]=0;
    for(i=0;i<rows;i++)
    {
        for(j=0;j<columns;j++)
        {
            c[i][j]=a[i][j]+b[i][j];
        }
    }
    for(i=0;i<rows;i++)
    {
        for(j=0;j<columns;j++)
        {
            printf("%d",c[i][j]);
        }
   printf("\n");
    }
    

}
    output:
    enter the rows and coloumns:2
    2
    enter first array:
    1
    2
    3
    4
    enter second array:
    1
    2
    3
    4
    2 4
    6 8
