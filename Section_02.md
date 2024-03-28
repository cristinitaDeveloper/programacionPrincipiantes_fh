# Seccion 2 [Volver](README.md)

v1. Algoritmo: Secuencia de pasos ordenada que se realiza buscando solucionar un problema, mostraron el ejemplo de llegar al 20
Variable: espacio en memoria que almacena informacion
Palabra reservada: palabra que es usada en un contexto especifico dependiendo el lenguaje
v5. Sintaxis: Es un error por escribir de manera ilogica o escribir mal el codigo, Camelcase: es la forma en que se escriben las variables, por ej. abcDeFg
v6. console.log(); significa que se esta usando un metodo que mas adelante se hablara de metodos, visual studio es un editor de codigo con extensiones, un ide es diferente porque tiene todo para desarrollar
v7. Se realiza y se explica la configuracion en el archivo package.json, en este se encuentran las devDependencies que son las dependencia para que funcione la aplicacion de manera optima por ej. typescript es una libreria que se usa, tambien hay tenemos algo que se llaman scripts esos scripts se usan para ejecutar el codigo de cierta manera por ej. si quieres ejecutar en tiempo real la aplicacion se ejecuta de cierta manera.

## Ejercicio 1.
1. Abrir chrome en modo incognito, abrir consola
2. Escribir `let numberOfCars = 10;`
3. Escribir `numberOfCars + 1;` y analizar
4. Escribir `numberOfCars;` y analizar lo que pasa
5. Escribir `numberOfCars = numberOfCars + 1;` analizar

## Ejercicio 2.
1. Abrir terminal
2. Escribir `node`
3. Escribir `let numberOfCars = 10;`
4. Escribir numberOfCars = `numberOfCars + 1;`
5. Analizar lo que pasa en cada punto.

## Ejercicio 3. [video y paquete para descargar codigo](https://www.udemy.com/course/programacion-para-principiantes/learn/lecture/33300036#overview)
1. Descargar paquete y descomprimirlo en escritorio
2. Abrir terminal y colocar comando cd y arrastrar carpeta de escritorio a la terminal para luego dar enter
3. Abrir el visual code y arrastrar la carpeta al visual studio y cambiarle el nombre a app.ts a app.js renombrando el archivo
4. Ejecutar node app porque ya node reconoce los archivos js
5. Volver a cambiar el archivo app.js a app.ts
6. Ejecutar node app y ver el error, no estresarse al ver errores es algo que la computadora hace cuando no entiende algo
7. Ejecutar node app.ts
8. Cambiar el archivo y colocar `console.log(10);`
9. Adherir al archivo `console.log('10');`
10. Adherir al archivo `console.log();` y analizar cada cambio

## Ejercicio 4.
1. Ejecutar el comando `npm i`
2. y analizar lo que pasa que directorios son creados
3. Revisar el archivo package.json
4. lanzar el comando npm run dev el cual ejecuta un script creado en el package.json
5. lanzar el comando npm run dev:watch el cual ejecutan un script creado en el package.json pero diferente

## Teoria y Ejercicio 5 Programacion Secuencial
La programacion secuencial consiste en que se ejecuta el codigo en orden de arriba hacia abajo.
En este caso se usan acumuladores de forma que se cambie el valor sin perderlo. ( `a += 1; a = a + 1; a++;` )
1. Abrir archivo app.ts
2. Adherir al inicio la linea `let numbersOfLine = 1;`
3. Editar la linea `console.log( "Linea #", numbersOfLine );` y repetirla 5 veces
4. Ejecutar el codigo
5. y despues de cada `console.log()` colocar codigo para que muestre la linea #1, 2, 3...

## 6 Teoria y Ejercicio Introduccion a Funciones
0. Las funciones se realizan para organizar el codigo que se repite y mejorar la lectura del mismo.
1. Crear funcion `function increaseLine() {}`
2. Dentro del codigo cortar la parte donde se incrementa el acumulador `numberOfLine = numberOfLine + 1`
3. Analizar el codigo y el resultado de la ejecucion
4. Editar el codigo de la funcion y duplicar la linea
5. Analizar el codigo y su resultado
6. Editar el codigo y cambiarla asi `numberOfLine += 2`
7. Analizar el codigo y su resultado

## 7 Teoria y Ejercicio Errores
0. Se muestra modificando let por LET un error, luego se cambia la variable numberOfLines por numberOfLine para ver ciertos errores y explica como se pueden dar tambien errores de logica realizando cambios en la funcion y en los valores.

## 8 Teoria y Ejercicio Evitar repetir codigo
0. Se cambia el nombre a la funcion por `prinLine()`
1. Se cambia el codigo interno de la funcion para que imprima el numero de la linea (Ejercicio hacer que imprima la linea)

## v18 Teoria y Ejercicio creacion de carpeta sections
0. Se termina el ejercicio y se crea la carpeta sections y
1. Se copia el codigo y se pone section-2.ts con el contenido correspondiente usando la palabra `export`.
0. 
