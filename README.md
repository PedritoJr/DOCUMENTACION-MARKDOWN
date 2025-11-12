# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: Pedro Alfredo Cardeña Quijano
## Actividad \#16 - documentación de Matrices 

---
### Identificación de matrices

# Ejercicio 1: Clasificar matrices
  ### Identifica el tipo de cada matriz:
  
  La matriz $A$ es una matriz cuadrada de 2x2. *Matriz identidad*
  
  $$ A =
  \begin{pmatrix}
  1 & 0 \\
  0 & 1 \\
  \end{pmatrix}
  $$
  
  
  La matriz $B$ es una matriz cuadrada de 3x3.
  
  
  $$ B =
  \begin{pmatrix}
  3 & 0 & 0 \\
  0 & -2 & 0 \\
  0 & 0 & 5 \\
  \end{pmatrix}
  $$
  
  La matriz $C$ es una *Matriz cuadrada* 
  
  $$ C =
  \begin{pmatrix}
  2 & 1 & 4 \\
  1 & 3 & 5 \\
  4 & 5 & 6 \\
  \end{pmatrix}
  $$
  
  La matriz $D$ es una matriz cuadrada de 3x3. Esta es una *Matriz triangular superior*,
  
  $$ D =
  \begin{pmatrix}
  1 & 2 & 3 \\
  0 & 4 & 5 \\
  0 & 0 & 6 \\
  \end{pmatrix}
  $$


