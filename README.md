# Aprendiendo _markdow_

Esto es un parrafo

**Esto es parrafo en negrita**

_Esto es otro parrafo en cursiva_

**_Cursiva y negritas_**

# Encabezado de nivel 1

## Ecabezado de nivel 2

### Encabezado de nivel 3...(hasta 6)

## Enlaces

Los enlaces tienen una estructura de \()[] en donde los coorchetes es el nombre y entre los parentesis el link.

[Youtube](https://youtube.com)

Los hastags de los encabezados puedes usarse como anclas en los links para redirigir al usuario

[Encabezado 1](#aprendiendo-markdow)

## Imagenes

La unica diferencia entre los enlaces y los encabezados son el signo "!"

![Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png)

## Divisiones

Puedes crear divisiones usando 3 giones medios

---

Asi puedo dividir el contenido

## Listas

### Listas ordenadas

La forma mas optima de crear listas ordenadas es simplemente llamar a todos tus elementos como "1." y Markdown en automatico ingresara los valores de los numeros.

1. Invierno
1. Primavera
1. Otoño
1. Verano

### Listas desordenadas

Podemos crear listas desordenads tanto con "\*" como con "-". Si necesitamos sub-items simplemente nos ayudamos de la **identacion**

- Leche
- Cereal
- queso

* Manzana
  - Verde
    - Acida
  - Roja
    - Dulce
* Banana
  - Platano
* Naranja
  - Color
  - Fruta

## Citas

Puedes citar con \>

> Todos los hombres han vivido en tiempos dificiles

### Citar en bloque

Simplemente utilizamos un "\>" en la separacion.

> Si das pescado a un hombre hambriento lo nutres durante una jornada.
>
> Si le enseñas a pescar, le nutrirás toda su vida
>
> Lao Tsé

## Tablas

Creamos tablas usando el caracter "|" para separar cada celda, luego en la segunda linea creamos "|---|" en cada elemento para formar la tabla en si.

| Nombre | Edad | Profesion  |
| ------ | ---- | ---------- |
| Pablo  | 18   | Estudiante |
| Pepito | 22   | Carpintero |
| Mora   | 19   | Artista    |

## Codigo

Cuando queremos hacer mencion de un codigo **en linea** lo implementamos dentro de \` `

Lorem ipsum dolor sit amet consectetur, adipisicing `let` elit.

En cambio, cuando queremos crear un bloque, usamos tripe \``` ```, con el agregado de poder implementar una palabra especial, para hacer referencia de qe lenguaje de programacion hablamos y agregar sus colores(como "js").

```js
function sumar(a, b) {
  return a + b;
}
```

### HTML en Markdown

_Markdown_ tiene soporte para todo lo que sea codio html, como en el siguiente ejemplo:

<form>
<label for="buscador">Buscador:</label>
<input type="search" name="buscador" id="buscador">
</form>

<!-- Esto es un comentario en Marckdown -->

## Escape de caracteres

Para mostar un caracter de codigo de _Markdown_ simplemtente teneos que usar la "\\"
# Gastronomic-Machine
