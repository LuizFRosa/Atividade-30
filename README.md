# Atividade-30

#include <stdio.h>
#include <string.h>
#include <stdlib.h>
 
int main(){
    char cpf[11]; 
 
    int conv; 
    int i=0;  

    printf("Digite seu CPF\n");
    gets (cpf);  
 
    conv=atoi(cpf); 
                          
   printf("CPF em inteiro: %i\n",conv);
 
system("pause");
}
