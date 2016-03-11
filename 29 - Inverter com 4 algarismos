#include <stdio.h>

int main(){
    int n,num1,num2,num3,num4;
    scanf("%d",&n);

    if(n>=1000 && n<=9999){

        num1=n/1000;
        num2=n/100-num1*10;
        num3=n/10-num1*100-num2*10;
        num4=n-num1*1000-num2*100-num3*10;

        if(num4==0 && num3==0 && num2==0 && num1!=0)
            printf("%d\n",num1);
        else if(num4==0 && num3==0 && num2!=0 && num1!=0)
            printf("%d%d\n",num2,num1);
        else if(num4==0 && num3!=0 && num2!=0 && num1!=0)
            printf("%d%d%d\n",num3,num2,num1);
        else
            printf("%d%d%d%d\n",num4,num3,num2,num1);
    }
    else
        printf("O numero digitado não tem 4 algarismos.\n");

return 0;
}
