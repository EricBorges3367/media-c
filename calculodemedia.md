#include <iostream>

int main(int argc, char** argv) {
	float n1,n2,n3,n4,soma,media;
	
	
	printf("Bem vindo ao sistema de calculo de medias \n");
	printf("Digite nota 1: \n");
	scanf("%f", &n1);
	printf("Digite nota 2: \n");
	scanf("%f", &n2);
	printf("Digite nota 3: \n");
	scanf("%f", &n3);
	printf("Digite nota 4: \n");
	scanf("%f", &n4);
	media = (n1+n2+n3+n4)/4;
	printf("Media final : %2.1f\n ", media);
	
	if (media >= 7){
	printf("Aluno Aprovado , Parabens ");
	}
	else {
	printf("Aluno Reprovado ");
	}


​	
	return 0;

}