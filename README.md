# programme in C language on switch statement
 programme on switch to understand how actually switch statement work
#include<stdio.h>
int main()
{
    int age,marks;
    printf("Enter your age\n");
    scanf("%d", &age);

    printf("Enter your marks\n");
    scanf("%d", &marks);

    switch (age)
    {
    case 12:
        printf("your age is 12\n");
        break;

    case 23: 
        printf("your age is 23\n");
         break;

    switch (marks)
    {
    case 98:
        printf("your marks is 98\n");
        break;
    
    default:

    printf("Your marks is not 98 \n");
        break;
    }

    case 29:
        printf("your age is 29\n");
    break;
    
    default:
     printf("your age is not 12,23,29\n");

        break;
    }


    return 0;


}