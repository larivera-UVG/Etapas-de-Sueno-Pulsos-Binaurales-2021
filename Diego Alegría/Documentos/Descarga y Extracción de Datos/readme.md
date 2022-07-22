# Cambios en versiones anteriores y consideraciones

Originalmente el proyecto fue planteado para que el entrenamiento del clasificador fuera preferiblemente desarrollado con datos recolectados de pacientes pero en esta investigación se plantea la utilización de una base de datos pública sumado a esfuerzos de investigadores de la Universidad del Valle para recolectar datos por las siguientes razones:
 - La utilización de un acercamiento inter-sujetos nos permite captar la varianza que existe entre distintos tipos de individuos y así lograr una precisión en el clasificador que no dependa del sujeto a aplicar el tratamiento.
 - La cantidad de datos necesaria para mejorar un modelo de clasificación es importante, debido a que no se cuenta con los recursos necesarios para armar un conjunto de datos lo suficientemente grande se refuerza la idea de sumar datos públicos a la investigación.
 - Debido a la pandemia del COVID-19 y a las restricciones de movilidad y distanciamiento social es recomendado no exponer a pacientes a clínicas en donde más personas
28 puedan asistir, motivado por priorizar la salud y bienestar de pacientes y el equipo
investigador.

Para esta nueva fase del proyecto se escogió el lenguaje de programación Python en un entorno en línea llamado Google Colab, una plataforma en línea que cuenta con librerías para utilizar modelos ya diseñados, una fuerte comunidad en línea para soporte y herramientas de visualización para poder entender las métricas y resultados.

# Utilización de herramienta

Los archivos de polisomnografías usualmente están en documentos del tipo EDF por lo que se implementó la librería MNE del lenguaje de programación python para poder acceder a los datos y luego poder transformarlos a cuadros de datos de la librería Pandas. Esta herramienta no solo permite la descarga sino también el procesamiento y extracción de las características para el posterior entrenamiento de clasificadores automáticos.

Si se desea correr esta herramienta sobre la plataforma de Google Colab se recomienda descargarlo y montarlo sobre un Jupyter Notebook de Google Colab
