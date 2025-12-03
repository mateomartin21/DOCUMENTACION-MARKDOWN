# Documentación de Ejercicios - MATEO MARTIN

## Información General
- **Materia:** Fundamentos de Álgebra Lineal
- **Tema:** Cálculo de determinantes
- **Fecha:** 16/11/2025]
- **Estudiante:** MATEO EMANUEL MARTIN TEC
- **Grupo:** 1-A

---

## Objetivo
Documentar y explicar paso a paso el procedimiento para calcular determinantes de matrices y aplicar una propiedad importante: el determinante del producto de matrices.

---

## Ejercicios Realizados

---

### Ejercicio 1 - Determinante de A

**Matriz A:**

| 4 | 5 |
|---|---|
| -3 | 2 |

**Fórmula usada:**  
Determinante de una matriz 2x2:  
a·d − b·c

Valores:
- a = 4
- b = 5
- c = -3
- d = 2

| Operación | Resultado |
|---|---|
| 4 × 2 | 8 |
| 5 × (-3) | -15 |
| 8 − (-15) | **23** |

**Resultado: Det(A) = 23**

---

### Ejercicio 2 - Determinante de B

**Matriz B:**

| 3 | 5 | 7 |
|---|---|---|
| 0 | -3 | 1 |
| 0 | 0 | -9 |

 Observación: Es **matriz triangular superior**  
➡ El determinante es el producto de la diagonal principal

| Elementos de la diagonal | Producto |
|---|---|
| 3, -3, -9 | 3 × -3 × -9 |

Cálculo:
- 3 × (-3) = -9  
- -9 × -9 = **81**

**Resultado: Det(B) = 81**

---

### Ejercicio 3 - Determinante de C

**Matriz C:**

| 8 | 7 | 6 |
|---|---|---|
| 15 | 2 | 3 |
| 2 | 4 | 10 |

Método: **Expansión por cofactores (1ra fila)**

---

Primer menor:

| 2 | 3 |
|---|---|
| 4 | 10 |

| Operación | Resultado |
|---|---|
| 2 × 10 | 20 |
| 3 × 4 | 12 |
| 20 - 12 | 8 |
| 8 × 8 | 64 |

---

Segundo menor:

| 15 | 3 |
|---|---|
| 2 | 10 |

| Operación | Resultado |
|---|---|
| 15 × 10 | 150 |
| 3 × 2 | 6 |
| 150 - 6 | 144 |
| -7 × 144 | -1008 |

---

Tercer menor:

| 15 | 2 |
|---|---|
| 2 | 4 |

| Operación | Resultado |
|---|---|
| 15 × 4 | 60 |
| 2 × 2 | 4 |
| 60 - 4 | 56 |
| 6 × 56 | 336 |

---

**Suma total:**

| Cálculo | Resultado |
|---|---|
| 64 - 1008 + 336 | **-608** |

 **Resultado: Det(C) = -608**

---

### Ejercicio 4 - Determinante del producto B·C

**Propiedad importante:**
> El determinante del producto es el producto de determinantes  
> Det(B·C) = Det(B) × Det(C)

| Determinante | Valor |
|---|---|
| Det(B) | 81 |
| Det(C) | -608 |

| Operación | Resultado |
|---|---|
| 81 × -608 | **-49248** |

**Resultado: Det(B·C) = -49248**

---


