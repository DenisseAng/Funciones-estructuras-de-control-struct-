#include <stdio.h>
#include <stdlib.h>

void agregar();
void mostrar();
void buscar ();

int reg;
int i, numero=0;
    struct datos
    {
       char nombre[60];
       int edad;
       char ciudad[20];
     }persona[20];
     
   int main()
   {
       
       int opcion;
       do{
           system("clear");
           printf("¿Qué desea hacer?" \n");
           printf("\t 1.- Agregar un Registro \n");
           printf("\t 2.- Mostrar los Registros \n");
           printf("\t 3.- Buscar un Registro \n");
           printf("\t 4.- Salir... \n");
           scanf("%d", & opcion);
           system("clear");
           
-- INSERTAR --
}
}
while(opcion<10);
}
void agregar(){
    puts("¿Cúantos registros deseas?:");
    scanf("%d", &reg);
    getchar();
     
     for (i=0; i<reg; i++)
{
       puts("Nombre:");
           fflush(stdin);
           fgets(persona[i].nombre, 60 , stdin);
           puts("Edad");
           scanf("%d", &persona[i].edad);
           getchar();
           puts("Ciudad");
           fflush(stdin);
           fgets(persona[i].ciudad, 20 , stdin);
           puts("----------------");
}
          return;
}
void mostrar(){
   for (i=0; i<reg; i++)
{
printf("Registro:%d\n\tNombre:%s\tEdad:%d\n\tCiudad:%s",i+1, persona[i].nombre, persona[i].edad, persona[i].ciudad);
getchar();
}
return;
}
void buscar(){
printf("¿Qué registro desea buscar?");
scanf("%d", & i);
printf("Registro:%d\n\tNombre:%s\tEdad:%d\n\tCiudad:%s", i, persona[i-1].nombre, persona[i-1].edad, persona[i-1].ciudad);
getchar();
return;
}
