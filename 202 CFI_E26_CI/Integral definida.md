---
scope: Específico
theme: white
---

| Antecedentes         |
| -------------------- |
| [[Sumas de Riemann]] |

---

# Intuición
Es el numero que resulta de calcular el límite de la suma de Riemann desde el extremo inferior $a$ hasta el extremo superior $b$ cuando **la norma de la partición** $||P|| \to 0$
$$||P|| = ||\Delta x||$$
$$||\Delta x|| = \frac{|b-a|}{n}$$

---

Si $||\Delta x|| \to 0$, entonces 
$$\frac{|b-a|}{n} \to 0$$
>¿Cuándo se cumple?

--

>$n\to \infty$

---

Se dice que $f$ **es integrable** entre $[a,b]$ si existe el límite de la suma de Riemann cuando la Norma de la partición $\to 0$

$$
\lim_{||P||\to 0}\ {\sum^{n}_{i=1}{f(\overline{x_l})\,\Delta x_i}}
$$

>La norma de la partición $||P||$ es el mayor valor $\Delta x_i$ de todos los rectángulos

---

# Definición

> [!info] Integral definida
> La **integral definida** de $f$ desde $a$ hasta $b$ es:
> 
> $$ \displaystyle \int_{a}^{b}f(x)\ dx = \lim_{n\to \infty}\ {\sum^{n}_{i=1}{f(\overline{x_l})\ \Delta x}} = L $$
> 
> Si el límite existe, se dice que $f$ es integrable en $[a,b]$


---
# Propiedades

> [!summary] Propiedades
> Sean $f(x)$ y $g(x)$ funciones integrables en el intervalo $[a,b]$ y $k, m, M$ son constantes, se cumplen las siguientes propiedades:


---

$$
\displaystyle \int_{a}^{a} f(x)\,dx = 0
$$
---

$$
\displaystyle  \int_{a}^{b} f(x)\ dx = - \int_{b}^{a} f(x)\ dx
\quad \text{donde } a > b
$$

---
### Linealidadz<
$$
\displaystyle  \int_{a}^{b} k f(x)\ dx = k \int_{a}^{b} f(x)\ dx
$$

$$
\displaystyle  \int_{a}^{b} [f(x) \pm g(x)]\ dx
=
\int_{a}^{b} f(x)\ dx \pm \int_{a}^{b} g(x)\ dx
$$

---
$$
\displaystyle  \int_{a}^{b} f(x)\ dx
=
\int_{a}^{c} f(x)\ dx + \int_{c}^{b} f(x)\ dx
$$

---

$$
\displaystyle  
\int_{a}^{b} f(x)\ dx \le \int_{a}^{b} g(x)\ dx
\quad \text{si } f(x) \le g(x)
$$
---

$$
\displaystyle  
m(b-a) \le \int_{a}^{b} f(x)\ dx \le M(b-a)
$$
$$
\text{siempre que } m \le f(x) \le M \text{ con } x \in [a,b]
$$

---

# Interpretación geométrica

