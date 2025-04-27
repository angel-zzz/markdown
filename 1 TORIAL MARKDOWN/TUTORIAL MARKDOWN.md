---
date: 2024/08/27 04:45pm
tags:
  - timeline
  - aangel
---
# Guía básica de la sintaxis de escritura y formato en Markdown.
---
**27/08/2024 - 04:45pm**

### Encabezados

Los encabezados se crean con `#`. Cuantos más `#`, menor es el nivel del encabezado (máximo hasta seis niveles).

```markdown
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
```

# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
---
### Énfasis

**Negrita** y *cursiva* se consiguen con asteriscos (`*`) dos y uno respectivamente o guiones bajos (`_`).

- **Negrita**: envuelve el texto con dos asteriscos o guiones bajos.
- *Cursiva*: envuelve el texto con un solo asterisco o guion bajo.
- ***Negrita y cursiva***: combina tres asteriscos o guiones bajos.

```markdown
**Texto en negrita**
*Texto en cursiva*
***Texto en negrita y cursiva***
```
---
### Listas

#### Listas no ordenadas
Usa `-`, `*`, o `+` para crear listas no ordenadas.

```markdown
- Elemento 1
- Elemento 2
  - Sub-elemento
* Otro elemento
```

- Elemento 1
- Elemento 2
  - Sub-elemento
* Otro elemento
---
#### Listas ordenadas
Las listas ordenadas se crean con números seguidos de un punto.

```markdown
1. Primer elemento
2. Segundo elemento
   1. Sub-elemento
3. Tercer elemento
```
---
### Enlaces

Para crear un enlace, usa la sintaxis `[texto del enlace](URL)`.

```markdown
[Google](https://www.google.com)
```

---
### Imágenes

Para insertar imágenes, usa la misma sintaxis que los enlaces pero añade un `!` antes.

```markdown
![Texto alternativo](URL de la imagen)
```
---
### Citas

Las citas se crean con el símbolo `>`.


> Esto es una cita.

---
### Código

El código en línea se delimita con una comilla invertida simple (\`), y los bloques de código se delimitan con tres comillas invertidas (\`\`\`).

#### Código en línea:

`Esto es un código en línea`
#### Bloque de código:
```markdown
Esto es un bloque de codigo
```
---
### Tablas

Las tablas se crean usando `|` y `-` para definir las columnas y filas.
	para escribir las barras puedes hacerlo con el símbolo alado del numero 1

```markdown
| Encabezado 1 | Encabezado 2 |
| ------------ | ------------ |
| Dato 1       | Dato 2       |
| Dato 3       | Dato 4       |
```

| Encabezado 1 | Encabezado 2 |
| ------------ | ------------ |
| Dato 1       | Dato 2       |
| Dato 3       | Dato 4       |

---
### Divisores

Para crear una línea divisoria, usa tres o más guiones bajos (`_`), guiones (`-`) o asteriscos (`*`).

```markdown
---
```

---
### Listas de tareas

Las listas de tareas se crean usando corchetes `[ ]` o `[x]` para marcar como no completado o completado, respectivamente.

```markdown
- [ ] Tarea pendiente
- [x] Tarea completada
```

- [x] Tarea pendiente
- [ ] Tarea completada
