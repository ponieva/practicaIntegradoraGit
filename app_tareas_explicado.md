#app.js#

	1 Agregar forEach a "listar" (P1)
	tareas.forEach(titulo => {
				console.log(titulo);
			});
			
	2 Agregar "crear" al case	(P2 d II)
		- vble "objeto literal":	(P2 d III)
			titulo = argumento ingresado por consola
			estado = pendiente
		- llamar a guardarTarea
	3 Agregar "filtrar" al case (P3 e I)
		- guardar estado desde la terminal (P3 e II)
		- leerPorEstado con estado de pto anterior (P3 e II)
		- mostrar en consola para cada elemento de un array las tareas filtradas (P3 e IV)
	
		  
#Tareas.js#

	1 leerJSON
		- archivoTareas.leerArchivo()
	2 escribirJSON (P2 a)
		- guardar tareas.json
	3 guardarTarea (P2 c)
		- leer tareas.json en un array usando leerJSON (P2 c I)
		- agregar nueva tarea al array anterior (P2 c II)
		- llamar a escribirJSON (P2 c III)
	4 leerPorEstado (P3 a)
		- leer tareas.json (P3 b)
		- filtrar tareas del estado requerido con filtrarPorEstado (P3 c)
		- nuevo array con tareas filtradas (P3 d)
	5 filtrarPorEstado	
		
		

	
		
		
		
		

	
	
	
		  