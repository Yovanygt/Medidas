# Conversor de Longitud en c++



#include <iostream>
#include <conio.h>
using namespace std;
int main(void)
 {
 	/* 1 centimetro = 0.01   metros
 	   1 centimetro = 0.0109 yardas
 	   1 centimetro = 0.0119 varas
 	   1 centimetro = 0.3937 pulgadas
 	   1 centimetro = 0.0328 pie */ 
	
	int opcion;		
	double centimetros, metros, yardas, varas, pulgadas, pies;
				cout <<"***************Bienvenidos Conversor de CENTIMETROS*************************"  <<endl <<endl <<endl;
		cout<<"				OPCION 1 Convertir a METROS	" 	<<endl;
		cout<<"				OPCION 2 Convertir a YARDAS" 	<<endl;
		cout<<"				OPCION 3 Convertir a VARAS" 	<<endl;
		cout<<"				OPCION 4 Convertir a PULGADAS" 	<<endl;
		cout<<"				OPCION 5 Convertir a PIES" 		<<endl <<endl <<endl;	 
		cin >> opcion;**
		
		switch (opcion) 
		{
			case 1:
			 		cout<< "					CENTIMETROS A METROS"  										<<endl;
					cout<< "			INGRESE LA CANTIDAD DE CENTIMETROS A CONVERTIR    " 				<<endl;
					cin>> centimetros; 
					metros = centimetros/100;
					cout<<  centimetros <<"    centimetros equivalen a "<<  metros <<"  metros  "			<<endl; 		
			break;
			
			case 2:
					cout<<"						CENTIMETROS A YARDAS"  <<endl;
					cout<<"				INGRESE LA CANTIDAD DE CENTIMETROS A YARDAS A CONVERTIR" 			<<endl;
					cin>> centimetros;
					yardas = centimetros/91.44;
					cout << centimetros  <<"	centimetros equivalen a  " << yardas  <<"	yardas  " 		<<endl;
			break;		
			
			case 3:	
					cout<<"						CENTIMETROS A VARAS"  <<endl;
					cout<<"				INGRESE LA CANTIDAD DE CENTIMETROS A VARAS A CONVERTIR" <<endl;
					cin>> centimetros;
					varas=centimetros/502.92;
					cout << centimetros  <<"	centimetros equivalen a  " << varas  <<"	varas  " 		<<endl;
			break;  
		
			case 4:
					cout<<"						CENTIMETROS A PULGADAS"  <<endl;
					cout<<"				INGRESE LA CANTIDAD DE CENTIMETROS A PULGADAS A CONVERTIR" <<endl;
					cin >>centimetros;
					pulgadas=centimetros/2.54;
					cout << centimetros  <<"	centimetros equivalen a  " << pulgadas  <<"	pulgadas  " 		<<endl;
			break;
			
			case 5:
					cout<<"						CENTIMETROS A PIES"  <<endl;
					cout<<"				INGRESE LA CANTIDAD DE CENTIMETROS A PIES A CONVERTIR" <<endl;
					cin>>centimetros;
					pies=centimetros/30.48;
					cout << centimetros  <<"	centimetros equivalen a  " << pies  <<"	pies  " 		<<endl;
			break;		
		} 
		
		
		
		
		
}

***********************************************************************************************
# Conversor de Longitud en PHYTON
#100    centimetros equivalen a 1 metro
#91.44  centimetros equivalen a 1 yarda
#502.92 centimetros equivalen a 1 vara
#2.54   centimetros equivalen a 1 pulgada
#30.48  centimetros equivalen a 1 pies
opcion= int(input("              Menu          \n" 
"     1.CENTIMETROS A METROS                   \n"
"     2.CENTIMETROS A YARDAS                   \n"                    
"     3.CENTIMETROS A VARAS                    \n"
"     4.CENTIMETROS A PULGDAS                  \n"                  
"     5.CENTIMETROS A PIES                     \n\n"
"*****INGRESA LA OPCION QUE DESEA******        \n"))


