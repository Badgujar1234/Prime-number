
//Prime number
#include<stdio.h>
int main(){
    int n,i,flag=0;
    printf("Enter the number:");
    scanf("%d",&n);

    for(i=2;i<=n-1;i++){
        if(n%i==0){
            flag=1;
            printf("Not Prime");
            break;
        }
    }
    if(flag==0)
        printf("Number is prime");
    return 0;
