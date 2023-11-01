# Juego_Dados

1. Objetivo: Modelar con UML y VP, para construir una solución basada en el concepto de relaciones entre clases-

2. Caso Juego de dados y sus consideraciones:

- Se desean modelar los elementos básicos de un dado, que permita solucionar el caso que se plantea a continuación.

- Para simplificar el concepto, consideramos como característica relevante sólo la cara superior de un dado que queda visible al lanzarlo.

- Se requiere que para dicho dado pueda simularse un lanzamiento y obtener un valor entre 1 y 6 de forma aleatoria.

- Considere que para un juego de dados se usan 2 dados. Se lanzan los dados y se calcula la suma de ambas caras superiores, si el resultado de la suma es 7 ganaste!!! sino has perdido!!!...

- Considere que el dado no sabe cómo se suman valores, para lo cual requiere la ayuda de una calculadora que para nuestro caso, al menos sabe cómo retornar la suma de dos cantidades de tipo entero.

- Implemente una prueba unitaria que permita probar su juego de dados y que le permita validar su funcionamiento.

3. Actividades a realizar (30 minutos)

- Identifique TODAS las clases presentes en el dominio problema.
- R: Clase dado, clase calculadora y clase juego de datos que actuara como un main

- Establezca los atributos y métodos para c/CLASE.
- R: Clase dado: Tiene un atributo que sera la cara visible del dado y tiene un metodo que sera el lanzar, que ejecutara el lanzamiento del dado y un getter para obtener su valor, ademas de un constructor para inicializar el objeto en alguna otra clase. En la clase Calculadora, tenemos solo un metodo que hara la suma de ambas caras. y en la clase juegoDeDados solo tenemos un metodo que iniciara el juego.

- Identifique y defina las relaciones entre clases presentes en este caso.
- R: La clase juegoDeDados usa la clase Dado y Calculadora

- Modele el caso usando diagrama de casos UML y VP.
- ![image](https://github.com/GatoMiau03/Juego_Dados/assets/142507343/7d805321-bbe7-4464-af63-d4febd900592)


- Codifique su solución, considerando el número mínimo de clases y test necesarios para su implementación y pruebas mínimas de funcionamiento.

