#include <stdio.h>

int main()
{
    

    int nota1, nota2, nota3, nota4, media;
    printf("digite a nota 1 do aluno: ");
    scanf("%i",&nota1);
    
    printf("digite a nota 2 do aluno: ");
    scanf("%i",&nota2);
    
    printf("digite a nota 3 do aluno: ");
    scanf("%i",&nota3);
    
    printf("digite a nota 4 do aluno: ");
    scanf("%i",&nota4);
    
    media = (nota1 + nota2 + nota3 + nota4) / 2;
    
    printf("media do aluno = %i\n", media);
    
}
