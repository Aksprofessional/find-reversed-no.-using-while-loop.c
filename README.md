# find-reversed-no.-using-while-loop.c
no. input from the user and then finding the reverse of no.

#include <stdio.h>

int main() {
    // Write C code here
    int n,r;
    printf("enter the no.=\n");
    scanf("%d",&n);
    while(1){
    r=n%10;
    printf("%d",r);
    n=n/10;
    if(n==0)
     break;
    }
    printf(" is the reversed no.");
    return 0;
}
