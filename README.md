#include <stdio.h>


int main(int argc, char *argv[]){

printf("\tPractico integrador\n\nIntegrantes:\n\tSofia Lazovki\n\tPachado Mauro");


int men;
char menu;

printf("Bienvenido al programa\n");
printf("\t\t\tIngrese la opcion requerida");
printf("\na. Registrar un instrumento.\tb. Listar los instrumentos.");
printf("\nc. Mostrar los instrumentos agrupados por frecuencia de calibración \td. Modificar los datos del  instrumental");
printf("\ne.   Salir.\n...");


scanf("%i",&men);
do
{
   switch (men)
{
case 1:
    printf("Usted  está en la opción .....Registrar un instrumento.");
    break;
case   2:
 
    printf("Usted  está en la opción .....Listar los instrumentos.");
    break;
case   3:

    printf("Usted  está en la opción .....Mostrar los instrumentos agrupados por frecuencia de calibración");
    break;
case   4:
 
    printf("Usted  está en la opción .....Modificar los datos del  instrumental");
    
    break;
case   5:

    printf("Fin del programa");
   
    break;
default:

printf("Opcion Incorrecta");
    break;

}
} while (men=!5);
  return 0;
}

