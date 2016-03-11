#include <stdio.h>

int main(){
	int max,min,i=1;
	scanf("%d %d",&min,&max);
    
    while(min%5!=0){
        min=min+1;
    }
    while(min<=max && min%5==0){
        if(max-min>=5){
			printf("%d|",min);
	 		min=min+5;
	    }
	 	else{
	 		printf("%d",min);
	 		min=min+5;
	    }
	}
	
	return 0;
}
