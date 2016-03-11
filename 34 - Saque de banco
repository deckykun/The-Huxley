#include <stdio.h>

int main(){
    int X,Y,Z,W,K,quantia;
   
    scanf("%d",&quantia);
    X=Y=Z=W=K=0;
   
    if(quantia<5){
        K=quantia;
        printf("Notas de 50: %d\nNotas de 20: %d\nNotas de 10: %d\nNotas de 5: %d\nNotas de 1: %d\n",X,Y,Z,W,K);
    }
    else if(quantia<10){
        W=quantia/5;
        K=quantia%5;
        printf("Notas de 50: %d\nNotas de 20: %d\nNotas de 10: %d\nNotas de 5: %d\nNotas de 1: %d\n",X,Y,Z,W,K);
    }
    else if(quantia<20){
        Z=quantia/10;
        W=(quantia%10)/5;
        K=(quantia%10)%5;
        printf("Notas de 50: %d\nNotas de 20: %d\nNotas de 10: %d\nNotas de 5: %d\nNotas de 1: %d\n",X,Y,Z,W,K);
    }
    else if(quantia<50){
        Y=quantia/20;
        Z=(quantia%20)/10;
        W=((quantia%20)%10)/5;
        K=((quantia%20)%10)%5;
        printf("Notas de 50: %d\nNotas de 20: %d\nNotas de 10: %d\nNotas de 5: %d\nNotas de 1: %d\n",X,Y,Z,W,K);
    }
    else{
        X=quantia/50;
        Y=(quantia%50)/20;
        Z=((quantia%50)%20)/10;
        W=((quantia%50)%20)%10/5;
        K=((quantia%50)%20)%10%5;
        printf("Notas de 50: %d\nNotas de 20: %d\nNotas de 10: %d\nNotas de 5: %d\nNotas de 1: %d\n",X,Y,Z,W,K);
    }

return 0;
}
