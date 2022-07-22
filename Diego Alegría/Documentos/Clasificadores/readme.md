# Clasificadores
En esta investigación se utilizaron modelos de aprendizaje automático debido a que se desea evaluar también, las mejores características para clasificar patrones en las etapas de sueño. Al diseñar con técnicas de aprendizaje automático profundo no se puede acceder a las características puesto que las redes determinan con convoluciones (Si se utiliza un modelo CNN o RNN) de forma automática lo que crean más convenientes llevando esto a una caja negra donde no se puede acceder a entender el comportamiento. 

Se utilizaron dos modelos en esta investigación debido a su naturaleza y los resultados obtenidos en investigaciones similares, son el modelo XGBoost y el modelo de Bosques Aleatorios o Random Forest, para ambos modelos se utilizaron las siguientes características:

- Densidad Espectral de Potencia
- Dimensión Fractal Petrosiana (PFD)
- Dimensión Fractal de Higuchi (HFD)
- Movilidad y Complejidad de Hjorth
- Entropía SVD
- Coeficiente de Información de Fisher
- Análisis de Fluctuación sin Tendencia

En el Jupyter Notebook adjunto en esta carpeta se puede encontrar un detalle paso a paso para replicar el experimento. Se recomienda correrlo sobre la plataforma Google Colab en línea para tener un entorno más controlado.
