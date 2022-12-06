# CSS

## Sintaxis

```css
h1 {
  color: gray;
  font-size: 50px;
}
/* h1: selector */
/* color: propiedad */
/* gray: valor */
/* font-size: propiedad */
/* 50px: valor */
```

## Tipos de selectores

- Selector universal `*`
- Selectores por `element`
- Selectores por `id`
- Selectores por `class`

### Selector global

Sirve para seleccionar todos los elementos HTML.

```css
* {
  box-sizing: border-box;
}
```

### Selector por `element`

Sirve para seleccionar en base a un elemento: `h1, table, etc`

```css
button {
  background-color: red
}
```

### Selector por `id`

Sirve para seleccionar por un `id` especifico: `#btn`

```css
#btn {
  background-color: red
}
```

### Selector por `class`

Sirve para seleccionar por un `class` en especifico: `.buttons`

```css
.buttons {
  background-color: red
}
```
