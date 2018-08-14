#include <stdio.h> 
#include <conio.h> 
#include <stdlib.h> 
main() 
{ 
int sueldo[100],hours[100],i,n; 
char name[100][100]; 
printf("Cuantos Trabajadores hay? " ); 
scanf("%d",&n); 
for(i=0;i<n;i++){ 
printf("Como se llama el obrero %d ",i+1); 
scanf("%s",&name[ i ]); 
printf("Cuantas horas trabajo %s ",name[ i ]); 
scanf("%d",&hours[ i ]); 
if(hours[ i ]<=40){ 
sueldo[ i ]=20*hours[ i ]; 
} 
if(hours[ i ]>40){ 
sueldo[ i ]=800+(25*(hours[ i ]-40)); 
} 
} 
system("cls" ); 
printf("Resultados" ); 
printf("Nombre Horas sueldo" ); 
for(i=0;i<n;i++){ 
printf(" %st%2d %2d/n/n",name[ i ],hours[ i ],sueldo[ i ]); 
} 
getch(); 
} 
