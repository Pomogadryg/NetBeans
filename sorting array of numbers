#include <stdio.h>
#include <string.h>
#include <stdlib.h>
#include <ctype.h>
#define SIZE 3
void sorting(int *ar,int n);

int main(void) {
    system("COLOR B0");
    
    int numbers[SIZE];
    printf("\nEnter numbers:  \n");
    for(int i=0;i<SIZE;i++)
    {
        scanf("%i",&numbers[i]);
       
    }
    char ch;
    
    printf("\n----------------\n");
    sorting(numbers,SIZE);
    printf("\n----------------\n");
   


    return 0;
}

void sorting(int *ar,int n)
{
    int *temp;
    int buffer[n];
    temp=buffer;
    int top;
    int count;
    
    
    for(int i=0;i<n;i++)
    {
        count=0;
        for(int j=0;j<n;j++)
        {
            if(ar[i]<ar[j]) //here to define ascending or descending
            
                count++;                     
            
        }
        temp[count]=ar[i];
    }
    for(int k=0;k<n;k++)
    {
        printf(" %i ",temp[k]);
    }
}
