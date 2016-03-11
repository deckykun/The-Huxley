#include <stdio.h>

int main(){
	int cod, quant;
	float valor,pagar;
	
	scanf("%d\n%d",&cod,&quant);
	
	switch(cod){
		case 1: valor=5.3; 	break;
		case 2: valor=6.;	break;
		case 3: valor=3.2;	break;
		case 4: valor=2.5;	break;
	}
	pagar= valor*quant;
	
	if(quant>=15 || pagar>=40){
		pagar=pagar - pagar*0.15;
	}
	
	printf("R$ %.2f",pagar);

    return 0;	
}
