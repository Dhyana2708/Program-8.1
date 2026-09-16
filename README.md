# Program-8.1
This program is for calculting the sum of Square of 10 integral digits scanned form user using Arrays concept
#include<stdio.h>
int main()
{
     //Dhyana Gandhi; IT; Batch:F3;
    //Program for finding sum of 10 scanned integers
    printf("Program for finding sum of 10 scanned integers \n");
    
    
    int Xi[10];
    int i, j, sum;
    printf("Enter 10 integral values: \n");
    for(i=0; i<10; i++)
        {
            scanf("%d", &Xi[i]);
        }
    printf("\n");
    sum=0;
    for(i=0; i<10; i++)
    {
        sum = sum + (Xi[i] * Xi[i]);
        
    }
    printf("Sum of sq. of th 10 integer entered = %d", sum);

    return 0;
}
