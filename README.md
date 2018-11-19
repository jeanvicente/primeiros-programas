# primeiros-programas
coisas extras
#include <stdio.h>

int main()
{
    int irmaaltura = 180;
    int paialtura = 180;
    int maealtura = 150;
    int minhaaltura = 170;
    
    int alturatotal;
    alturatotal = irmaaltura * paialtura * maealtura +minhaaltura;
     
    printf("%i\n",alturatotal); 
    return 0;
}

#include <stdio.h>

int main()
{
    int base;
    int altura;
    int area;
    
    printf("digite o valor da base:");
    scanf("%i",&base);
    
    printf("digite o valor da sua altura:");
    scanf("%i", &altura);
    area=base*altura;
    printf("o valor da area do retangulo e´ =%i", area);
    return 0;
}

#include <stdio.h>

int main()
{
    int inteira = 10;
    float decimal =10.50;
    char letra = 'a';
    
    printf("%i\n",inteira);
    printf("%f\n",decimal);
    printf("%c\n", letra);
    
    return 0;
}
#include <stdio.h>

int main()
{
    int numero1=10;
    float numero2=4;
    float resultado= numero1/numero2;
     
     printf("%f\n",resultado);
    return 0;
}
int main()
{   int i=0;
    while(i!=0)
    {
        printf("teste\n");
    }
    do{
        printf("teste 2\n");
    } while (i !=0);
    return 0;
}





