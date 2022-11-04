# Proyecto_individual 02 - Datathon
![imagen](https://github.com/Karenuzca/Proyecto_individual02/blob/main/henry.png)

## Descripción del Proyecto

El proyecto en desarrollo es usar cierta métrica para medir la performance del modelo, la cual será usada para elegir los mejores modelos en Machine Learning, basado en un mercado inmobiliario en Colombia que esta dentro de la sociedad globalizada e industrializada, donde los precios de los inmuebles han presentado un constante cambio, por lo que quienes deseen invertir o vender una propiedad se enfrentan al fenómeno especulativo existente en la valorización de éstos, debido a la constante tendencia de las ciudades a crecer demográfica y comercialmente, llegando a un punto en donde no se tiene certeza de la valorización real dentro del sector en donde se desee invertir, sin embargo el precio depende en cierta medida de las tendencias que esté teniendo el mercado inmobiliario en un determinado tiempo, el cual así poder estimar adecuadamente el valor de una propiedad es una referencia clave para entender si es una buena oportunidad, ya sea de compra o de venta,con el fin de que implemente un modelo que permita clasificar el precio de las propiedades en venta, utilizando los datos que se han puesto a su disposición correspondientes al año 2020.

Herramienta a utilizar:

- Visual Studio Code (Python)
- Jupyter Notebooks

Librerias en Python:

- Pandas
- Numpy
- Missingno
- Matplotlib
- Seabor
- scikit-learn

## Requisitos

Deben tener el código en un script .py o Jupyter Notebook .ipynb, el cual debe incluir un buen EDA, feature engineerging y, de ser posible, un pipeline de Machine Learning para el procesamiento de datos que consideren necesario. Es importante explicar claramente cada paso realizado mediante comentarios en el script o textos formato markdown dentro del Notebook, pensar que cualquier persona (en este caso serán los Henry Mentors evaluadores) debe entender de la mejor manera posible cada razonamiento y pasos aplicados. Recuerden, además, que deben enviar el repositorio que contenga el proyecto, por lo que es importante que le dediquen tiempo también a esta parte, dejando todo ordenado y con un README acorde, que sirva de introducción al contenido dentro de éste. Por otro lado, es obligatorio que el script genere un archivo .csv sólo con las predicciones, teniendo únicamente una sola columna (sin index) que debe llamarse 'pred' y tenga todos los valores de las predicciones, con un valor por fila. De no llamarse así la única columna, nuestro script de validación NO LO VA A TOMAR y no aparecerán en el dashboard. El nombre del archivo debe ser su usuario de GitHub, si su usuario de GitHub es 'pjr95', el archivo .csv con las predicciones debe llamarse 'pjr95.csv'. Vamos a validar tanto los datos que suban como el código, por lo que seguir estos pasos es fundamental. Cuando entreguen les pedimos que verifiquen que su usuario de GitHub aparezca en el dashboard. En caso de que no aparezca, tal como se comentó más arriba, es debido a que el archivo entregado con las predicciones no cumple con los requisitos solicitados.

## Desarrollo

En el proyecto se tomaron los archivos csv enviados por HENRY para así llevarlos a un proceso de validacion, limpieza y transformación desde la herrramienta de python, haciendo diferentes procesos como hacer una columna nueva categorica donde 0 = casas baratas y 1 = casas caras, tomar las columnas relevantes, eliminar columnas no relevantes, rellenar los valores faltantes con el promedio de cada dataset, hacer una matriz de correlación y finalizando con el entrenamiento de modelo llevado a cabo.

![imagen](https://github.com/Karenuzca/Proyecto_individual02/blob/main/Page-6-Image-18.png)

