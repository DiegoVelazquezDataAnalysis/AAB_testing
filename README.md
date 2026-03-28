# Pruebas AAB en analisis de embudos
![Static Badge](https://img.shields.io/badge/-Python-%233776AB?logo=python&logoColor=white)

## Objetivo del proyecto
Primeramente, se estudia el embudo de ventas. Se requiere saber cómo los usuarios llegan a la etapa de compra
* ¿Cuántos usuarios realmente llegan a esta etapa?
* ¿Cuántos se atascan en etapas anteriores?
* ¿Qué etapas en particular?

Posteriormente, se realizarán pruebas A/A/B. El equipo de diseño pretende cambiar las fuentes de toda la aplicación; se decide poner a prueba un test A/A/B para tomar una decisión basada en los resultados de la prueba.

## Metodologia
1. Cargar dataset
2. Data Cleaning (Preparación): Remover errores, inconsistencias, duplicados, procesar datos faltantes.
3. Análisis exploratorio de los datos (EDA): Realizar un análisis preliminar del comportamiento de los usuarios a lo largo del proceso de compra
4. Modelado de datos e interpretación: Aplicar pruebas estadísticas (SciPy) para extraer información útil.
5. Visualización (Matplotlib) y reportar

## Descripción de los datos
Los usuarios se dividen en tres grupos: dos grupos de control con acceso a las fuentes antiguas y un grupo de prueba, que aprecia las fuentes nuevas.
Cada entrada de registro es una acción de usuario o un evento
* EventName: nombre del evento
* DeviceIDHash: identificador de usuario univoco
* EventTimestamp: hora del evento
* ExpId: número de experimento. 246 y 247 son los grupos de control, y 248 es el grupo de prueba.
