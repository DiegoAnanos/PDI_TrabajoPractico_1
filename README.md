Sistema de Calificación Automática de Exámenes - TP1
Este proyecto contiene una serie de scripts desarrollados en un entorno de Jupyter Notebook para el procesamiento digital de imágenes de exámenes. El sistema realiza tareas que van desde la mejora de la imagen hasta la detección de marcas y validación de datos del alumno.

Contenido del Proyecto:
El flujo de trabajo se divide en las siguientes etapas principales:

0. Importacion de librerias a usar

1. Ecualización Local de Histograma: Mejora del contraste de las imágenes originales.

2. Correccion Multiple Choice: Filtrado y Segmentación: Aplicación de filtros para reducir ruido y umbralización para binarizar la imagen.

2.A. Preguntas Correctas e Incorrectas: Detección de Grillas y Marcas: Identificación de los cuadros de respuesta y detección de las opciones marcadas (A, B, C, D).

2.B. Validación de Datos de Encabezados: Verificación de campos obligatorios como Nombre, Fecha y Clase.

2.C. Evaluacion de Imagenes: Informe de evaluacion de Examenes

2.D. Alumnos Calificados: Calificación: Generación de un resumen de notas basado en las respuestas detectadas.

Requisitos:
Para ejecutar este código, necesitas tener instalado Python 3 junto con las siguientes librerías:

pip install opencv-python numpy matplotlib pandas

Instrucciones de Ejecución:
Sigue estos pasos para correr el TP correctamente:

1. Preparación de Archivos
Asegúrate de tener el archivo del notebook PI_TrabajoPractico_1.ipynb y las imágenes de los exámenes en el mismo directorio o configurar las rutas dentro del script.

2. Ejecución de Celdas
Abre el notebook y ejecuta las celdas en orden secuencial:

Sección 0: Realiza la importación de las librerías necesarias (cv2, numpy, matplotlib, os, pd).

Secciones 1 a 4: Procesan la imagen y detectan las respuestas.

Sección Final: Muestra visualmente los resultados, imprimiendo el ID del examen y la imagen marcada con las detecciones realizadas.

Visualización de Resultados: Al finalizar la ejecución, el sistema mostrará una cuadrícula de imágenes (usando matplotlib) donde se pueden observar los encabezados calificados y las marcas identificadas en cada examen procesado.
