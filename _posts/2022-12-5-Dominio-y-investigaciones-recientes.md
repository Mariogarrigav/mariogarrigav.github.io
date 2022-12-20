---
layout: post
title: Resumen clase dominio de aplicaciones e investigaciones recientes
---

## Contexto: Se realiza mencion a algunos de los problemas más relevantes de las RECSYS y sobre los Graph Neural Networks para los modelos de recomendacion.
### Profesor: Denis Parra


### Problemas de las RECSYS.

Es importante siempre tener en cuenta al momento de realizar nuestro recomendador que este puede caer en uno de los principales problemas de los RECSYS, estos son:

* La IA no necesariamente esta recomendado lo que el usuario prefiere, esta esta sesgada y aprende a maximizar una función o valor de ganancia que es pre-definida por el programador, esta puede ser pasar tiempo viendo un video, foto, hacer clicks pero no necesariamente es la preferencia de mayor gusto para nuestro usuario, solo es la que maximiza la ganancia definida en base a un valor esperado.
* Es importante además siempre mantener un margen de control sobre la IA, es decir, que el usuario pueda ajustar las preferencias o regular el aprendizaje de la IA. Ya sea por un feedback o mostrar diversas recomendaciones es importante que el usuario pueda ajustar esta para ser más personalizada.
* El recomendador puede estar sesgado por los mismos datos de entrenamiento, viniendo estos de un sesgo previo a los datos con los comportamientos de los usuarios, el cual es dificil de lograr regular o percatarse de este.

Existen varios problemas en los cuales se pueden abordar o afectan a los RECSYS provenientes de falta de datos, sobrecarga de información, falta de variedad, desde el mismo Bias en los datos o problemas de privacidad. Es una responsabilidad latente que debemos manejar para lograr que nuestro recomendador sea lo más justo y ético posible, sin contener algún sesgo éticamente cuestionable.


### Graph neuronal networks para recomendadores.

Es bastante natural definir un recomendador en base a un sistema de grafo, por lo que este tipo de recomendador es bastante utilizado para lograr modelar relaciones entre las distintas sugerencias que se le realizan al usuario. Un ejemplo bastante aterrizado es spotify que puede generar relaciones entre las canciones recomendadas, géneros o podcast para los usuarios o incluso un recomendador de películas, las relaciones resultan naturales debido a la arquitectura de esta red.

Gracias a la complejidad y alcance de las redes neuronales este tipo de modelos permite generar relaciones entre las recomendaciones más complejas para los usuarios, mezclando más variables de diversas fuentes pero a la vez mas asertivas.

Uno de los mayores desafíos es lograr de forma eficiente definir o modelar la relación entre los datos para generar el grafo correspondiente al problema.

Algunas de las aplicaciones que utilizan este sistema son: Spotify, Steam, Algoritmos de georreferenciación, las redes sociales como facebook o instagram.



----
****
