# proyecto-final-isi

Crsithian Josué Poveda Betanco
Ingeniería en Sistemas 
Grupo #5

# Calculadora

Algoritmo calculadora
	
	continuar <- "si"
	
	Mientras continuar = "si" Hacer
		
		Escribir "Ingrese el primer número"
		Leer n1
		
		Escribir "Ingrese el signo de la operación a realizar (+, -, *, /, %)"
		Leer operacion
		
		Escribir "Ingrese el segundo número"
		Leer n2
		
		Si operacion = "+" Entonces
			resultado <- n1 + n2
			Escribir "El resultado es: ", resultado
		FinSi
		
		Si operacion = "-" Entonces
			resultado <- n1 - n2
			Escribir "El resultado es: ", resultado
		FinSi
		
		Si operacion = "*" Entonces
			resultado <- n1 * n2
			Escribir "El resultado es: ", resultado
		FinSi
		
		Si operacion = "/" Entonces
			Si n2 = 0 Entonces
				Escribir "No se puede dividir entre 0"
			SiNo
				resultado <- n1 / n2
				Escribir "El resultado es: ", resultado
			FinSi
		FinSi
		
		Si operacion = "%" Entonces
			resultado <- (n1 * n2) / 100
			Escribir "El resultado es: ", resultado
		FinSi
		
		Escribir "¿Desea hacer otra operación? (si/no)"
		Leer continuar 
		Si continuar = "no" Entonces
			
		FinSi
		
	FinMientras
	
         FinAlgoritmo
