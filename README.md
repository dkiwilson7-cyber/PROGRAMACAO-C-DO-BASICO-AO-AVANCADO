#include <stdio.h>
#include <stdlib.h>

int main()
{
    int idade;

    printf("Digite a sua idade: \n");
    scanf("%d", &idade);

    if(idade <= 0)
    {
        printf("Idade invalida! Digite um valor positivo. \n");
    }
    else if(idade > 0 && idade < 18)
    {
        printf("Voce eh de menor.\n");
    }
    else if(idade >= 18 && idade < 60)
    {
        printf("Voce eh adulto.\n");
    }
    else
    {
        printf("Voce eh idoso.\n");
    }

    system("pause");
    return 0;
}
