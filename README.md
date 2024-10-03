# CARPETA_DE_INFORMATICA_9N0B_VICTOR_JOSE_CHIPANTIZA
Algoritmo juegodedados
	Definir x Como Entero
	x <- 1
	Mientras x<>0 Hacer
		Escribir 'lanzar el dado nuevamente'
		Escribir '1= girar dado'
		Escribir '0=salir'
		Leer x
		Si x==1 O x==0 Entonces
			Si x==1 Entonces
				Escribir 'obtuviste un: ', azar(6)+1
			FinSi
		SiNo
			Escribir 'ingresar una opcion correcta'
		FinSi
	FinMientras
FinAlgoritmo
