## Programación de la hoja de Excel  
# Tecnológico de Software  
## Materia: Fundamentos de Álgebra  
## Alumno: Mateo Emanuel Martin Tec  
## Actividad #17 - Documentación de Matrices en Excel

---

## Objetivo
El propósito de esta actividad es trabajar con matrices dentro de Excel, representando imágenes mediante números, y aplicar operaciones fundamentales de álgebra lineal como:

- Transposición  
- Suma  
- Resta  
- Multiplicación escalar  
- Composición (multiplicación de matrices)

---

## Programación de la hoja de Excel

### 1. Diseño de las matrices (imágenes pixeladas)
Cada matriz fue creada manualmente en una hoja distinta de Excel, en una cuadrícula de **30 filas por 30 columnas**.  

El usuario puede aplicar **Formato condicional** para colorear cada valor siguiendo esta ruta:

Inicio → Formato condicional → Nueva regla → Formato de celdas que contengan


Asignando un color diferente para cada número.

---

### 2. Transposición de las matrices

Para cada matriz original (ejemplo: en la hoja `Matriz1`), se generó su transpuesta en otra hoja (`Matriz1_T`).

Para transponer una matriz completa se utilizó la función:

```excel
=TRANSPONER(Matriz1!A1:AD30)
```
---

### 3. Suma de matrices

La suma se realizó seleccionando las dos matrices originales (por ejemplo, `Matriz1` y `Matriz2`) con:
```excel
=Matriz1!A1 + Matriz2!A1
```

---

### 4. Resta de matrices

Para calcular la diferencia entre dos matrices:

```excel
=Matriz1!A1 - Matriz2!A1
```

---

### 5. Multiplicación escalar

Para multiplicar una matriz por un número (ejemplo: `3`), en una nueva hoja se usó:

```excel
=Matriz1!A1 * 3
```


---

### 6. Composición de matrices (Multiplicación de matrices)

La multiplicación entre matrices se realizó usando la función:


```excel
=MMULT(Matriz1!A1:AD30, Matriz2!A1:AD30)
```




