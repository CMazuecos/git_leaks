# Buscador de leaks en commits de github
Creamos un buscador de leaks en commits de github con un formato ETL (código comentado en el programa), extraemos los datos, los modificamos y acabamos cargándolos en un archivo csv.
Para ello, lo primero que hacemos es descomprimir todo el zip en una misma carpeta.
Posteriormente, instalamos requirements.txt escribiendo en la terminal 'pip install -r requirements.txt'.
A continuación ejecutaremos el programa.
- En extract se obtienen los commits del repositorio.
- En la función transform se transforman los commits y se añaden a una lista de commits, buscando en cada commit las palabras clave.
- Finalmente, se muestra por pantalla el resultado y se escribe en un csv la lista de commits.
- También tenemos una función que controla el exit del programa cuando se hace Ctrl + C
