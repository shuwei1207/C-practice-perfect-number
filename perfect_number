#include <stdio.h>
#include <stdlib.h>


int main(void) {
	int e=2;
	int i=0;
	int s=0;
	printf("以下是完美數:\n");
	
	do{
		i=1;
		s=0;
		e++;
		do{
			if(e%i==0){
				s+=i;
			}
			i++;
		}
		while(i<e);
		if(s==e){
			printf("%d\n",s);
		}
	}while(e<=10000);
		
	
	
	return 0;
}
