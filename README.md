# Clasificación de Planes Megaline

Proyecto de clasificación de clientes para recomendar planes de telefonía en Megaline utilizando Machine Learning.

Introducción al Proyecto La compañía móvil Megaline está enfocada en optimizar su oferta de planes debido a la insatisfacción causada por el uso de planes heredados por parte de muchos clientes. Este proyecto busca ajustar los planes para garantizar la satisfacción del usuario, mejorar la retención de clientes y maximizar los ingresos.

Objetivo del Proyecto Desarrollar un modelo de clasificación para recomendar el plan más adecuado, ya sea Smart o Ultra, basado en el comportamiento de los clientes de Megaline. Este modelo permitirá a la empresa tomar decisiones informadas para optimizar su oferta de planes.

Datos Utilizados El conjunto de datos incluye información sobre:

Número de llamadas realizadas por el cliente (calls).
Duración total de las llamadas en minutos (minutes).
Número de mensajes enviados (messages).
Uso total de datos móviles en MB (mb_used).
Plan actual del cliente (etiquetado como 0 para Smart y 1 para Ultra).
Tecnologías Utilizadas

Python: Lenguaje principal de programación.
Pandas: Manipulación y análisis de datos.
NumPy: Operaciones matemáticas y estadísticas.
Scikit-learn: Implementación de modelos de Machine Learning.
Matplotlib: Visualización de datos.
Seaborn: Complemento para la generación de gráficos.
Instrucciones para Reproducir el Proyecto

Clonar este repositorio:
bash
Copiar
Editar
git clone https://github.com/jose-alberto-hurtado/Clasificacion-Planes-Megaline.git
Instalar las dependencias necesarias:
bash
Copiar
Editar
pip install pandas numpy scikit-learn matplotlib seaborn
Abrir el archivo Jupyter Notebook:
bash
Copiar
Editar
jupyter notebook Clasificacion_Planes_Megaline.ipynb
Seguir las celdas en el orden indicado para reproducir el análisis y la clasificación.
Resultados del Modelo El modelo Random Forest alcanzó los siguientes resultados:

Precisión en el conjunto de validación: 77.85%.
Precisión en el conjunto de prueba: 82.78%.
Conclusión El modelo Random Forest permite identificar el plan más adecuado para cada cliente de Megaline, superando el umbral de precisión establecido por la empresa (75%). Se concluye que el uso de datos móviles es el factor más relevante para determinar la elección entre los planes Ultra y Smart.

Contacto José Alberto Hurtado Echeverría
Correo: josealberto1829@gmail.com
LinkedIn: linkedin.com/in/josé-alberto-hurtado-echeverría-77910a319/
