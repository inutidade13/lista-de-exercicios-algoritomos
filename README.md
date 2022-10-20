# lista-de-exercicios-algoritomos
#include<stdio.h>
#include<math.h>

int main(){
	
	char operador;
	float hipo, cat1, cat2, resultado1, resultadof;
	
	
	printf("algoritimos e programação \n");
	printf("joyce siqueira \n");
	printf("erik daniel silva de souza \n");
	printf("UC277353 \n");
	printf("engenharia de sofware \n");
	printf("dev c++ \n");
	printf("https://github.com/inutidade13/lista-de-exercicios-algoritomos \n");
	printf("digite a atividade que deseja visualizar \n:");
	scanf("%c", &operador);
	
		switch(operador)
			{
			
				case 'a':
							
					printf("digite o valor de A: ");
					scanf("%f", &cat1);
					
					printf("digite o valor de B: ");
					scanf("%f", &cat2);
					
					hipo = pow(cat1,2) + pow(cat2,2);
					resultado1 = sqrt(hipo);
					
					resultadof = cat1 / resultado1;
					
					
					 
					
					 printf("resultado hipotenusa: %f. \n",hipo );
					 printf("resultado seno: %f", resultadof);
					 break;
	}
		
	
	
	
	
	
}
