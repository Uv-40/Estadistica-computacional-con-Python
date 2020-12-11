<div align="center">
  <h1> Estadistica-computacional-con-Python</h1>
  <p> El contenido de este documento son los apuntes realizados del curso Estadistica computacional con Python dictado por @David Aroesti en @Platzi.</p>
</div>

# Tabla de contenido
- [objetivos](#objetivos)
- [Programación Dinámica](#Programación-Dinámica)
    - [Introducción a la Programación Dinámica](#Introducción-a-la-Programación-Dinámica)
    - [Optimización de Fibonacci](#Optimización-de-Fibonacci)
- [Caminos Aleatorios](#Caminos-Aleatorios)
    - [Entendiendo la aleatoriedad con Python](#entendiendo-la-aleatoriedad-con-python)
    - [¿Qué son los caminos aleatorios?](#¿Qué-son-los-caminos-aleatorios?)
    - [Camino de Borrachos](#Camino-de-Borrachos)
- [Programas Estocásticos](#Programas-Estocásticos)
    - [Introducción a la Programación Estocástica](#Introducción-a-la-Programación-Estocástica)
    - [Cálculo de Probabilidades](#Cálculo-de-Probabilidades)
    - [Simulación de Probabilidades](#Simulación-de-Probabilidades)
    - [Inferencia Estadística](#Inferencia-Estadística)
    - [Media](#Media)
    - [Varianza y Desviación Estándar](#Varianza-y-Desviación-Estándar)
    - [Distribución Normal](#Distribución-Normal)
- [Simulaciones de Montecarlo](#Simulaciones-de-Montecarlo)
    - [¿Qué son las Simulaciones de Montecarlo?](#¿Qué-son-las-Simulaciones-de-Montecarlo?)
    - [Simulación de Barajas](#Simulación-de-Barajas)
    - [Cálculo de PI](#Cálculo-de-PI)
- [Muestreo e Intervalos de Confianza](#Muestreo-e-Intervalos-de-Confianza)
    - [Muestreo](#Muestreo)
    - [Teorema del Límite Central](#Teorema-del-Límite-Central)
- [Datos Experimentales](#Datos-Experimentales)
    - [¿Cómo trabajar con datos experimentales?](#¿Cómo-trabajar-con-datos-experimentales?)
    - [Regresión Lineal](#Regresión-Lineal)


# Objetivos
- Aprender cúando utilizar la programación dinámica y sus beneficios
- Entender la diferencia entre programas deterministas y estocásticos
- Aprender a utilizar la programación estocástica
- Aprender a crear simulaciones computacionales válidas.

# Programación Dinamica

El nombre de programación dinamica no tiene nada que ver con la tecnica de programación utilizada.

La historia inicia en los años 50 con **@Richard Bellman**, el cual necesitaba financiación del gobierno para poder desaroolar sus investigaciones, para lo cual decidio usar un nombre rimbombante a su investigación para que ningun congresista se negara de concederle los recursos.

Según sus propias palabras "el nombre **Programación dinámica** se escogió para esconder a patrocinadores gubernamentales el hecho que en realidad estaba haciendo matemáticas. La frase programacion dinamica es algo que ningún congresista puede oponerse." @Richard Bellman

Lo cierto es que la programación dinamica es una de las técnicas más poderosas para optimizar cierto tipo de problemas.
Los problemas que son **Optimizables** son aquellos que tienen una **subestructura óptima** esto significa que una **solución óptima global** se puede encontrar al combinar soluciones optimas de **subproblemas locales**

**Problemas empalmados** implican resolver el mismo problema en varias ocaciones para dar con la solución óptima.

Con el fin de optener alta velocidad en los problemas de optimización utilizamos la técnica de **Memoization/ Memorización**, la cual evita computos adicionales guardando cómputos previos en diccionarios o estructuras de datos y asi evitar realizarlos nuevamente. Normalmente en esta técnica se usan diccionarios, donde las consutas son eficientes y se pueden hacer en O(1) cambiando rendimiento (tiempo) por memoria (espacio).

# Caminos aleatorios

Los caminos aleatorios son un tipo de simulación que elige aleatoriamente una decisión en cada momento dentro de un conjunto de decisiones válidas existe un término de probabilidad.

Se utiliza en muchos campos del conocimiento cuando los sistemas no son deterministas e incluyen elementos de aleatoriedad.

Movimiento Browniano, con el avance de los microscopios en el siglo XIX, se empezaron a estudiar fenomenos extraños que no se podian explicar con las ciencias del momento. Como el **movimiento del polen en el agua** Albert Einstein logra explicar como los movimientos atomicos son aleatorios y como los atomos del agua golpeaban el polen aleatoriamente.

Los caminos aleatorios tambien son usados para simular el comportamiento del mercado de valores, simulación del movimiento de particulas para simular humo, simulación de la fusión de galaxias en el tiempo, mediante los caminos aleatrios se genero la escultura de nube aleatoria que se encuentra en inglaterra.


## entendiendo la aleatoriedad con python







