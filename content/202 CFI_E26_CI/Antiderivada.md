---
theme: white
---
La operación Derivada tiene su propia inversa, la cuál se conoce como ==ANTIDERIVADA== o ==INTEGRACIÓN==

--- 

> [!info] Definción
> $F(x)$ es **una antiderivada** de $f(x)$ en el intervalo $I$ si se verifica que $D_xF(x) = f(x)$
> 
> Es decir:
> $$F\ '(x) = f(x)$$

--

>👀 **una antiderivada**

--

>hay más


El [[Teorema del valor medio del Cálculo Diferencial]] indica que si 2 funciones distintas tienen derivadas iguales en un intervalo, entonces entre ellas solo difieren en una **constante de traslación**

---

Por ejemplo, $f(x) = 5x^4$ en el intervalo $(-\infty, \infty)$, algunas de sus antiderivadas son:

$F(x)= x^5$

$F(x)= x^5 + 20$

$F(x)= x^5 - \pi$

Por lo tanto, $f(x) = 5x^4$ tendrá una *familia de antiderivadas* que se denota como:
$x^5 + C$

$$\int_{}^{}{f(x)\ dx = F(x) + C}$$

---
### Comprobación
Basta con hacer su derivada para comprobar y obtener la función original

$$\int5x^4\ dx = x^5 + C \Longleftrightarrow D_x(x^5 + C) = 5x^4\ $$

---
# Regla de la cadena

---
$$\int f(u)\, du = \int f(u) [D_xu\, dx] = F(u) +C$$

--
## Ejemplo
$$\int{x^2\,dx}$$
--
#### Trivial
$$
\int{x^2\,dx} = 
\boxed{ \frac{x^3}{3}+C}
$$

---
#### Pero ¿y qué tal esta?
$$\int{(x^4+3x)(4x^3+3)\,dx}$$
--
##### Aplicamos regla de la cadena, especialmente:

>$u = x^4+3x$
>observe que entonces:
>$du = (4x^3 + 3)dx$

$$\int {u^2\,du} = \frac{u^3}{3} + C$$

--

>y luego devolvemos $u \to x^4+3x$

$$\boxed{\frac{(x^4+3x)^3}{3}+C}$$
>Pero esto se verá más a profundidad en ==Integración por cambio de Variable==

---
# Ejercicio

---

