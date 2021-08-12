Readme

Los archivos del proceso realizado los podrá encontrar en el link 

del GitHub (link), donde encontrara la carpeta con los archivos 

procesados y sin procesar en las carpetas.

Los pasos que se realizaron durante la ejecución del trabajo en OpenRefine son los siguientes:

1. Se cargo el archivo llamado "dataset.xlxs" el cual contenía los datos iniciales.

2. Para la columna "Autores", se realizó la estructura: Apellido, nombre. Esto por medio de los métodos del cluster: Key collision – fingerprint, Key 

collision – metaphone3, Key Collision – Daitch-Mokotoff y Nearest neighbor – ppm.

3. Para la columna de "Lugares de Publicación", se quitaron los caracteres especiales por medio del método de Cluster: (Key collision – fingerprint)

4. Para la columna de "Editorial", se utilizó los siguientes métodos de cluster: Key collision – fingerprint, Key collision – Metaphone3, Key collision – 

Daitch-mokotoff y Nearest neighbor – ppm.

5. Para la columna de "Años de publicación", inicialmente se editó la columna a formato número, luego se aplica los formatos de cluster: (Key collision – 

fingerprint y Key collision – ngram-fingerprint.

6. Luego se descargó el archivo generado en OpenRefine en formato Excel Xslx, que se llamó "DatosProcesados".

7. Para la estructura de archivos, utilizamos dos carpetas. Una, donde se encuentra el archivo dataset.xlxs en la carpeta DatosSinProcesar. Y otra, donde se 

encuentra el archivo ProyectoExamen en la carpeta DatosProcesados. Y finalmente, utilizamos la nomenclatura PascalCase.
