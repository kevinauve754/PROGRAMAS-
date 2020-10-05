# PROGRAMAS-
//Kevin Eduardo González Avendaño
//24/09/2020
#include <stdio.h>

int main(){
    float V;
    int R1,R2,R3;
    float I,I1,I2,I3;

    printf("Escribe el valor del Voltaje: ");
    scanf("%f",&V);

    printf("Escriba el valor de la resistencia 1: ");
    scanf("%d",&R1);
    printf("Escriba el valor de la resistencia 2: ");
    scanf("%d",&R2);
    printf("Escriba el valor de la resistencia 3: ");
    scanf("%d",&R3);

    I1=V/R1;
    I2=V/R2;
    I3=V/R3;
    I=I1+I2+I3;

    printf("La corriente electrica total es %0.2fA\n",I);
    printf("El voltaje en R1  es %0.0fV\n",V);
    printf("El voltaje en R2  es %0.0fV\n",V);
    printf("El voltaje en R3  es %0.0fV\n",V);

return 0;
}