if      opcion == 1:
        metros=int(input("INGRESE LA CANTIDAD DE CENTIMETROS A CONVERTIR   "))
        centimetros = metros/100
        print (  metros, "centimetros equivalen a ",centimetros,"metros"  )
        
elif    opcion == 2:
        yarda = float(input("INGRESE LA CANTIDAD DE CENTÍMETROS A CONVERTIR EN YARDAS: "))
        centimetros = yarda/91.44
        print (  yarda, "centimetros equivalen a ",centimetros,"yarda"  )


elif    opcion == 3:
        vara = float(input("INGRESE LA CANTIDAD DE CENTÍMETROS A CONVERTIR EN VARAS: "))
        centimetros = vara/502.92
        print (  vara, "centimetros equivalen a ",centimetros,"varas"  )
        
elif    opcion == 4:
        pulgada = float(input("INGRESE LA CANTIDAD DE CENTÍMETROS A CONVERTIR EN PULGADAS: "))
        centimetros = pulgada/2.54
        print (  pulgada, "centimetros equivalen a ",centimetros,"pulgadas"  )

elif    opcion == 5:
        pie = float(input("INGRESE LA CANTIDAD DE CENTÍMETROS A CONVERTIR EN PULGADAS: "))
        centimetros = pie/30.48
        print (  pie, "centimetros equivalen a ",centimetros,"pie"  )


else:
    print("Opción no válida")

***********************************************************************************************

# Conversor de Longitud en PSEINT
Algoritmo sin_titulo
	Definir opcion, centimetros, metros, yardas, varas, pulgadas, pies Como Real
	
    Escribir "***************Bienvenidos Conversor de CENTIMETROS*************************"
    Escribir ""
	
    Escribir "OPCION 1 Convertir a METROS"
    Escribir "OPCION 2 Convertir a YARDAS"
    Escribir "OPCION 3 Convertir a VARAS"
    Escribir "OPCION 4 Convertir a PULGADAS"
    Escribir "OPCION 5 Convertir a PIES"
    Escribir ""
	
	Leer opcion
	Si opcion = 1 Entonces
        Escribir "CENTIMETROS A METROS"
        Escribir "INGRESE LA CANTIDAD DE CENTIMETROS A CONVERTIR"
        Leer centimetros
        metros = centimetros / 100
        Escribir centimetros, " centimetros equivalen a ", metros, " metros"
	Fin Si
	Si opcion = 2 Entonces
        Escribir "CENTIMETROS A YARDAS"
        Escribir "INGRESE LA CANTIDAD DE CENTIMETROS A YARDAS A CONVERTIR"
        Leer centimetros
        yardas = centimetros / 91.44
        Escribir centimetros, " centimetros equivalen a ", yardas, " yardas"
    FinSi
	
    Si opcion = 3 Entonces
        Escribir "CENTIMETROS A VARAS"
        Escribir "INGRESE LA CANTIDAD DE CENTIMETROS A VARAS A CONVERTIR"
        Leer centimetros
        varas = centimetros / 502.92
        Escribir centimetros, " centimetros equivalen a ", varas, " varas"
    FinSi
	
    Si opcion = 4 Entonces
        Escribir "CENTIMETROS A PULGADAS"
        Escribir "INGRESE LA CANTIDAD DE CENTIMETROS A PULGADAS A CONVERTIR"
        Leer centimetros
        pulgadas = centimetros / 2.54
        Escribir centimetros, " centimetros equivalen a ", pulgadas, " pulgadas"
    FinSi
	
    Si opcion = 5 Entonces
        Escribir "CENTIMETROS A PIES"
        Escribir "INGRESE LA CANTIDAD DE CENTIMETROS A PIES A CONVERTIR"
        Leer centimetros
        pies = centimetros / 30.48
        Escribir centimetros, " centimetros equivalen a ", pies, " pies"
    FinSi
	
FinAlgoritmo
