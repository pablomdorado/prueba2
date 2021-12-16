# Actividad 3 Pablo Martínez Dorado 
Para realizar esta actividad he tenido que escoger el gráfico del volumen de tuits desde abril de 2020 a enero de 2021 publicados por Donal Trump, Mike Pence, Kamala Harris y Joe Biden. Tras llegar al archivo dejado en Github y descargármelo, he abierto Open Refine con el objetivo de separar los datos en columnas y, después, limpiarlos. 

## Pasos previos antes de crear el proyecto

En primer lugar, para separar los datos, he elegido dentro del programa Open Refine varias opciones: 

1. La primera ha sido indicarle al programa que las columnas estaban separadas por comas, de manera que las ordenara adecuadamente. Asimismo, el lenguaje que he puesto es UTF-8 dado que es la codificación que permite todos los caracteres actualmente.

2. Además, le he indicado al programa que no cargue filas en blanco y que seleccione la primera línea para los nombres de la columna. 

3. Por último, también he pinchado en que tampoco cargue celdas en blanco domo nulas y le he dado a crear proyecto. 

## Desarrollo de la actividad 


A continuación, y una vez abierto el archivo, he cambiado los nombres de las columnas a español siendo fecha, nombre y volúmen de tuits los valores indicados. Además, por si acaso le he indicado que nombre me lo tratara como texto, volumen de tuits como número y fecha como fecha mediante el uso del comando de transformaciones comunes.

Con la faceta de texto también he comprobado que ninguno de los nombres está mal escrito o existe incoherencia alguna. Además, mediante la opción ordenar (opción por texto y distinguiendo mayúsculas y minúsculas) le he indicado al programa que me ordenara la columna de fechas por su fecha correspondiente (en ordenar/fechas). Una vez hecho esto, he exportado el proyecto en formato Xls.  

## Elección del gráfico 

Por último, tras abrir el DataWrapper y cargar el archivo en la web con sus correspondientes columnas de nombre, fecha y volumen de tuits. Después de investigar los distintos gráficos, he decidido escoger el de diagrama de dispersión de manera que me indicara no solo el volumen de tuits, sino también su éxito. Dentro de este apartado he seleccionado la fecha como eje horizontal y el volumen de tuits como eje vertical.

Además, en el apartado de color, he personalizado a cada candidato con un color de manera que se viera diferenciado cuál de ellos tenía más éxito. 

En última instancia, le he dado a publicar incluyendo mi nombre y la posibilidad de descargárselo y este es el resultado: 

![Volumen de tuis](img/Actividad3.png)