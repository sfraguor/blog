
# Javascript - Getting Started
### [Aprende javascript con MentoringJS - Pretraining Step 2](http://mentoringjs.com)

Antes de empezar a trabajar con proyectos en Javascript es muy importante tener las bases claras. Para aprender estos conceptos el primer cápitulo del libro Speaking Javascript es un muy buen inicio.

http://speakingjs.com/es5/ch01.html

A continuación he realizado una pequeña síntesis de conceptos, dudas y aclaraciones que me han surgido en el momento de la lectura y que servirán como recordatorio y tabla de consulta rápida por si tenemos dudas más adelante. 

### Conceptos que debemos tener claros en Javascript

Statements

Expressions

Variables

Funciones

Objetos

Métodos

Identifier = Nombres que juegan diversos roles sintácticos. Son sensibles a mayúsculas.

Properties = .Utilizamos el operador (.) para acceder a una propiedad

#### Variables

Las variables en Javascript se definen con la palabra clave **var** pudiéndo dar un valor a esta variable en el momento de crearla:

var test1;
var test1=0;

#### Valores primitivas, Objetos y Propiedades

Es fundamental tener claros estos conceptos. 
Los valores primitivos son los valores más simples que tiene javascript y son los boleanos, los numeros, los strings y el valor null, undefined y symbol(ES6).
Los objetos, son entidades independientes que pueden tener propiedades, y estas propiedades son las que definen al objeto. Es decir, si tenemos un objeto coche, este objeto podrá tener definidas propiedades como: tamaño, color, numero de ruedas, velocidda que alcanza ...
Las propiedades por tanto serán las características asociadas a los objetos y **una vez definidas no pueden ser cambiadas, añadidas o borradas**.

var prueba = 1;
var prueba2 = { 
  nombre: "Prueba de ciencias",
  dificultad: 2,
  numeroPaginas: 3
};

En este caso tenemos la variable prueba que tiene asignado un valor primitivo y el objeto prueba2, tiene las propiedades : nombre, dificultad y numeroPaginas.

### Undefined and null ([ref](http://www.enrique7mc.com/2016/01/diferencia-entre-null-y-undefined-en-javascript/))

Estos valores llamados "nonvalues" son importantes en Javascript y enseguida que empecemos a desarrollar con el lenguaje nos daremos cuenta de que vamos a verlos y utilizarlos muy amenudo. Estos valores pueden dar lugar a confusion y esta confusión puede dar lugar errores lógicos o bugs difíciles de encontrar y por eso es muy importante entender la diferencia.

**Undefined**

Cuando una variable se declara pero todava no tiene valor asignado = undefined, y esto se aplica tambien a los parámetros de una función:

var miVariable; //miVariable tiene un varlor undefined.

function foo(bar) {}
foo(); // El parámetro bar tiene un valor undefined.

Undefined es un tipo de dato y por lo tanto, lo podemos asignar a una variable, sin embargo es preferible que nunca asignemos directamente el valor undifined, ya que cunado nos encontremos con una variable de este tipo no estaremos seguros si fue javascript o nosotros quien le asignamos ese valor, y eso nos puede generar problemas más adelante.

**Null**

Null representa la ausencia de valor intencional, es decir que somos nosotros intencionadamente los que asignamos este valor a una variable cuando no sabemos que valor va a contener.

var test = null;

#### Funciones










