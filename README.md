# TRABAJO PRACTICO

1. **¿Qué tipo de autómata corresponde a lr-conocido?**  
   Es un **autómata finito determinístico (AFD)**.

2. **Diagrama del autómata:**  
   ![Automata](https://iili.io/fCy4KIj.md.png)

   Definición formal:  
   - ({0, 1, 2, 3},  {+, -, 0,1,2,3,4,5,6,7,8,9}, {0} , {2}, {0 ⇒ S ⇒ 1, 0 ⇒ D ⇒ 2, 0 ⇒ O ⇒ 3,1 ⇒ S ⇒ 3, 1 ⇒ D ⇒ 2, 1 ⇒ O ⇒ 3,2 ⇒ S ⇒ 3, 2 ⇒ D ⇒ 2, 2 ⇒ O ⇒ 3,3 ⇒ S ⇒ 3, 3 ⇒ D ⇒ 3, 3 ⇒ O ⇒ 3} )

3. **Comparación con constanteEntera:**  
   El lenguaje de `lr-conocido` reconoce **solo enteros decimales** y `constanteEntera` reconoce **enteros decimales, octales y hexadecimales** por lo tanto **El lenguaje reconocido está incluido dentro de constanteEntera.**

4. **¿Son infinitos?**  
   Sí, **ambos lenguajes son infinitos**.

5. **¿Qué tipo de autómata corresponde a lic-clasico?**  
   Es un **autómata finito con pila determinístico (PDA)**.

6. **¿Cuál es la menor palabra que reconoce?**  
   La **cadena vacía (ε)**.

7. **¿Qué estructura de datos utiliza este autómata?**  
   Utiliza una **pila**.

8. **¿Con qué etapas del proceso de compilación se relaciona cada autómata?**  
   - `lr-conocido` → **Análisis léxico**  
   - `lic-clasico` → **Análisis sintáctico**
9. **¿Qué significa la palabra static? ¿En dónde se guarda?**
    - La palabra `static` define una variable que conserva su valor entre llamadas y se almacena en la sección de reserva estática de la memoria del programa.

10.
    | Variable            | Tipo de dato   | Sección de la variable | Sección de los datos                                        |
    | ------------------- | -------------- | ---------------------- | ----------------------------------------------------------- |
    | **palabra**         | `const char *` | *stack*                | **static**                                                  |
    | **longitud_maxima** | `size_t`       | *stack*                | stack                                                       |
    | **pila**            | `t_pila *`     | *stack*                | **heap**                                                    |
    | **sentido**         | `int`          | *stack*                | stack                                                       |
    | **ptr_sentido**     | `int *`        | *stack*                | stack                                                       |





