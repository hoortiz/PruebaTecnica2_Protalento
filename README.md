1. ¿Cuál es el propósito principal de CSS?

El lenguaje CSS se encarga de organizar los objetos  HTML y como estos se visualizaran  en la pantalla de un dispositivo. También define su forma, propiedades y colores de los mismos.


2. ¿Cuál es la diferencia entre margin y padding en CSS?

La diferencia es que margin define el espacio del exterior y el padding define el espacio entre el borde y el contenido 

3. ¿Qué es Bootstrap?

Este es un framework de css qué se utiliza para hacer más sencillo los estilos de muchos objetos de los sitios web qué se desarrolle.

4. ¿Cuál es la etiqueta correcta para enlazar un archivo de hoja de estilos externo en un documento HTML?

<head><linkrel="stylesheet"type="text/css"href="patharchivo.css"></head>

5. ¿Qué es una clase CSS y cómo se selecciona en un documento HTML?

Una clase css es la manera en la que podemos unir propiedades a un objeto html, y la manera de definirlo es mediante la propiedad class.

Ej: <a class="clasehipervinculo"></a>

.class{
Color:green;
}

6. ¿Qué es un diseño web responsivo (responsive design)?

Un diseño responsivo es aquel que le permite  a una página web adaptarse a cualquier tipo de dispositivo y se acomoda al tamaño de la pantalla y sus dimensiones 

7. En tan solo 3 líneas de código en tu css indica cómo harías para posicionar los cuadros rojos justo en medio de un contenedor, como se muestra en la siguiente imágen, (si es necesario crea el index)

.cuadrorojo{
display: flex;   
justify-content: center; 
}

8. Encuentra y corrige los errores

function maxNum (n1, n2){
	 if (n1>n2){
		return n1;
	}
	else{
		return n2;
	}
}

console.log(maxNum(3,7);


function squared (b){
	return b*b;
}

console.log(squared(5);


function menosque100 (a,b){
	let sum = a+b;
	If (sum>=100)
		return false;
	else
		return true;
}

console.log(menosque100(25,100);
console.log(menosque100(35,75);


Javascript

Parte teórica

1. Pregunta: ¿Qué es JavaScript? 

Es un lenguaje de programación utilizado en desarrollo de sitios web para lograr mayor dinamismo en el navegador web.

2. Pregunta: ¿Cuál es la diferencia entre "null" y "undefined" en JavaScript?

la diferencia principal es que cuando alguna variable  está null es que tiene valor definido nulo y exuste y cuando esta undifinded es que no existe del todo.

3. Pregunta: ¿Cómo se declara una variable en JavaScript?

La manera de declarar una variable es mediante la estructura:

var nombredevariable;
var nombredevariable = valor;

let nombredevariable;
let nombredevariable = valor;

const nombredevariable;
const nombredevariable = valor;

4. Pregunta: ¿Qué es una función en JavaScript? 

Una función es una pieza de código que es llamado para cumplir un función especifica que recibe unos parámetros y retorna un resultado después de ser llamada.

5. Pregunta: ¿Cuál es la diferencia entre "==" y "===" en JavaScript? 

La diferencia de los operadores es que el == compara sin necesidad de verificar el tipo de dato y el === realiza una comparación estricta y si hay diferencia en tipo de dato retornará una comparación falsa

6. Pregunta: ¿Qué es el DOM (Document Object Model) en JavaScript?

Es un modelo utilizado para los documentos html qué obliga a respetar las reglas del código para que se puedan manipular como archivos xml. También podemos ver el diseño como una manera de ver en forma de árbol los objetos y mejorar su administración.


Parte Práctica
Ejercicio 3: Desarrolla una función que tome un número entero positivo como parámetro y devuelva el factorial de ese número.

function factorial(numero){
let resultadonumero = 1;
	for(i=1; i<=numero; i++){
		resultadonumero = resultadonumero * i;
	}
return resultadonumero;
}

Ejercicio 4: Escribe una función que tome un array de strings como parámetro y devuelva un nuevo array con las mismas palabras, pero ordenadas alfabéticamente de forma ascendente.

function ordenarstrings(stringaordenar)
{
	const ordenado = stringaordenar.sort(function(a, b){
    if(a.name < b.name) { return -1; }
    if(a.name > b.name) { return 1; }
    return 0;});
    
    return ordenado;
}

¿Qué realiza el siguiente código JavaScript? 

Va a realizar una linea roja dentro del canvas.

¿Cual de las siguientes líneas de código es la correcta en HTML5?


¿Qué haces cuando al ejecutar código tienes un error y no das con la causa? 

Reviso el codigo en el IDE y utilizo el debbuger del navegador para validar que los valores y lo que halla desarrollado este correcta, para asi lograr encontrar donde es que no esta funcionando el codigo.

Ejercicio 1: Convertir el siguiente modelo ER a uno relacional:


Responde las siguientes preguntas:
a) ¿Qué es una clave primaria y cuál es su propósito en una base de datos?

EL proposito de una clave primaria es tener un identificador unico por cada tupla en la tabla.

b)¿Cuál es la diferencia entre una clave primaria y una clave foránea?

La diferencia entre la llave primaria y la llave foranea es que la clave primaria identifica la tupla en la tabla en la que me encuentro y la llave foranea identifica el valor que le corresponde a la columna en otra tabla y debera estar consignada en la otra tabla.

c) ¿Cómo se realiza una consulta SELECT en SQL?

Select columna1,columna2,columna3,etc from tabla where 'condicional';

d)¿Cuál es la diferencia entre una relación uno a uno y una relación uno a muchos en el modelo ER?

La diferencia es que la relacion de la tabla uno con tabla dos de uno a uno es que solo existe una tupla en la tabla uno por cada tupla de la tabla dos, y la relacion uno a muchos es que la tupla de la tabla uno tiene muchos referidos de la tabla dos

e) ¿Qué es la cardinalidad en el contexto de las relaciones en el modelo ER?

Es el sentido en el que los datos tienen precedencia.

f) ¿Cuáles son los 3 lenguajes básicos existentes en el contexto de base de datos, dependiendo de su función?

Lenguaje de control de datos, lenguaje de definición de datos, lenguaje de manipulación de datos, 

