

[# Pagina para practicar CSS](https://flukeout.github.io/)

https://flukeout.github.io/

[soluciones a los ejercicios y explicacion](https://andersjensen.org/solutions-to-css-diner/)

https://andersjensen.org/solutions-to-css-diner/

por si la pagina fue borrada puedes leeer lo que a continuacion esta 

SOLUCIONES PARA CSS DINER
   CSS Diner es un lugar muy agradable que te permite aprender CSS muy rápido. Simplemente 
   completa los 32 desafíos y asegúrate de comprender la intuición. Si te quedas atascado,
   lee a continuación y nuevamente asegúrate de comprender la intuición.


Generalmente resolvemos/leemos los selectores al revés.

# Nivel 1

### plate

Intuición: para seleccionar todos los elementos de un tipo, simplemente especifique el tipo.

# Nivel 2

## bento

Intuición: para seleccionar todos los elementos de un tipo, simplemente especifique el tipo.

# Nivel 3

## #fancy

Intuición: utilice un selector de ID. Utilice [id=”fancy”] o el acceso directo para id, “#”.

# Nivel 4

### plate apple

Intuición: un selector descendente le permite seleccionar elementos secundarios de otro elemento.

# Nivel 5

### #pepinillo elegante
Intuición: queremos un pepinillo dentro de un padre de id=”plate”. Esta es una combinación de selectores de descendientes e ID.

# Nivel 6

### .small
Intuición: selector de clases. El “.small” nos permite seleccionar todos los elementos con clase=”small”.

# Nivel 7

### orange.small
Intuición: Combinación del Selector de Clases. Elegimos cada naranja con una clase = "pequeña". Recuerde que no necesitamos escribir la clase, simplemente use el "." (punto).

# Nivel 8

### bento orange.small
Intuición: ahora usamos lo que hemos aprendido. Primero queremos un elemento bento con un niño naranja, que contenga la clase "pequeña".

# Nivel 9

### bento, plate
Intuición: combinador de comas. Utilice una coma entre sus selectores para combinarlos.

# Nivel 10

*
Intuición: Utilice el asterisco, “*”, para seleccionar todo.

# Nivel 11

### plate *
Intuición: Combina el selector universal.

# Nivel 12

### plate + apple
Intuición: Podemos usar el Selector de hermanos adyacentes para elegir todas las manzanas al lado de un plato.

# Nivel 13

### bento ~ pickle
Intuición: utilice el selector general de deslizamiento para colocar todos los elementos de pepinillo junto a un bento.

Nivel 14

### plate > apple
Intuición: Usamos el Selector de Niños para elegir la manzana que es hija de un plato.

Nivel 15

orange:first-child
Intuición: para seleccionar el primer hijo de un grupo de niños, utilice el pseudoselector de primer hijo.

Nivel 16

plate > :only-child
Intuición: Aplicar el Pseudo-Selector de Hijo Único, “:only-child”, para asegurarnos de que solo miramos las placas que tienen un hijo. Luego usamos el “plato >” para seleccionar todos los niños a un plato.

Nivel 17

.small:last-child
Intuición: queremos ver solo los elementos del último hijo, por lo que utilizamos el pseudoselector del último hijo, “:last-child”. Los elementos son hijos de la clase "pequeña". Consejo profesional: recuerde que usamos el "." (punto) para la clase.

Nivel 18

:nth-child(3)
Intuición: utilizamos el pseudo-selector de enésimo hijo, “nth-child(3)” y simplemente especificamos que queremos encontrar un elemento, que es el tercer elemento hijo de otro elemento. Si tuviéramos más elementos, con 3 o más hijos, podríamos usar "plate:nth-child(3)".

Nivel 19

bento:nth-last-child(3)
Intuición: Seleccionamos el tercer hijo del final de los elementos con el enésimo último selector de hijos, “:nth-last-child(3)”. Luego decimos que sólo queremos mirar los elementos “bento”.

Nivel 20

apple:first-of-type
Intuición: utilizamos el selector de primero de tipo, selector “:primero de tipo” y luego especificamos que queremos ver manzanas.

Nivel 21

:nth-of-type(even)
Intuición: Usando el selector de tipo enésimo, “:enésimo de tipo (par)”, seleccionamos todos los elementos pares, en nuestro caso las placas son los únicos elementos.

Nivel 22

:nth-of-type(2n+3)
Intuición: queremos seleccionar cada segundo elemento a partir de (e incluyendo) la tercera instancia. Podríamos hacerlo aún más específico si tuviéramos diferentes elementos con "placa: enésima de tipo (2n+3)".

Nivel 23

apple:only-of-type
Intuición: Con el selector Sólo de tipo, “:solo-de-tipo”, seleccionamos el elemento manzana, si es el único de su tipo dentro de su elemento padre. Es posible que desee limitar la selección con "placa de manzana: solo de tipo".

Nivel 24

.small:last-of-type
Intuición: Usando el último selector de tipo encontramos que el último elemento de la clase es pequeño.

Nivel 25

bento:empty
Intuición: Usamos el Selector de vacíos, “:empty” para encontrar todos los bentos vacíos.

Nivel 26

apple:not(.small)
Intuición: Ahora es el momento de la pseudoclase de Negación, “:not”. Aquí seleccionamos todas las manzanas que no pertenecen a la clase "pequeña".

Nivel 27

[for]
Intuición: Aplicamos el selector de Atributos y seleccionamos todos los elementos con un atributo “for=".

Nivel 28

plate[for]
Intuición: Nuevamente usamos el selector de atributos y especificamos que queremos seleccionar todas las placas con un atributo “for=".

Nivel 29

[for="Vitaly"]
Intuición: Para seleccionar la comida de Vitaly aplicamos el Selector de Valor de Atributo y buscamos el valor específico, “Vitaly”.

Nivel 30

[for^="Sa"]
Intuición: aplique el atributo comienza con el selector y especifique los caracteres, "Sa".

Nivel 31

[for$="ato"]
Intuición: similar al nivel 30, podemos usar el selector de atributo termina en y buscar el valor del atributo que termina en “ato”.

Nivel 32

[for*="obb"]
Intuición: aplique el selector comodín de atributo para el atributo for con el valor "obb".

