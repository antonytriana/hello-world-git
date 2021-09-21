# Version del curso
Version actual: v1.2.1

# Cabeceras
# Cabecera h1
## Cabecera h2
### Cabecera h3
#### Cabecera h4
##### Cabecera h5
###### Cabecera h6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- formato *italica* en primera forma.
- formato _italica_ en segunda forma.
- formato **bold o strong** en primera forma.
- formato __bold o strong__ en segunda forma.
- formato ~~tachado~~, formato normal.
- Combinacion: *italica*, **bold o strong**, ~~tachado~~.

# Listas
1. Item 1
2. Item 2
3. Item 3
- Item lista desordenada
- Item lista desordenada
- Item lista desordenada

# Links
- [Link en Markdown](http://www.google.com)
- [Link en index.html](index.html)

# Imagenes
![Logo Github](https://logos-marcas.com/wp-content/uploads/2020/11/GitHub-Logo.png)

# Code Snippets
Codigo en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Codigo en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxim  | Burgos   | 123456    |
| Tomas  | Tompson  | 123456    |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
> Esto es una cita.

# Lineas divisoras
Esto es un texto que será dividido por guiones.

---
Esto es otro texto dividido por asteriscos.

***

Esto es otro texto dividido por guiones bajo.

___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.