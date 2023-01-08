# machine learning 
## Introdución 
La compañía móvil Megaline no está satisfecha al ver que muchos de sus clientes utilizan planes heredados. Quieren desarrollar un modelo que pueda analizar el comportamiento de los clientes y recomendar uno de los nuevos planes de Megaline: Smart o Ultra.

**Descripción de los datos**

El conjunto de datos contiene los siguientes datos:

- сalls— número de llamadas,
- minutes— duración total de la llamada en minutos,
- messages— número de mensajes de texto,
- mb_used— Tráfico de Internet utilizado en MB,
- is_ultra— plan para el mes actual (Ultra - 1, Smart - 0).

## conclusiones

+ No hay datos ausentes, el objetivo de los datos es la columna is_ultra y las columnas carateristicas son todas menos is_ultra
+ Segmentamos los datos en 3:1:1, eso quiere decir 60% para entrenamiento, 20% para validación y 20% para el modelo de prueba
+ Utilisaremos un modelo de clasificación, ya que el modelo solo tiene que predecir entre 0 y 1
+ Se entrena el modelo con Decision Tree Classifier y tenemos una exactitud de 78.5% con una profundidad de arbol de 3
+ Se entrena el modelo con Random Forest Classifier y tenemos una exactitud de 77.9% con un numero de estimaciones de 50
+ Podemos observar que de los dos modelos de clasificación, con el que mayor exactitud obtuvimos fue el de Decision Tree Classifier, con el que trabajaremos
+ Nuestro modelo tiene una exactitud del 78% de exactitud, con una profundidad de 3, esto quier decir que 8 de cada 10 estan correctas, de igual manera cabe de observar que con el modelo de prueba la exactitud bajo de 78.5% a 77.9%
+ Podemos observar la exactitud del modelo Dummy (68.4%) es menor a la exactitud de nuestro mejor modelo que es 77.9%, nuestro modelo pasa la prueba de cordura
