# curso-esencial-html-css
https://leonidasesteban.com/aprender/html-css-fundamentos


## CSS

```
.title {
  color: red
}
```

### .title  = selector
### color = propiedad
### red = valor

### N Selectores separados por coma(,)
### N Propiedades separadas por coma(,)

### Selector Basico
  #### Afecta a todos los elementos

### * Global

### Selector Etiqueta
  #### Hacen referencia a todos los elementos HTML que coincidan.

```
h1 {
  color: red
}
```

### Selector Clase .nombreClase
  #### Las clases se pueden repetir y un elemento puede tener mas de una clase

```
.nombreClase {
  color: red
}
```

### Select ID #idComponente

#### Solo un elemento puede tener el mismo id en un página

```
#id {
  color: red
}
```

### Selector atributo []

#### Todos los elementos que contegan el atributo o valor de atributo en cuestion.
```
[id='title' ] {
  color: red
}

<h1 id="title">
  Curso escencial de HTML y CSS
</h1>
```
### Selector Grupo
#### N selectores se pueden configurar con las mismas propiedades

```
#title, .sub-title {
  color: red
}

 <h1 id="title">Hola</h1>
 <h2 class="sub-title">Raul</h2>
 <h3>Castillo</h3>
```

### Selector :PseudoClase
#### Representa estados de un elemento
```
h1:hover {
  color: red
}

<h1>Curso escencial de HTML y CSS</h1>
```

### Selector ::PseudoElemento
#### Crean elementos especiales

```
h1::after {
  content: "-"
}

h1::before {
  content: "-"
}

<h1>Curso escencial de HTML y CSS</h1>
```