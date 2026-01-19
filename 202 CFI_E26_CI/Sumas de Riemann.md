---
scope: Específico
ancestro_directo: "[[Conceptos"
---

| Recursos                                                                                                                   | ADONS                                    |
| -------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| [Geogebra que ejemplifica la Suma de Riemann con $e$ rectángulos bajo la curva](https://www.geogebra.org/classic/czqqrvau) | [[Funciones interesantes para graficar]] |

Partimos de una función $f(x)$ definida en un intervalo cerrado $[a,b]$. La vamos a dividir en $n$ sub-intervalos[^1], la cuál recibirá el nombre de partición $P$

En cada sub-intervalo seleccionamos un punto "*muestra*" que llamaremos $\overline{x_l}$ que puede ser incluso el **punto frontera**

Para cada sub-intervalo, el valor $f(\overline{x_l})$ determinar el valor de la altura de un rectángulo cuya base sea el ancho $\Delta x_i$

De tal forma que la **Suma de Riemann** es el valor resultante de la suma de áreas de todos los rectángulos de la partición
$$
\boxed{ R_p = \sum^{n}_{i=1}{f(\overline{x_i})\Delta x_i} }
$$

Se dice que $f$ es integrable entre $[a,b]$ si existe el límite de la suma de Riemann cuando la Norma de la partición $\to 0$

$$
\lim_{||P||\to 0}\ {\sum^{n}_{i=1}{f(\overline{x_l})\,\Delta x_i}}
$$




[^1]: No necesariamente de la misma magnitud
