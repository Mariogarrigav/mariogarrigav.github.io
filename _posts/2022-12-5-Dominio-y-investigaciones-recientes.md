---
layout: post
title: Resumen clase dominio de aplicaciones e investigaciones recientes
---

## Contexto: Se realiza mencion a algunos de los problemas más relevantes de las RECSYS y sobre los Graph Neural Networks para los modelos de recomendacion.
### Profesor: Denis Parra


### Problemas de las RECSYS.

Es importante siempre tener en cuenta al momento de realizar nuestro recomendador que este puede caer en uno de los principales problemas de los RECSYS, estos son:

* La IA no necesariamente esta recomendado lo que el usuario prefiere, esta esta sesgada y aprende a maximizar una funcion o valor de ganancia que es pre-definida por el programador, esta puede ser pasar tiempo viendo un video, foto, hacer clicks pero no necesariamente es la preferencia de mayor gusto para nuestro usuario, solo es la que maximisa la ganancia definida en base a un valor esperado.
* Es importante ademas siempre mantener un margen de control sobre la IA, es decir, que el usuario pueda ajustar las preferencias o regular el aprendizaje de la IA. Ya sea por un feedback o mostrar diversas recomendaciones es importante que el usuario pueda ajustar esta para ser más personalizada.
* El recomendador puede estar sesgado por los mismos datos de entrenamiento, viniendo estos de un sesgo previo a los datos con los comportamientos de los usuarios, el cual es dificil de lograr regular o percatarse de este.

Existen varios problemas en los cuales se pueden abordar o afectan a los RECSYS provinientes de falta de datos, sobrecarga de informacion, falta de variedad, desde el mismo Bias en los datos o problemas de privacidad. Es una responsabilidad latente que debemos manejar para lograr que nuestro recomendador sea lo más justo y etico posible, sin contener algun sesgo eticamente cuestinable.


### Graph neuronal networks para recomendadores.

Es bastante natural definir un recomendador en base a un sistema de grafo, por lo que este tipo de recomendador es bastante utilizado para lograr modelar relaciones entre las distintas sugerencias que se le realizan al usuario. Un ejemplo bastante aterrizado 


----
****
