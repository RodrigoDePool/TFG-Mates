## Presentación del TFG de Matemáticas

####Índice:
1. Superficies: Definición, ejemplos compactas vs no compactas, introducir aquí las superficies 'estándar'. Plantear objetivo dividiendo entre las compactas y no compactas
2. Para el estudio de las compactas necesitamos de dos herramientas: la suma conexa y la triangulación. Explicar las dos dando respectivos ejemplos (en especial con toros, suma de dos toros, triangulación de unn toro).
3. Teorema de Tibor Radó y teorema de clasificación de superficies. Explicar alguna parte del teorema.
4.  Hablar de género para probar que las clases son disjuntas (característica de euler e invariancia topológica).
6. Superficies no compactas (insistir en la segundo numerabilidad que nos permite utilizar Radó!). Hablar de las nuevas dificultades que hay
7. Extremos, clases de extremos y borde ideal. Teorema de Kerekjartó. (Idea de la demostración) "como una superficie se escapa hacia infinito"
8. Propiedades de la frontera ideal, conjunto cerrado del conjunto de Cantor. (recordar referencias)
9. Teorema de I. Richards dando un ejemplo concreto para toda posible frontera ideal. (idea de la demostración)
10. Cardinalidad.



####Texto:
- 'Diapo 0.1: Título'
El objetivo de nuestro trabajo fue el estudio del teorema de clasificación de superficies topológicas.

- 'Diapo 1: Definición de superficies'
 Recordamos que las superficies se definen como espacios topológicos, localmente homeomorfos a bolas abiertas  en R^2, que cumplen ser Hausdorff, segundo numerables y conexos.  Durante la presentación expondremos únicamente superficies orientables, pero todos los resultados tienen su análogo con superficies no orientables. El objetivo será  caracterizar topológicamente una superficie.
 
 - 'Diapo 2: Distinción entre superficies compactas y no compactas'
 Como las funciones continuas mantienen la compacidad, podemos tratar por separado el caso de superficies compactas y no compactas.  Aquí tenemos algunos ejemplos canónicos de superficies compactas como el toro o la esfera.
 
 - 'Diapo 2.1: Título de clasificación de superficies compactas'
 Tratemos primero el problema de la clasificación de superficies compactas. Para caracterizar a una superficie compacta primero necesitaremos de dos herramientas: La suma conexa y la triangulación.
 
-  'Diapo 3: La suma conexa'
La suma conexa es una operador entre superficies. La operación consiste en retirar un disco abierto de cada una de las superficies e identificarlas por el borde, como resultado tenemos otro espacio dotado de la topología cociente. Se puede comprobar que sumar dos superficies compactas resulta en otra superficie compacta. Las imagenes que tenemos en las diapositivas sugieren una forma gráfica de entender la suma, en este caso, entre dos toros. 
Recordamos aquí que un toro también se puede representar como un rectángulo plano en el que se identifican sus lados apropiadamente, como pegando los lados de una tira de papel para formar un 'donut'. En esta  representación la suma conexa de dos toros se sigue como indica la imagen, resultando en un octágono con las aristas identificadas como indican los símbolos en la dirección de las flechas. 
La suma conexa ya nos sirve de herramienta para crear un sinfín de superficies.

- 'Diapo 4: La triangulación'
La triangulación de una superficie es una _especie_ de partición de una superficie en conjuntos cerrados, donde cada conjunto es homeomorfo a un triángulo en R^2. Llamaremos un vértice de la superficie a todo punto que se correponda con un vértice de un triángulo en R^2 y de igual manera lo haremos con las aristas. A los conjuntos cerrados, además de recubrir a la superficie, les exigimos que o sean disjuntos o compartan un solo vértice o una sola arista. 

- 'Diapo 5: Ejemplo de triangulación'
La triangulación es una herramienta muy potente que esencialmente nos permite manera una superficie como si de un conjunto de triángulos en R^2 se tratáse. Esencialmente nos permite _teselar_ una superficie por triángulos. En la diapositiva vemos un ejemplo de triangulación de un toro (en su representación plana) y la triangulación de una esfera (donde a cada triángulo en la esfera podríamos deformarlo para formar uno en el plano). 
La triangulación es una herramienta muy potente pero para utilizarla primero es necesario probar que una tal triangulación existe. Este hecho fue demostrado por Tibor Radó, que asegura que toda superficie **separable** es triangulable. Recordamos aquí que en la definición de superficie que dimos exigimos la segunda numerabilidad, por lo que todas las superficies que tratamos son separables y con ello triangulables. Con este par de herramientas ya se puede abordar el teorema de clasificación

- 'Diapo 6: Teorema de clasificación de superficies compactas'
El teorema asegura que toda superficie compacta y orientable es homeomorfa a una esfera o a una suma conexa de _n_ toros.

- 'Diapo X: Cardinalidad'
Recapitulando en la clasificación de superficies compactas dijimos que una superficie es homeomorfa o una esfera o una suma conexa de n toros, lo que nos indica que existen una cantidad numerable de clases topológicas de superficies compactas. Para el caso de superficies no compactas, vimos que podemos crear al menos una superficie no compacta por cada subconjunto cerrado del conjunto de Cantor. Si contamos el número de conjuntos cerrados del conjunto de Cantor no homeomorfos, obtenemos que tenemos un total de alef\_1 clases topológicas de superficies no compactas. Y curiosamente, si en nuestra definición de superficie retiramos la exigencia de 2do numerabilidad, se puede probar que entonces existirán alef\_2 superficies salvo homeomorfismo. 