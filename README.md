Preguntas Abiertas (10)

    JavaScript Básico:
        Describe qué es una función en JavaScript y cómo se declara.
        R// Una función es una pedazo de código que se encarga de ejecutar una tarea en específico y es reutilizable, es decir que la puedo utilizar muchas veces sin necesidad de escribir nuevamente todo el código, sino que solo llamando la función. Una función se declara así utilizamos la palabra reservada "function" y le asiganamos un nombre, seguido de parentesis y corchetes (function myFunction() {};)

    Manipulación del DOM:
        Explica cómo seleccionar un elemento del DOM y cambiar su contenido.
        R// Hay diferentes formas de seleccionar un elemento del DOM como puede ser por el ID, clase y etiqueta, para hacerlo utilizamos document.querySelector('clase(utilizamos punto), ID(utilizamos numeral #), etiqueta(nombre de la etiqueta)');, y para cambiar su contenido tulizamos .innerHTML

    Programación Orientada a Objetos (OOP):
        ¿Qué es una clase en JavaScript y cómo se define una?
        R// Se define con la palabra reservada class y es una buena manera de generar objectos, en la programacòn orientada a objetos. Es parecido a una función, solo que el código es más limpio y no retorna nada.

    Eventos en JavaScript:
        ¿Cómo se agrega un evento de clic a un botón en JavaScript?
        R// Utilizamos seleccionamos el botón con el DOM y agregamos .addEventListener('click') {}

    Variables y Tipos de Datos:
        Explica las diferencias entre var, let, y const en JavaScript.
        R// var = No se utiliza actualmente ya que genera conflictos en el código
        let = nos permite almacenar una variable con información que puede ser cambiante o que esta sujeta a actualizaciones

    Control de Flujo:
        ¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?
        R// Son las que nos permiten establecer condicionales como if, if else y else

    Funciones de Flecha:
        Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.
        R// Una función flecha, es una función que no tiene nombre y se ejecutan en orden a diferencia de las funciones normales, 

    JSON:
        ¿Qué es JSON y cómo se utiliza en JavaScript?
        R// es una herramienta que nos permite almacenar información como una base de datos y simula una API

    Promesas:
        Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.
        R//Una promesa es una código que no es permite esperar a que se ejecute antes de pasar al siguiente paso.

    Depuración:
        ¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?
        R//

Preguntas de Selección Múltiple (20)


    ¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?

    A) var myVariable;
    B) variable myVariable;
    C) let myVariable;
    D) A y C son correctas.

    Respuesta D

    ¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?

    A) push()
    B) pop()
    C) shift()
    D) unshift()

    Respuesta A

    ¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?

    A) ==
    B) ===
    C) !=
    D) !==

    Respuesta B

    ¿Cuál es la salida del siguiente código?

console.log(typeof null);

    A) null
    B) undefined
    C) object
    D) number

    Respuesta A

    ¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?

    A) forEach()
    B) map()
    C) filter()
    D) Todas las anteriores

    Respuesta A

    ¿Qué se entiende por “hoisting” en JavaScript?

    A) Declaraciones de variables y funciones se mueven al principio de su ámbito.
    B) Es un término para describir la eliminación de variables.
    C) Es un método para agrupar varias funciones.
    D) Ninguna de las anteriores.

    Respuesta C

    ¿Cuál es la diferencia entre null y undefined en JavaScript?

    A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado.
    B) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor.
    C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor.
    D) No hay diferencia.

    Respuesta C

    ¿Cuál es el propósito del método Array.prototype.map()?

    A) Modificar el array original.
    B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original.
    C) Filtrar los elementos de un array.
    D) Encontrar un elemento en un array.

    Respuesta B

    ¿Qué es el Event Loop en JavaScript?

    A) Un ciclo que controla las llamadas recursivas.
    B) Un proceso que permite a JavaScript realizar operaciones asincrónicas.
    C) Un método para iterar sobre arrays.
    D) Ninguna de las anteriores.

    Respuesta C

    ¿Cuál es la salida del siguiente código?

    console.log(0.1 + 0.2 === 0.3);

    A) true
    B) false
    C) undefined
    D) NaN

    Respuesta A

¿Qué se entiende por strict mode en JavaScript?

    A) Un modo que permite utilizar características experimentales.
    B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
    C) Un método para validar datos.
    D) Ninguna de las anteriores.

    Respuesta D

¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

    A) let obj = {};
    B) let obj = Object.create();
    C) let obj = new Object();
    D) A y C son correctas.

    Respuesta D

¿Qué es un callback en JavaScript?

    A) Una función que se pasa como argumento a otra función.
    B) Un tipo de variable especial.
    C) Un método para declarar funciones.
    D) Ninguna de las anteriores.

    Respuesta D

¿Cuál es el propósito de async y await en JavaScript?

    A) Ejecutar funciones síncronas.
    B) Manejar operaciones asincrónicas de manera más simple y legible.
    C) Declarar variables globales.
    D) Ninguna de las anteriores.

    Respuesta B

¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

    A) Arrays
    B) Strings
    C) Objetos
    D) Ninguna de las anteriores.

    Respuesta D

¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

    A) JSON.parse()
    B) JSON.stringify()
    C) toString()
    D) parseInt()

    Respuesta B

¿Qué es un Promise en JavaScript?

    A) Una función que se ejecuta inmediatamente.
    B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
    C) Un método para declarar variables.
    D) Ninguna de las anteriores.

    Respuesta D

¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

    A) push()
    B) pop()
    C) shift()
    D) unshift()

    Respuesta C

¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

    A) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
    B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente.
    C) No hay diferencia entre ellos.
    D) Ambos almacenan datos solo durante la sesión del navegador.

    Respuesta B

¿Qué método se utiliza para detener la propagación de un evento en el DOM?

    A) event.stopPropagation()
    B) event.preventDefault()
    C) event.stop()
    D) event.cancel()

    Respuesta C


