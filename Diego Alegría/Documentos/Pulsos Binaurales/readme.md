# Generación de pulsos binaurales

Para la generación del pulso binaural se utilizó la librería de Python AccelBrainBeat. Utilizando objetos de tipo BinauralBeat se crea el pulso genérico y luego implementando la función nativa de la librería Save Beat se pasan los parámetros deseados como las frecuencias centrales, el tiempo de reproducción y el volumen para el pulso específico.

Al pulso original se añade una pista portadora, esto debido a que durante un período de sueño es de suma importancia considerar la comodidad de una persona para optimizar el descanso. Es por ello que las frecuencias centrales y el volumen del pulso juegan un papel importante pero la reproducción sola de los pulsos puede parecer un poco tediosa por su patrón repetitivo. En esta investigación la solución propuesta fue añadir una pista portadora (pista.wav) al pulso binaural original. Dicha pista posee un contenido frecuencia definido y que al añadir esta pista portadora para modular, esta no añade contenido frecuencial importante al audio aportando solamente la comodidad en el proceso de escucha.

El proceso de modulación y crossfading para añadir transiciones suaves fue realizado gracias a la librería PyDub la cuál permite realizar modificaciones de audio como sumar, recortar y añadir contenido externo.
