# Sintaxis Markdown

## Parrafos y saltos de lineas

Para generar un nuevo párrafo en Markdown simplemente separa el texto mediante una   
línea en blanco (pulsando dos veces intro).

Markdown no soporta dobles líneas en blanco, así que si intentas generarlas estas   
se convertirán en una sola al procesarse.

## Encabezados

Las # almohadillas son uno de los métodos utilizados en Markdown para crear encabezados.   
Debes usarlos añadiendo uno por cada nivel.

Es decir,

' # Encabezado 1   
' ## Encabezado 2   
' ### Encabezado 3   
' #### Encabezado 4   
' ##### Encabezado 5   
' ###### Encabezado 6   

Siendo 6 almohadillas(#) el mas pequeño y 1 almohadillas(#) el mas grande.

## Citas

Las citas se generar utilizando el carácter mayor que (>) al comienzo del bloque de   
texto.

Si la cita en cuestión se compone de varios párrafos, deberás añadir el mismo símbolo   
al comienzo de cada uno de ellos.

Ejemplo:

>Todo debe simplificarse lo máximo posible, pero no más. 

## Listas
### Listas Desordenadas
Para crear listas desordenadas utiliza * asteriscos, - guiones, o + símbolo de   
suma.

* Elemento 1
- Elemento 2
+ Elemento 3

Para generar listas anidadas dentro de otras, simplemente tendrás que añadir   
**cuatro espacios en blanco antes del siguiente *, - o +.

* Elemento 1 
    * Sup Elemento 1

### Liatas Ordenadas

Para crear listas ordenadas debes utilizar la sintaxis de tipo:   
«número.» 1.. Al igual que ocurre con las listas desordenadas,   
también podrás anidarlas o combinarlas.

1. Elemento de lista 1
2.  Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        1. Elemento de lista 5
        2. Elemento de lista 6

## Códigos de bloque

Si quieres crear un bloque entero que contenga código. Lo único que tienes   
que hacer es encerrar dicho párrafo entre dos líneas formadas por tres ~ virgulillas.

~~~
Creando códigos de bloque.
Puedes añadir tantas líneas y párrafos como quieras.  
~~~

## Énfasis (negritas y cursivas)

Simplemente tendrás que envolver palabras o textos en éstos símbolos   
para conseguir cursivas o negritas.

*Cursivas*   
**Negritas**

Para utilizar los dos tipos de énfasis no tienes más que combinar la  
sintaxis, envolviendo la palabra entre tres asteriscos    
o tres guiones bajos.

***Convinacion***

## Links o enlaces

Añadir enlaces a una publicación, más que común, hoy en día es algo casi obligatorio.   
Con Markdown tendrás varias formas de hacerlo.

### Links o enlaces en línea

Se crean escribiendo la palabra o texto enlazada entre [] corchetes,   
y el link en cuestión entre () paréntesis.

link de prueba [GITHUB](https://github.com/MilkoDK?tab=repositories)

### Links o enlaces como referencia

EL texto enlazarás palabras o códigos concretos (formados por letras y/o números),   
que en otro lugar más apartado de tu documento tendrás definidos como determinadas URL.

Presento e link de mi [cuenta][github] para tenerlo como ejemplo   
en mi presentacion del Markdown, que tambien estara en mi [github][github].

[github]: https://github.com/MilkoDK?tab=repositories

### Links automaticos 

Estos son necesarios cuando lo que quieres es mostrar una URL completa, y no   
un enlace enmascarado bajo una palabra o frase como ocurre con los links en línea.

Para generar links automáticos tan solo tendrás que rodearlos con los símbolos < >

<https://github.com/MilkoDK?tab=repositories>

## Codigo 

### Código puro 

La forma más sencilla de escribir código en Markdown es envolver el texto entre dos   
comillas sencillas `.

` Esto seria una linea de codigo `

### Texto preformateado

La otra manera de añadir código en Markdown es comenzar el párrafo con cuatro   
espacios en blanco.

    Esto seria una linea de codigo

## Imágenes

Solo que en este caso, deberás añadir un símbolo de ! exclamación al principio y   
el enlace no será otro que la ubicación de la imagen.

![Imagen de muestra](Escritorio\1.jpg)

