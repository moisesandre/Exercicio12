# Exercicio12

#include <stdio.h>
#include <stdlib.h>

int main()

{
    system("color 0b");


    int n, maior, menor, cont=0;
    printf("Digite quantos numeros quiser e digite 0 para encerrar\n\n");

   do
   {
        printf("Digite um valor ");
        scanf("%d",&n);

        cont=cont+1;
        if (maior<n)
        {
           maior=n;
        }
        if (menor>n && n!= 0)
        {
            menor=n;
        }
   }while(n!= 0);

    printf("O maoir e %d\n", maior);
    printf("O menor e %d\n", menor);
    printf("Quantidade de nmrs digitados e %d\n", cont-1);

system("pause");
return 0;
}
