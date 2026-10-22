# EvaP2_Spoty
Evaluación Parcial 2, Machine Learning


Fase 1: Definición y Preparación de Datos (Meta: Jueves 22 de Octubre)
Seleccionar el dataset: Elegir preferentemente uno de la EP1 o buscar uno nuevo (sin extensión de plazo). Debe permitir una variable objetivo categórica (clasificación) y una numérica (regresión) lógicas, sin crear objetivos artificiales.

Definir el problema: Plantear 2 preguntas predictivas (clasificación y regresión) y 1 pregunta exploratoria sobre segmentos/anomalías.

Preparar los datos: Documentar el origen, tamaño, variables, calidad y los pasos de limpieza.

Estrategia de validación: Dividir los datos en entrenamiento y prueba, explicando el método y asegurando que no haya fuga de información.

Fase 2: Modelado Supervisado (Meta: En progreso para el 27 de Octubre)
Experimentos de Clasificación:

Implementar 1 modelo principal y evaluar al menos 2 configuraciones de parámetros.

Considerar 1 algoritmo alternativo y explicar por qué se descartó (haya sido ejecutado o no).

Extraer matriz de confusión y métricas (precision, recall, F1 y/o ROC-AUC).

Si el modelo entrega probabilidades, comparar 2 umbrales de decisión.

Experimentos de Regresión:

Implementar 1 modelo principal y evaluar al menos 2 configuraciones de parámetros.

Considerar 1 algoritmo alternativo y explicar por qué se descartó.

Calcular MAE, RMSE y/o R² y redactar su interpretación.

Si corresponde, evaluar métodos de regularización Ridge o Lasso.

Documentar justificaciones: Escribir en Markdown (para cada modelo) los parámetros probados, comparaciones, y por qué ciertas técnicas vistas en clases (como SVM con kernel o árboles) no aplicaron a este caso.

Fase 3: Modelado No Supervisado e Insights (Meta: Martes 27 de Octubre)
Experimentos con DBSCAN (Obligatorio):

Probar un mínimo de 3 combinaciones de eps y min_samples.

Crear una tabla resumen con: parámetros probados, número de clústeres (sin contar ruido) y porcentaje de ruido.

Elegir y justificar una configuración final.

Describir las características de los grupos encontrados y de las observaciones marcadas como ruido.

Otros métodos (Opcional): Si se utiliza K-Means, justificar la elección de la cantidad de clústeres (k) usando el método del codo/inercia o la silueta.

Generar 3 Insights:

Redactar el primer insight mezclando información supervisada/no supervisada. Formato exigido: Hallazgo + Evidencia (gráfico/tabla/métrica) + Interpretación + Recomendación.

Redactar el segundo insight bajo el mismo formato.

Redactar el tercer insight bajo el mismo formato.

Nota: Evitar insights vacíos como "92% de accuracy". Explicar qué significa eso para el problema real.

Fase 4: Consolidación y Entregables (Meta: Jueves 29 de Octubre)
Finalizar el Notebook (.ipynb):

Ordenar estrictamente en 7 secciones: (1) Problema/preguntas, (2) Preparación, (3) Clasificación, (4) Regresión, (5) DBSCAN, (6) 3 Insights, (7) Conclusiones.

Asegurar que todas las justificaciones técnicas estén en celdas de texto Markdown.

Verificar reproducibilidad: Ejecutar desde la primera hasta la última celda sin errores (Kernel > Restart & Run All), usar rutas relativas para el dataset y documentar las dependencias instaladas.

Preparar la Presentación Oral (10 minutos, 7 láminas):

Lámina 1: Dataset, problema y las 3 preguntas.

Lámina 2: Datos, limpieza y estrategia de evaluación (train/test).

Lámina 3: Clasificación (modelos, parámetros, métricas y decisión justificada).

Lámina 4: Regresión (modelos, parámetros, métricas y decisión justificada).

Lámina 5: DBSCAN (las 3 pruebas, grupos resultantes, ruido y análisis).

Lámina 6: Los 3 insights completos con su respectiva evidencia visual e implicancias.

Lámina 7: Conclusiones finales, limitaciones del proyecto y recomendaciones.
