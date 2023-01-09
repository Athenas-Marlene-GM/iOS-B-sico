# Operaciones básicas en Swift.
Antes que nada cualquier duda que se tenga respecto al material por favor comentarla a los instructores o también enviar un correo estaría bien, constestaremos tan rápido como podamos 😁.

Para comenzar en Swift existen dos tipos de datos importantes que se tienen que entender desde el principio: **Constantes** y **Variables**, en este lenguaje de programación para declarar una *constante* existe la palabra reservada llamada **let** y en el caso de una *variable* está la palabra reservada **var**. En el caso de **let** no podremos cambiar su valor despuès ya que es una constante, sin embargo, en el caso de *var* sí lo podemos hacer.

Para la impresión de valores en otros lenguajes de programación existe la función llamada: *print(MuestraAlgoEnPantalla)*.

## Cosas básicas del lenguaje.

```swift
// <- Con doble diagonal hacemos comentarios en el texto de una sola linea.
/*
Con diagonal asterico podemos
hacer comentarios usando
mas de una sola
linea de codigo
*/
let holaMundoSwift = "Hola mundo en Swift!"//Para no perder la costumbre.

let miConstante = "Hola soy una constante en forma de texto"

let miVariable = "Hola soy una variable en forma de texto"

print(holaMundoSwift)//En Swift ya no es necesario las llaves en Objetive-C si
print(miConstante)
print(miVariable)
```

Si nos damos cuenta a diferencia de otros lenguajes de programación no tenemos que especificar el tipo de dato que estemos trabajando ya que lo que Swift es *inferencia de dato* ¿No es mágico? 🪄
```swift
//Infiere el tipo de dato.
var numero1 = 10
//Si quieres ser mas especifico

var numero2: Int = 94
``` 
## Tipos de datos 💾

Como en todos los lenguajes de programación me atrevo a decir que tenemos tipos de datos y Swift no es la excepción, dentro de los cuales tenemos:

- **Int** - Enteros
- **Float** - Decimales no tan exactos o precisos, y con menos gasto de memoria.
- **Double** - Decimales con una gran cantidad de precisión pero más gasto de memoria.
- **String** - Cadenas de texto.
- **Bool** - Booleano, que solamente se puede tener valores *true* o *false* o también 0 o 1.
- **Character** - Un caracter.

```swift
let entero:Int = 5
let flotante:Float = 1.5
let double:Float = 3.1415926535897932384626433832795028841971693993751058209749445923078164062862089986280348253421170679

let string:String = "Not In The Mood"// Cancion que andaba escuchando mientras que escrbia esto :v sorry

let booleano:Bool = true
let caracter:Character = "Y"

//Operaciones matemáticas basicas

let primerNumero:Int = 3
let segundoNumero:Int = 5

print(primerNumero + segundoNumero)

4+10
10-4
4*5
4/2
```
Si queremos algo más grande, es decir, una potencia o una raíz cuadrada de un cierto número, se tiene que importar una biblioteca (se verá más adelante) para poder usar esas funciones. 

```swift
import Foundation

pow(3,2)// Función para potencia de un número
sqrt(2) // Función para la raíz de un número

abs(-12) // Funcón para obtner el valor absoluto de un número

max(20,49,102 7902) // Obtener el mayor de los números.

min(2834,209,2) // Obtener el menos de los números.
```

## Arreglos, Sets y Diccionarios 💐 🌾 📕


## Operadores lógicos 🧮

Supongamos que *a* y *b* enunciados lógicos, para hacerlo más fácil, con números, $a = 1$ y $b= 2$.

Los operadores lógicos en Swift sirven para:

**Porder colocar condicionales (tema que se verá después) mediante la siguiente nomenclatura:** 

**NOT:** !a. Quiere decir que es distinto de 1.

**AND:** a && b. Quiere decir que si a *y* b.

**OR:** a||b. Quiere decir que si a *o* b.

Se verá más adelante con ejemplos más claros.

 