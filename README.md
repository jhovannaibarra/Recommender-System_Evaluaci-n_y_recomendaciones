# Recommender_System_Evaluacion_y_recomendaciones
Recommender System — Evaluación de un sistema de recomendaciones

# Contexto y problema.

El objetivo del proyecto fue evaluar el desempeño de un nuevo sistema de recomendaciones mediante un experimento A/B.

La empresa quería determinar si el nuevo sistema generaba diferencias en el comportamiento de los usuarios a lo largo del proceso de conversión, desde el inicio de sesión hasta la compra.

# Mi contribución.

Realicé la preparación y filtrado de los datos, construí el embudo de conversión y comparé estadísticamente el comportamiento de los grupos de control y experimental.

También me encargué de interpretar los resultados del experimento y determinar en qué etapas del embudo existían diferencias estadísticamente significativas.

# Proceso y decisiones:
* Revisé la distribución de usuarios entre los grupos de prueba.
* Filtré los datos para trabajar con usuarios y eventos que cumplían las condiciones del experimento.
* Consideré únicamente los primeros 14 días del experimento para mantener un periodo de observación comparable.
* Eliminé usuarios que participaban simultáneamente en otros experimentos para reducir posibles interferencias.
* Después del filtrado, trabajé con 1,939 usuarios del grupo A y 655 del grupo B.
* Construí el embudo: Login → Product Page → Product Cart → Purchase
* Comparé las tasas de conversión entre los grupos.
* Utilicé pruebas estadísticas para determinar si las diferencias observadas eran significativas.

# Resultado y aprendizaje

El análisis permitió evaluar estadísticamente el comportamiento de ambos grupos en cada etapa del embudo.

Los resultados mostraron una diferencia estadísticamente significativa entre los grupos en la transición de login a product page, mientras que las diferencias observadas en otras etapas no fueron estadísticamente significativas bajo los criterios establecidos para el análisis.

Este proyecto fortaleció mi experiencia en A/B testing, análisis de embudos de conversión y pruebas estadísticas, así como mi capacidad para interpretar resultados sin asumir que una diferencia observada implica necesariamente un efecto real.

Herramientas: Python · Pandas · NumPy · SciPy · A/B Testing · Statistical Analysis · Z-test
