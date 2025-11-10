# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: Mateo Emanuel Martin Tec
## Actividad \#16 - Matrices documentación

---
## Ejercicio 1: Identifica el tipo de cada matriz
---

### Matriz A

| 1 | 0 |
|---|---|
| 0 | 1 |

**Tipo de matriz:** Identidad  
**Argumentación:**  
Es una matriz identidad porque todos los elementos de la diagonal principal son 1  
y los demás elementos son 0.

---

### Matriz B

| 3 | 0 | 0 |
|---|---|---|
| 0 | -2 | 0 |
| 0 | 0 | 5 |

**Tipo de matriz:** Diagonal  
**Argumentación:**  
Es una matriz diagonal porque todos los elementos fuera de la diagonal principal son 0  
y sólo la diagonal principal contiene valores distintos de cero.

---

### Matriz C

| 2 | 1 | 4 |
|---|---|---|
| 1 | 3 | 5 |
| 4 | 5 | 6 |

**Tipo de matriz:** Simétrica  
**Argumentación:**  
Es simétrica porque es cuadrada y cumple que cada elemento `aᵢⱼ` es igual a `aⱼᵢ`. Como un espejo 

---

### Matriz D

| 1 | 2 | 3 |
|---|---|---|
| 0 | 4 | 5 |
| 0 | 0 | 6 |

**Tipo de matriz:** Triangular superior  
**Argumentación:**  
Es triangular superior porque todos los elementos que están debajo de la diagonal principal son 0,  
y sólo hay valores distintos de cero en la parte superior de la matriz.

---
## Ejercicio 2: Operaciones básicas

Dadas las matrices:

### Matriz A

| 2 | -1 |
|---|---|
| 3 | 4 |

### Matriz B

| 5 | 2 |
|---|---|
| -1 | 3 |

Se solicitan las siguientes operaciones:  
**A + B**, **2A - B**, **A × B**, **B × A**, y **Aᵗ (A transpuesta)**.

---

### 1. A + B

**Cálculo:**

| (2 + 5) | (-1 + 2) |
|----------|-----------|
| (3 + -1) | (4 + 3) |

**Resultado:**

| 7 | 1 |
|---|---|
| 2 | 7 |

**Argumentación:**  
La suma de matrices se realiza sumando cada elemento correspondiente  
(fila con fila, columna con columna).

---

### 2. 2A - B

**Cálculo intermedio:**
Primero, se multiplica A por 2:

| 4 | -2 |
|---|----|
| 6 | 8 |

Luego se resta B:

| (4 - 5) | (-2 - 2) |
|----------|-----------|
| (6 - -1) | (8 - 3) |

**Resultado:**

| -1 | -4 |
|----|----|
| 7 | 5 |

**Argumentación:**  
Se aplica la multiplicación escalar a A y luego se restan los valores  
de la matriz B elemento por elemento.

---

### 3. A × B

**Cálculo:**

| (2×5 + -1×-1) | (2×2 + -1×3) |
|----------------|---------------|
| (3×5 + 4×-1)   | (3×2 + 4×3)  |

**Resultado:**

| 11 | 1 |
|----|---|
| 11 | 18 |

**Argumentación:**  
El producto de matrices se obtiene multiplicando las filas de A por las columnas de B,  
sumando los productos correspondientes de cada posición.

---

### 4. B × A

**Cálculo:**

| (5×2 + 2×3) | (5×-1 + 2×4) |
|--------------|--------------|
| (-1×2 + 3×3) | (-1×-1 + 3×4) |

**Resultado:**

| 16 | 3 |
|----|---|
| 7 | 13 |

**Argumentación:**  
La multiplicación de matrices **no es conmutativa**,  
por lo tanto **A × B ≠ B × A**.  
Se multiplican las filas de B por las columnas de A siguiendo la misma regla.

---

### 5. Aᵗ (Transpuesta de A)

**Cálculo:**
Se intercambian filas por columnas.

| 2 | 3 |
|---|---|
| -1 | 4 |

**Resultado:**

| 2 | 3 |
|---|---|
| -1 | 4 |

**Argumentación:**  
La transpuesta de una matriz se obtiene al convertir sus filas en columnas  
y sus columnas en filas.

---
# Actividad: Documentación de Matrices

## Ejercicio 3: Multiplicación en cadena

Dadas las siguientes matrices:

### Matriz A

| 1 | 2 |
|---|---|
| 3 | 4 |

### Matriz B

| 2 | 0 |
|---|---|
| 1 | 3 |

### Matriz C

| 1 | 1 |
|---|---|
| 0 | 2 |

Se debe **verificar que (A × B) × C = A × (B × C)**.

---

### Paso 1: Calcular (A × B)

**Cálculo:**

| (1×2 + 2×1) | (1×0 + 2×3) |
|--------------|--------------|
| (3×2 + 4×1)  | (3×0 + 4×3)  |

**Resultado:**

| 4 | 6 |
|---|---|
| 10 | 12 |

---

### Paso 2: Calcular (A × B) × C

**Cálculo:**

| (4×1 + 6×0) | (4×1 + 6×2) |
|--------------|--------------|
| (10×1 + 12×0) | (10×1 + 12×2) |

**Resultado:**

| 4 | 16 |
|---|----|
| 10 | 34 |

---

### Paso 3: Calcular (B × C)

**Cálculo:**

| (2×1 + 0×0) | (2×1 + 0×2) |
|--------------|--------------|
| (1×1 + 3×0)  | (1×1 + 3×2)  |

**Resultado:**

| 2 | 2 |
|---|---|
| 1 | 7 |

---

### Paso 4: Calcular A × (B × C)

**Cálculo:**

| (1×2 + 2×1) | (1×2 + 2×7) |
|--------------|--------------|
| (3×2 + 4×1)  | (3×2 + 4×7)  |

**Resultado:**

| 4 | 16 |
|---|----|
| 10 | 34 |

---

### Verificación final

**(A × B) × C = A × (B × C)**

| 4 | 16 |
|---|----|
| 10 | 34 |

=  

| 4 | 16 |
|---|----|
| 10 | 34 |

**Conclusión:**  
Se cumple que **(A × B) × C = A × (B × C)**,  
---

