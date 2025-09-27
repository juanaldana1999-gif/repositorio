# repositorio
main
Algoritmo ClasificarConexion
	Definir v Como Entero
	Escribir "Ingrese su velocidad (Mbps) como número entero:"
	Leer v

	Segun v Hacer
		// Valores no válidos
		-999999..-1:
			Escribir "Valor no válido"

		// Clasificaciones
		0..9:
			Escribir "Conexión Lenta"
		10..50:
			Escribir "Conexión Estándar"
		51..100:
			Escribir "Conexión Rápida"
		101..999999:
			Escribir "Conexión Muy Rápida"

		De Otro Modo:
			Escribir "Valor no válido"
	FinSegun
FinAlgoritmo
