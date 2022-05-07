# SmallGraphs

Los siguientes grafos muestran **variabilidad en los coloreos de Greedy con los reordenamientos**.

*Observación obvia: Greedy con un orden dado es determinístico y el "orden natural" también.*

Así que Greedy con el orden natural les debe dar igual que lo que se dice acá.

(Aunque no les pedi una función "OrdenNatural" es algo que deberian poder programar en una linea con las funciones que si estan dadas en el proyecto)

Por otro lado, WelshPowell y los reordenes por bloques de colores no son determísticos según el proyecto (no especificamos cómo se ordenan vertices con el mismo grado o el mismo color) así que les puede dar distinto.

## bxb_15_22_10

> Grafo relativamente chico. Deberia dar más colores con WelshPowell que con otros reordenes (está construido para que WelshPowell ande particularmente mal).

## n=100_m=1470

> queen10.Numero de vertices=100. Numero de lados=1470

Greedy con el orden natural: 16 colores
Greedy con WelshPowell: 17 colores
Con una cantidad moderada de iteraciones baja a 14 y con más iteraciones a 13 e incluso 12. Nunca pude colorearlo con 11 colores.
X(G) es 10 así que no les puede dar menos de eso.

## n=169_m=3328

> queen13

Numero de vertices=169
Numero de lados=3328

Greedy con el orden natural: 21 colores
Greedy con WelshPowell: 23 colores
Se lo puede bajar a 17 con varios reordenes por bloque de colores. X(G)=13.

## n=385_m=19095

> School1 de la pagina de DIMACS

Numero de vertices=385
Numero de lados=19095

Greedy con el orden natural: 42 colores
Greedy con WelshPowell: 34 colores
Haciendo 100 ordenes aletorios baja a 32
Haciendo 426 reordenes por bloque de colores logro bajarlo a 14, pero incluso con 3000 reordenes no parece mejorar.

## n=1010_m=60980

> Numero de vertices=1010. Numero de lados=60980

Greedy con orden natural: 42 colores
Greedy con WelshPowell: 34 colores
Se lo puede bajar a 14 colores.
X(G) >= 11.

## n=3779_m=371357

> Numero de vertices=3779. Numero de lados=371357

Greedy con orden natural: 77 colores
Greedy con WelshPowell: 97 colores
Lo puedo bajar a 72 colores con los reordenes por bloques, pero X(G)=61 así que hay espacio para bajarlo más.
