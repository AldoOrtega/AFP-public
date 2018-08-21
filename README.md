# AFP-public

[Eng] 


The repository contains jupyter Python notebooks of work in progress for the creation of a ranking of clients of a financial entity in Chile, which allows to offer through direct marketing optional products (accounts) to its clients in a personalized and effective way.
Most of the comments are in Spanish.


[Spa] 

El repositorio contiene jupyter notebooks de Python del trabajo en progreso para la creación de un ranking de clientes de una entidad administradora de fondos de pensión de Chile, que permita ofrecer a través de marketing directo productos (cuentas) opcionales a sus clientes de manera personalizada y efectiva.


## Introducción

Las administradoras de fondos de pensiones (AFP) de Chile son instituciones financieras privadas encargadas de administrar los fondos de cuentas individuales de ahorros para pensiones. Una de las tareas más demandantes del área de ventas dentro de dichas entidades, radica en el ofrecimiento de un set de productos adicionales a la cotización previsional legal, a través de marketing directo, a aquellos clientes ya consolidados. Estos productos consisten en cuentas que permiten a los clientes un ahorro previsional adicional y voluntario con distintas características. En particular, la entidad financiera con la cual se está trabajando cuenta con tres productos de contratación voluntaria y la decisión de qué cliente contactar y qué producto ofrecer es tomada basada fundamentalmente en el criterio de cada ejecutivo.

Se propone crear un ranking de usuarios a través de la aplicación de técnicas de minería de datos sobre los perfiles de usuarios de la entidad financiera, con el objetivo de dirigir los esfuerzos del área de ventas de manera personalizada y más efectiva al momento de selección de cliente y producto a ofrecer. La puntuación de cada usuario asociada a cada producto constará de dos partes principales: primero, estimar la probabilidad de que el cliente contrate el producto (asociado a un problema de clasificación binaria) y segundo, estimar el monto de dinero a invertir en dicho producto (asociado a un problema de regresión).

El principal desafío que subyace a la resolución del problema es la gran cantidad de perfiles de usuarios incompletos dentro de la base de datos, dificultando e incluso imposibilitando la aplicación de distintas técnicas de análisis de datos. Otras características  del conjunto de datos que podrían obstaculizar el alcance de los objetivos planteados son la presencia de atributos categóricos con un dominio demasiado grande y el desbalance de las clases.
