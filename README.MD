Readme

Los archivos del proceso realizado los podr� encontrar en el link 

del GitHub (link), donde encontrara la carpeta con los archivos 

procesados y sin procesar en las carpetas.

Los pasos que se realizaron durante la ejecuci�n del trabajo en OpenRefine son los siguientes:

1. Se cargo el archivo llamado "dataset.xlxs" el cual conten�a los datos iniciales.

2. Para la columna "Autores", se realiz� la estructura: Apellido, nombre. Esto por medio de los m�todos del cluster: Key collision � fingerprint, Key 

collision � metaphone3, Key Collision � Daitch-Mokotoff y Nearest neighbor � ppm.

3. Para la columna de "Lugares de Publicaci�n", se quitaron los caracteres especiales por medio del m�todo de Cluster: (Key collision � fingerprint)

4. Para la columna de "Editorial", se utiliz� los siguientes m�todos de cluster: Key collision � fingerprint, Key collision � Metaphone3, Key collision � 

Daitch-mokotoff y Nearest neighbor � ppm.

5. Para la columna de "A�os de publicaci�n", inicialmente se edit� la columna a formato n�mero, luego se aplica los formatos de cluster: (Key collision � 

fingerprint y Key collision � ngram-fingerprint.

6. Luego se descarg� el archivo generado en OpenRefine en formato Excel Xslx, que se llam� "DatosProcesados".

7. Para la estructura de archivos, utilizamos dos carpetas. Una, donde se encuentra el archivo dataset.xlxs en la carpeta DatosSinProcesar. Y otra, donde se 

encuentra el archivo ProyectoExamen en la carpeta DatosProcesados. Y finalmente, utilizamos la nomenclatura PascalCase.
