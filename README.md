# Role-Hierarchy
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
struct roleH{
    char z;
};

void child();
void main()
{
    int n,i,x,y;
    char r,z,sub;
    printf("Enter the root role name");
    scanf("%s",&r);
    printf("%c",r);
    printf("Operations");
    printf("\n1.Add Sub role");
    while(1)
    {
    printf("\nOperation to be performed");
    scanf("%d",&n);
    switch(n)
    {
        case 1:
         printf("Enter the subrole");
         scanf("%s",&sub);
         child();
        printf("Enter reporting to roll name");
        scanf("%s",&z);
            break;
        default:
        break;
    }
    }
    void child(struct )
    {
        if(z.left==NULL)
        {
            z.left=sub;
        }
        else
        {
            z.right=sub;
        }
    }
    
}