# Ejercicio 2: Operaciones Básicas
  ### Dadas las siguientes Matrices: 
  
  
  
  $$
  A =
  \begin{pmatrix}
  2 & -1 \\
  3 & 4
  \end{pmatrix}
  $$
  $$ 
  B =
  \begin{pmatrix}
  5 & 2 \\
  -1 & 3
  \end{pmatrix}
  $$
  
  ### Suma de A + B
  
  $$
  A + B =
  \begin{pmatrix}
  2 & -1 \\
  3 & 4
  \end{pmatrix}
  +
  \begin{pmatrix}
  5 & 2 \\
  -1 & 3
  \end{pmatrix}
  $$
  
  $$
  A + B =
  \begin{pmatrix}
  2 + 5 & -1 + 2 \\
  3 + (-1) & 4 + 3
  \end{pmatrix}
  $$
  
  $$
  A + B =
  \begin{pmatrix}
  7 & 1 \\
  2 & 7
  \end{pmatrix}
  $$
  
  
  ### 2A - B
  
  $$
  2A = 2 \begin{pmatrix}
  2 & -1 \\
  3 & 4
  \end{pmatrix}
  = \begin{pmatrix}
  2 \cdot 2 & 2 \cdot (-1) \\
  2 \cdot 3 & 2 \cdot 4
  \end{pmatrix}
  $$
  
  $$
  2A =
  \begin{pmatrix}
  4 & -2 \\
  6 & 8
  \end{pmatrix}
  $$
  
  $$
  2A - B = 
  \begin{pmatrix}
  4 & -2 \\
  6 & 8
  \end{pmatrix} -
  \begin{pmatrix}
  5 & 2 \\
  -1 & 3
  \end{pmatrix}
  $$
  
  $$
  2A - B =
  \begin{pmatrix}
  4 - 5 & -2 - 2 \\
  6 - (-1) & 8 - 3
  \end{pmatrix}
  $$
  
  $$
  2A - B =
  \begin{pmatrix}
  -1 & -4 \\
  7 & 5
  \end{pmatrix}
  $$
  
  ### AB
  
  $$
  A \times B =
  \begin{pmatrix}
  2 & -1 \\
  3 & 4
  \end{pmatrix}
  \begin{pmatrix}
  5 & 2 \\
  -1 & 3
  \end{pmatrix}
  $$
  
  $$
  A \times B =
  \begin{pmatrix}
  (2)(5) + (-1)(-1) & (2)(2) + (-1)(3) \\
  (3)(5) + (4)(-1) & (3)(2) + (4)(3)
  \end{pmatrix}
  $$
  
  $$
  A \times B =
  \begin{pmatrix}
  10 + 1 & 4 + (-3) \\
  15 + (-4) & 6 + 12
  \end{pmatrix}
  $$
  
  $$
  A \times B =
  \begin{pmatrix}
  11 & 1 \\
  11 & 18
  \end{pmatrix}
  $$
  
  
  ### BA
  
  $$
  B \times A =
  \begin{pmatrix}
  5 & 2 \\
  -1 & 3
  \end{pmatrix}
  \begin{pmatrix}
  2 & -1 \\
  3 & 4
  \end{pmatrix}
  $$
  
  
  $$
  B \times A =
  \begin{pmatrix}
  (5)(2) + (2)(3) & (5)(-1) + (2)(4) \\
  (-1)(2) + (3)(3) & (-1)(-1) + (3)(4)
  \end{pmatrix}
  $$
  
  $$
  B \times A =
  \begin{pmatrix}
  10 + 6 & -5 + 8 \\
  -2 + 9 & 1 + 12
  \end{pmatrix}
  $$
  
  $$
  B \times A =
  \begin{pmatrix}
  16 & 3 \\
  7 & 13
  \end{pmatrix}
  $$
  
  
  ###  $A^T$ 
  
  $$
  A =
  \begin{pmatrix}
  2 & -1 \\
  3 & 4
  \end{pmatrix}
  $$  
  
  $$
  A^T =
  \begin{pmatrix}
  2 & 3 \\
  -1 & 4
  \end{pmatrix}
  $$ 

  # Ejercicio 3: Multiplicacion en Cadena
  
    
  $$
  A = \begin{pmatrix}
  1 & 2 \\
  3 & 4
  \end{pmatrix},
  \quad
  B = \begin{pmatrix}
  2 & 0 \\
  1 & 3
  \end{pmatrix},
  \quad
  C = \begin{pmatrix}
  1 & 1 \\
  0 & 2
  \end{pmatrix}
  $$
  
  
  
  $$
  AB =
  \begin{pmatrix}
  1 & 2 \\
  3 & 4
  \end{pmatrix}
  \begin{pmatrix}
  2 & 0 \\
  1 & 3
  \end{pmatrix}
  $$
  
  $$
  AB =
  \begin{pmatrix}
  (1)(2) + (2)(1) & (1)(0) + (2)(3) \\
  (3)(2) + (4)(1) & (3)(0) + (4)(3)
  \end{pmatrix}
  $$
  
  $$
  AB =
  \begin{pmatrix}
  4 & 6 \\
  10 & 12
  \end{pmatrix}
  $$
  
  $$
  (AB)C =
  \begin{pmatrix}
  4 & 6 \\
  10 & 12
  \end{pmatrix}
  \begin{pmatrix}
  1 & 1 \\
  0 & 2
  \end{pmatrix}
  $$
  
  $$
  (AB)C =
  \begin{pmatrix}
  (4)(1) + (6)(0) & (4)(1) + (6)(2) \\
  (10)(1) + (12)(0) & (10)(1) + (12)(2)
  \end{pmatrix}
  $$
  
  $$
  (AB)C =
  \begin{pmatrix}
  4 & 16 \\
  10 & 34
  \end{pmatrix}
  $$
  
  
  $$
  BC =
  \begin{pmatrix}
  2 & 0 \\
  1 & 3
  \end{pmatrix}
  \begin{pmatrix}
  1 & 1 \\
  0 & 2
  \end{pmatrix}
  $$
  
  $$
  BC =
  \begin{pmatrix}
  (2)(1) + (0)(0) & (2)(1) + (0)(2) \\
  (1)(1) + (3)(0) & (1)(1) + (3)(2)
  \end{pmatrix}
  $$
  
  $$
  BC =
  \begin{pmatrix}
  2 & 2 \\
  1 & 7
  \end{pmatrix}
  $$
  
  
  
  $$
  A(BC) =
  \begin{pmatrix}
  1 & 2 \\
  3 & 4
  \end{pmatrix}
  \begin{pmatrix}
  2 & 2 \\
  1 & 7
  \end{pmatrix}
  $$
  
  $$
  A(BC) =
  \begin{pmatrix}
  (1)(2) + (2)(1) & (1)(2) + (2)(7) \\
  (3)(2) + (4)(1) & (3)(2) + (4)(7)
  \end{pmatrix}
  $$
  
  $$
  A(BC) =
  \begin{pmatrix}
  4 & 16 \\
  10 & 34
  \end{pmatrix}
  $$
  
  
  
  $$
  (AB)C = A(BC) =
  \begin{pmatrix}
  4 & 16 \\
  10 & 34
  \end{pmatrix}
  $$






