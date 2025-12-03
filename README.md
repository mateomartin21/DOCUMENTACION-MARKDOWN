-----

##  Programación de la hoja de Excel

# Tecnológico de Software

## Materia: Fundamentos de Álgebra

## Alumno: Mateo Emanuel Martin Tec

## Actividad \#17 - Documentación de Matrices en Excel

-----

##  Objetivo

El propósito de esta actividad es trabajar con matrices dentro de Excel, representando imágenes mediante números, y aplicar operaciones fundamentales de álgebra lineal como:

  * **Transposición**
  * **Suma**
  * **Resta**
  * **Multiplicación escalar**
  * **Composición** (multiplicación de matrices)

-----

##  Programación de la hoja de Excel

### 1\. Diseño de las matrices (imágenes pixeladas)

Cada matriz fue creada manualmente en una hoja distinta de Excel, en una cuadrícula de **30 filas por 30 columnas**.

El usuario puede aplicar **Formato condicional** para colorear cada valor siguiendo esta ruta:

> Inicio → Formato condicional → Nueva regla → Formato de celdas que contengan

Asignando un color diferente para cada número.

#### Matriz 1 ($30 \times 30$)

<img width="722" height="360" alt="image" src="https://github.com/user-attachments/assets/8eabf0ca-5410-4de9-9940-bb36b6723b3a" />


### 2\. Transposición de las matrices

Para cada matriz original, se generó su transpuesta.

Para transponer una matriz completa se utilizó la función:

```excel
=TRANSPONER(Matriz1!A1:AD30)
```

#### Matriz 1 Transpuesta ($30 \times 30$)


<img width="721" height="356" alt="image" src="https://github.com/user-attachments/assets/f979f6e4-a06d-492f-9797-18070fa188f5" />


-----

### 3\. Suma de matrices

La suma se realizó seleccionando las dos matrices originales (`Matriz1` y `Matriz2`).

```excel
=Matriz1!A1 + Matriz2!A1
```

#### Suma ($30 \times 30$) - Matriz 1 + Matriz 2

<img width="750" height="360" alt="image" src="https://github.com/user-attachments/assets/0c7f5c83-07fd-4484-9933-8951255f99ec" />

-----

### 4\. Resta de matrices

Para calcular la diferencia entre dos matrices:

```excel
=Matriz1!A1 - Matriz2!A1
```

#### Resta ($30 \times 30$) - Matriz 1 - Matriz 2

<img width="1680" height="474" alt="image" src="https://github.com/user-attachments/assets/c5790bc9-41b1-47b5-8133-7ab9060d71b8" />

-----

### 5\. Multiplicación escalar

Para multiplicar una matriz por un número (ejemplo: `2`), en una nueva hoja se usó:

```excel
=Matriz1!A1 * 2
```

#### Multiplicación Escalar ($30 \times 30$) - Matriz 1 $\times 2$
<img width="570" height="388" alt="image" src="https://github.com/user-attachments/assets/e390d435-07a0-4245-9b29-73a3ba81d876" />


-----

### 6\. Composición de matrices (Multiplicación de matrices)

La multiplicación entre matrices se realizó usando la función:

```excel
=MMULT(Matriz1!A1:AD30, Matriz2!A1:AD30)
```

#### Composición ($30 \times 30$) - Matriz 1 $\times$ Matriz 2
<img width="751" height="538" alt="image" src="https://github.com/user-attachments/assets/069f7721-ba49-4724-ae1c-84d3c620e6b7" />

