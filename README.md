# Apuntes-Dinamica de Sistemas-Primer Corte-2025
# Nombre: Kevin Nicolas Perez Tobar
#  Facultad: Mecatronica
# Grupo: M6A

# Apuntes de la clase Dia 1
## Transformada de Laplace

>🔑*sistema*: Es una combinacion de compoenetes que actuan conjutamente para alcanzar un objetivo. Se puede representar mediante este esquema las entradas y slaidas
>
> ![Figura de prueba](https://github.com/Djtunder/Apuntes-Kevin-Perez/blob/fd77448d6f3245fa697195d5269b578426b9619d/Grafica1.png)
>
>>Figura 1. Figura de Prueba
>>
>🔑 *Sistema Dinamico*: Es aquel sistema que depende de la entrada y salida.
>>
>🔑* Sistema Estatico*: Si su salida depende unicamente de la entrada en caso, el sistema se conoce como estatico.
>> 
>> 💡'Ejemlos:'
>> 
>>  Circuito Transistorio de Motor DC
>> >![figura de prueba 2](https://github.com/Djtunder/Apuntes-Kevin-Perez/blob/c3deab089e3c7beb97cd2a524eb3f094d8946527/circuito%202.jpg)
>>
>> Circuito Dinamico de Motor DC
>> ![Figura de Prueba 3](https://github.com/Djtunder/Apuntes-Kevin-Perez/blob/697bf00f683cd438f16ca847671ecc0fddbd562e/CIRCUITO%20DE%20TRANSFERENCIA%20MOTOR%20DC.jpg)
>>
> 🔑 *Planta*: Es todo aquello a que se puede referir un proceso
>>
> 🔑*Proceso-Sinonimo*: Es la secuencia de pasos que te permite el objetivo de un producto
>>
>🔑*Modelos Dinamicos*: Hay modelos matemticos que varian en funcion del tiempo, entonces tenemos simplemente:
>>  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=f(t)"><img src="http://www.alciro.org/cgi/tex.cgi?f(t)" title="f(t)" border="0" /></a>
## SISTEMAS LINEALES Y NO LINEALES
>> 🔑*Sistema Lineal*:  es un modelo matemático de un sistema basado en el uso de un operador lineal. Los sistemas lineales generalmente exhiben características y propiedades que son mucho más simples que el caso no lineal.
>>
## EJEMPLOS DE SISTEMAS LINEALES
>>
## CIRCUITO RLC
![image-31](https://github.com/user-attachments/assets/fac02e05-398f-4bf0-a23c-eb64015bd0fd)
>>
>>
## SISTEMA AMORTIGUADO MASA-RESORTE
![sistema masa resorte](https://github.com/user-attachments/assets/7f010590-7f02-4b14-8b03-0e79c8f5da9c)

>>
>>
## SISTEMAS NO LINEALES
> 🔑*Definicion*: Un sistema no lineal en dinámica de sistemas es aquel en el que las ecuaciones que describen su comportamiento no son lineales, es decir, no pueden ser representadas por una combinación lineal de las variables del sistema. En otras palabras, las relaciones entre las variables del sistema no siguen una proporción directa y constante.
>>
## ECUACION
> 💡*Ejemplo*: un sistema descrito por la ecuación diferencial:
>>
$$\frac{d^2x}{dt^2} + \sin(x) = 0$$
>>
>> 💡*Ejemplo*: Pendulo Rotacional
>>

![unnamed](https://github.com/user-attachments/assets/c0d870c3-0c6a-42b7-b16a-7aa83e97621d)


### CALCULO DIFERENCIAL
>>
![](https://github.com/Djtunder/Apuntes-Kevin-Perez/blob/333a0f27b44763ac068e688d9b3f4c7e74d85e69/Grafica%201%20Derivada.jpg)
>>
>>
![Grafica de la derivada](Grafica_1_Derivada.jpg)

### APUNTES CLASE 2
### DESCOMPOCISION DE FRACCIONES PARCIALES
> 🔑*Caso 1*: Q(s) tiene raíces reales distintas.
>
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G\left(s\right)=\frac{P\left(S\right)}{Q\left(S\right)}=\frac{P\left(S\right)}{\left(s+p_1\right)\left(s+p_2\right)+...(s+p_{n)}}\ \ \ \ "><img src="http://www.alciro.org/cgi/tex.cgi?G\left(s\right)=\frac{P\left(S\right)}{Q\left(S\right)}=\frac{P\left(S\right)}{\left(s+p_1\right)\left(s+p_2\right)+...(s+p_{n)}}\ \ \ \ " title="G\left(s\right)=\frac{P\left(S\right)}{Q\left(S\right)}=\frac{P\left(S\right)}{\left(s+p_1\right)\left(s+p_2\right)+...(s+p_{n)}}\ \ \ \ " border="0" /></a>
</center>
>
> Entonces,
>
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{A}{(s+p_1)}+\frac{B}{(s+p_2)}+...\frac{N}{(s+p_{n)}}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{A}{(s+p_1)}+\frac{B}{(s+p_2)}+...\frac{N}{(s+p_{n)}}" title="\frac{A}{(s+p_1)}+\frac{B}{(s+p_2)}+...\frac{N}{(s+p_{n)}}" border="0" /></a>
</center>

> 🔑*Caso 2*:Que N tiene raices reales repetidos.
>
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G(s)=\frac{P(s)}{Q(s)}=\frac{P_{(s)}}{{(s+p)}^n}"><img src="http://www.alciro.org/cgi/tex.cgi?G(s)=\frac{P(s)}{Q(s)}=\frac{P_{(s)}}{{(s+p)}^n}" title="G(s)=\frac{P(s)}{Q(s)}=\frac{P_{(s)}}{{(s+p)}^n}" border="0" /></a>  
</center>
>

> 🔑*Caso 3*: Q(s), tiene raices complejas conjugadas.
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G\left(s\right)=\frac{P\left(S\right)}{Q\left(S\right)}=\frac{P\left(S\right)}{\left(s^2+b_1+c_1\right)\left(s^2+b_s+C_S\right)+\ldots\left(s^2+bnS+Cn\right\}}\ \ \ \ "><img src="http://www.alciro.org/cgi/tex.cgi?G\left(s\right)=\frac{P\left(S\right)}{Q\left(S\right)}=\frac{P\left(S\right)}{\left(s^2+b_1+c_1\right)\left(s^2+b_s+C_S\right)+\ldots\left(s^2+bnS+Cn\right\}}\ \ \ \ " title="G\left(s\right)=\frac{P\left(S\right)}{Q\left(S\right)}=\frac{P\left(S\right)}{\left(s^2+b_1+c_1\right)\left(s^2+b_s+C_S\right)+\ldots\left(s^2+bnS+Cn\right\}}\ \ \ \ " border="0" /></a>
</center>

## SOLUCION DE EJERCICIOS
> Ejercicio: Obtenga la trnaformada inversa de la siguiente funcion
>🔑*Caso 3*: Q(s), tiene raices complejas conjugadas, se aplica a este ejercicio:
>
<center>
 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G(s)=\frac{s^2+2s+3}{(s^2+2S+2)(s^2+2s+5)}"><img src="http://www.alciro.org/cgi/tex.cgi?G(s)=\frac{s^2+2s+3}{(s^2+2S+2)(s^2+2s+5)}" title="G(s)=\frac{s^2+2s+3}{(s^2+2S+2)(s^2+2s+5)}" border="0" /></a> 
</center>
>>💡Ejemplo de descomposición en fracciones parciales y transformada inversa de Laplace
# Ejemplo de descomposición en fracciones parciales y transformada inversa de Laplace

Consideramos la función \( G(s) \):

$$\[G(s) = \frac{s^2 + 2s + 3}{(s^2 + 2s + 2)(s^2 + 2s + 5)}\]$$

### Paso 1: Descomposición en fracciones parciales

Escribimos \( G(s) \) como una suma de fracciones parciales:

$$\[\frac{s^2 + 2s + 3}{(s^2 + 2s + 2)(s^2 + 2s + 5)} = \frac{A s + B}{s^2 + 2s + 2} + \frac{C s + D}{s^2 + 2s + 5}\]$$

### Paso 2: Resolver para \( A \), \( B \), \( C \), y \( D \)

Multiplicamos ambos lados por \( (s^2 + 2s + 2)(s^2 + 2s + 5) \) para eliminar los denominadores:

$$\[s^2 + 2s + 3 = (A s + B)(s^2 + 2s + 5) + (C s + D)(s^2 + 2s + 2)\]$$

### Paso 3: Expandir ambos términos

Expandimos ambos términos del lado derecho:

$$\[s^2 + 2s + 3 = (A s + B)(s^2 + 2s + 5) + (C s + D)(s^2 + 2s + 2)\]$$

Al expandir y agrupar términos, obtenemos el siguiente sistema de ecuaciones:

1) \( A + C = 0 \)

2) \( 2A + B + 2C + D = 1 \)

3) \( 5A + B + 2C + 2D = 2 \)

4) \( 5B + 2D = 3 \)

### Paso 4: Despejar \( A \) y resolver el sistema

Despejamos \( A \):

$$\[A = -C\]$$

Sustituimos en la ecuación (2):

$$\[2(-C) + B + 2C + D = 1\]$$

$$\[-2C + B + 2C + D = 1\]$$

$$\[B + D = 1\]$$
>>

### FRACCIONES PARCIALES EN MATLAB
> Matlab se puede calcular los terminos de las fracciones parciales conociendo los polinomios del numerador y el denominador de la funcion en el dominio s.
> Ejercicio: Transforme en el dominio de s la siguiente funcion:
> r=> terminos del numerador
> p=> terminos del denominador
> k=> terminos independientes
>
<center>
 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=F\left(s\right)=\frac{\left(s^2-s-3\right)}{s\left(s-1\right)\left(s+3\right)}"><img src="http://www.alciro.org/cgi/tex.cgi?F\left(s\right)=\frac{\left(s^2-s-3\right)}{s\left(s-1\right)\left(s+3\right)}" title="F\left(s\right)=\frac{\left(s^2-s-3\right)}{s\left(s-1\right)\left(s+3\right)}" border="0" /></a>
</center>

>>💡Ejemplo

$Si f(x)=sen(x^2)$

**Entonces**

$$f'(x)=cos(x^2)*2x = 2xcos(x^2)$$

## Derivadas de funciones comunes

![image](https://github.com/user-attachments/assets/1ed3d45d-15d2-4197-b809-18af999a78bd)

## 🔑MODELAMIENTO Y VALIDACION
El modelamiento consiste en representar un sistema fisico mediante ecuacines metematicas basadas en principios fisicos, como la mecanica, la termodinameica o la electronica sin embargo estos 
modelos pueden representar dudas debido a simplificaciones.
La **validacion** es el proceso de comprobar que el modelo matematico representa decuadamente el comportamiento real del sistema. para ell se comparan las salidas del modelo con las mediciones
experimentales y si la diferencia no es aceptable se ajusta el modelo.

## 🔑Transformada de LaPlace
La trnsforma de laplace es una tecnica que transforma funciones que dependen del tiempo en una forma mas simplificada y facil de manejar, especialmente cuando se trabaja con ecuaciones diferenciales, en vez de resolver estas ecuaciones directamente,la transformada de laplace las convierte en ecuaciones algebraicas simples.
basicamente toma una funcion en el tiempo y la transforma el dominio de la frecuencia donde se puede hacer calculos mas sencillos. 

![image](https://github.com/user-attachments/assets/bd13df49-0c43-4438-a19b-47a7421f2281)

$$\mathcal{L}\{f(t)\} = F(s) = \int_{0}^{\infty} e^{-st} f(t) \, dt$$

**💡Ejemplo transformada de una funcion exponencial**

# Ejemplo de descomposición en fracciones parciales y transformada inversa de Laplace

Consideramos la función \( G(s) \):

$$\[G(s) = \frac{s^2 + 2s + 3}{(s^2 + 2s + 2)(s^2 + 2s + 5)}\]$$

### Paso 1: Descomposición en fracciones parciales

Escribimos \( G(s) \) como una suma de fracciones parciales:

$$\[\frac{s^2 + 2s + 3}{(s^2 + 2s + 2)(s^2 + 2s + 5)} = \frac{A s + B}{s^2 + 2s + 2} + \frac{C s + D}{s^2 + 2s + 5}\]$$

### Paso 2: Resolver para \( A \), \( B \), \( C \), y \( D \)

Multiplicamos ambos lados por \( (s^2 + 2s + 2)(s^2 + 2s + 5) \) para eliminar los denominadores:

$$\[s^2 + 2s + 3 = (A s + B)(s^2 + 2s + 5) + (C s + D)(s^2 + 2s + 2)\]$$

### Paso 3: Expandir ambos términos

Expandimos ambos términos del lado derecho:

$$\[s^2 + 2s + 3 = (A s + B)(s^2 + 2s + 5) + (C s + D)(s^2 + 2s + 2)\]$$

### TRANSFORMADA INVERSA DE LAPLACE 
Transforme al dominio s:
<center>
 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=8\sin{(4t)-5\cos{(4t)}}"><img src="http://www.alciro.org/cgi/tex.cgi?8\sin{(4t)-5\cos{(4t)}}" 
                                                                                                     title="8\sin{(4t)-5\cos{(4t)}}" border="0" /></a>
</center>
>
> Para obtener la transformada usamos Matlab, ya que nos permite verificar si la ecuacion quedo bien resuelta y asi la podemos comprobar Las Variables t y s para pasar al dominio s
y  denotamos la variable t en minuscula para expresar la funcion defininida en el tiempo.
>
<center>
 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=8\sin{(4t)-5\cos{(4t)}}"><img src="http://www.alciro.org/cgi/tex.cgi?8\sin{(4t)-5\cos{(4t)}}" title="8\sin{(4t)-5\cos{(4t)}}" border="0" /></a>
</center>
> Aplicamos la transfromada inversa
>
<center>
 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\mathcal{L}^{-1}{(8\sin{(4t)-5\cos{(4t)}}"><img src="http://www.alciro.org/cgi/tex.cgi?\mathcal{L}^{-1}{(8\sin{(4t)-5\cos{(4t)}}" title="\mathcal{L}^{-1}{(8\sin{(4t)-5\cos{(4t)}}" border="0" /></a>
</center>
>
>> La solucion de la ecuacion es:

>> >![](https://github.com/Djtunder/Apuntes-Kevin-Perez/blob/main/Ejercicio%20de%20Transformada%20de%20Laplace.jpg)
>
> ### APUNTES CLASE 3
> ###  TRANSFORMADA DE LAPLACE
> ## Definicion de Transformada de Laplace
> Sea E el espacio vectorial de las funciones continuas a trozos y de orden exponencial (esto
es, dada una funci´on f(t) continua a trozos existen las constantes K y ω tales que ∀t la
funcion f est´a acotada en la forma |f(t)| ≤ Ke
ωt).
>
### TRANSFROMADAS DE LAPLACE EN MODELOS DINAMICOS
>> 🔑*Definicion*: Propósito en modelos dinámicos:
En el análisis de sistemas dinámicos, la Transformada de Laplace se usa para:
>>
Simplificar la resolución de ecuaciones diferenciales: Al transformar una ecuación diferencial en una ecuación algebraica, es mucho más sencillo manipular y resolver el sistema.
Estudiar la estabilidad de un sistema: El dominio 𝑠, se puede usar para examinar los polos del sistema, lo que ayuda a determinar si el sistema es estable, marginalmente estable o inestable.Obtener la respuesta en el dominio del tiempo: Después de resolver el sistema en el dominio s, la transformada inversa de Laplace permite obtener la solución en el dominio original del tiempo.
>>
## ECUACION
$$
\tau \frac{d y(t)}{dt} + y(t) = u(t)
$$
>>
## Transformada de LaPlace
La trnsforma de laplace es una tecnica que transforma funciones que dependen del tiempo en una forma mas simplificada y facil de manejar, especialmente cuando se trabaja con ecuaciones diferenciales, en vez de resolver estas ecuaciones directamente,la transformada de laplace las convierte en ecuaciones algebraicas simples.
basicamente toma una funcion en el tiempo y la transforma el dominio de la frecuencia donde se puede hacer calculos mas sencillos. 

![image](https://github.com/user-attachments/assets/bd13df49-0c43-4438-a19b-47a7421f2281)

$$\mathcal{L}\{f(t)\} = F(s) = \int_{0}^{\infty} e^{-st} f(t) \, dt$$
>>
### CASOS DE SOLUCION DE ECUACIONES DIFERENCIALES 
## CASO 1
>>🔑 Definicion 1.1: El caso 1 de una solución de una ecuación diferencial lineal homogénea con coeficientes constantes se refiere a un caso en el que todas las raíces de la ecuación característica o auxiliar son diferentes.
>>
>>💡Ejemplo de Transformada de Laplace

Consideramos la ecuación diferencial de segundo orden:

$$\ddot{x} + 3\dot{x} + 2x = 0$$

con condiciones iniciales $\(x(0) = a\) y \(\dot{x}(0) = b\)$.

## Paso 1: Aplicar la transformada de Laplace

Aplicamos la transformada de Laplace a ambos lados de la ecuación:

$$
\mathcal{L}\{ \ddot{x}(t) \} = s^2 X(s) - s x(0) - \dot{x}(0)
$$
$$
\mathcal{L}\{ x(t) \} = X(s)
$$

Sustituyendo en la ecuación obtenemos:

$$
[s^2 X(s) - s x(0) - \dot{x}(0)] + 3[s X(s) - x(0)] + 2X(s) = 0
$$

## Paso 2: Reemplazar condiciones iniciales

Reemplazamos \(x(0) = a\) y \(\dot{x}(0) = b\):

$$
[s^2 X(s) - s a - b] + 3[s X(s) - a] + 2X(s) = 0
$$

Desarrollamos:

$$
[s^2 X(s) - s a - b] + 3s X(s) - 3a + 2X(s) = 0
$$

## Paso 3: Agrupar términos

Reagrupamos para despejar \(X(s)\):

$$
[s^2 + 3s + 2] X(s) = s a + b + 3a
$$

## Paso 4: Despejar \(X(s)\)

Despejamos \(X(s)\):

$$
X(s) = \frac{s a + b + 3a}{s^2 + 3s + 2}
$$

## Paso 5: Factorización del denominador

Factoreamos el denominador:

$$
X(s) = \frac{s a + b + 3a}{(s + 1)(s + 2)}
$$

## Ejemplo numérico:

Si \(a = 2\) y \(b = 3\), la solución es:

$$
X(s) = \frac{2s + 9}{(s + 1)(s + 2)}
$$
>>
## CASO 2
>> 🔑 Definicion 1.2:es un caso específico que se presenta al resolver ecuaciones diferenciales utilizando la transformada inversa de Laplace. Este caso ocurre cuando el denominador de la función de Laplace, que representa el sistema en el dominio s, tiene raíces reales y coincidentes (es decir, repetidas) en el polinomio del denominador.
>> 💡Ejemplo:
>>
 $$\[F(s) = \frac{P(s)}{(s + a)^n}\]$$
 >>
## PROCEDIMIENTO
Dada la siguiente función:

$$\[F(s) = \frac{s^2 + 2s + 3}{(s + 1)^3}\]$$

Aplicamos descomposición en fracciones parciales:

$$\[F(s) = \frac{A(s)}{(s+1)^3} + \frac{B(s)}{(s+1)^2} + \frac{C(s)}{(s+1)}\]$$

Multiplicamos por el denominador común:

$$\[s^2 + 2s + 3 = A(s)(s+1) + B(s)(s+1)^2 + C(s)(s+1)^3\]$$

Expandimos y agrupamos los términos:

$$\[s^2 + 2s + 3 = (A + B + C)s^3 + (2A + 2B + 3C)s^2 + (A + B + 3C)s + (A + C)\]$$

Comparando coeficientes, obtenemos el siguiente sistema de ecuaciones:

$$\[
\begin{aligned}
A + B + C &= 0 \\
2A + 2B + 3C &= 1 \\
A + B + 3C &= 2 \\
A + C &= 3
\end{aligned}
\]$$

Resolviendo el sistema, encontramos:

$$\[A = 2, \quad B = -3, \quad C = 1\]$$

Sustituyendo en la ecuación original:

$$\[F(s) = \frac{2}{(s+1)^3} - \frac{3}{(s+1)^2} + \frac{1}{s+1}\]$$

Aplicamos la transformada inversa de Laplace:

$$\[f(t) = 2 \cdot t^2 e^{-t} - 3 \cdot t e^{-t} + e^{-t}\]$$
>>
## CASO 3
>>🔑Defincion 1.3: Cuando la ecuación diferencial tiene raíces complejas conjugadas, la función de Laplace tiene términos con denominadores que contienen un factor de la forma 
(𝑠+𝛼)2+𝛽2(s+α) 2 +β 2, donde α es la parte real de las raíces y β es la parte imaginaria. Este caso se puede representar generalmente de la siguiente manera:
>>
>>💡Ejemplo:
>># Ejemplo de Prueba: Raíces Complejas Conjugadas

Consideramos la ecuación diferencial:

$$\[y'' + 2y' + 5y = 0\]$$

### Paso 1: Transformada de Laplace de la ecuación

Aplicamos la transformada de Laplace a ambos lados de la ecuación. Usando las transformadas de Laplace de las derivadas:

- $$\( \mathcal{L}\{y'(t)\} = sY(s) - y(0) \)$$
- $$\( \mathcal{L}\{y''(t)\} = s^2Y(s) - sy(0) - y'(0) \)$$

Con condiciones iniciales \( y(0) = 0 \) y \( y'(0) = 0 \), obtenemos:

$$\[s^2 Y(s) + 2s Y(s) + 5 Y(s) = 0\]$$

Factorizando:

$$\[Y(s) \left( s^2 + 2s + 5 \right) = 0\]$$

### Paso 2: Resolver la ecuación en el dominio \( s \)

La ecuación \( s^2 + 2s + 5 = 0 \) tiene raíces complejas conjugadas. Usamos la fórmula cuadrática:

$$\[s = \frac{-2 \pm \sqrt{2^2 - 4(1)(5)}}{2(1)} = \frac{-2 \pm \sqrt{-16}}{2} = -1 \pm 2i\]$$

Las raíces son complejas $$\( s_1 = -1 + 2i \) y \( s_2 = -1 - 2i \)$$.

### Paso 3: Aplicar la transformada inversa de Laplace

La transformada inversa de Laplace de \( Y(s) \) es:

$$\[y(t) = e^{-t} \left( \cos(2t) + \frac{\sin(2t)}{2} \right)\]$$

Este es el comportamiento oscilatorio amortiguado de la solución en el dominio del tiempo.
>>
### REFERENCIAS
 (Sergio C., 2013)
 https://controlautomaticoeducacion.com/analisis-de-sistemas/6-transformada-de-laplace-en-analisis-de-sistemas/
 >>
 (Rodriguez, 2023/2024)
https://www.studocu.com/co/document/universidad-nacional-abierta-y-a-distancia/sistemas-dinamicos/fase-3-grupo-243005-105-sistemas-dinamicos/94307502
>>
### CONCLUSIONES
>>Aprendimos a interpretar las diferentes ecuaciones diferenciales a travez de las tecnicas vistas de cursos anteriores en Fracciones Parciales
>> La técnica de fracciones parciales permite descomponer funciones racionales en términos más simples, lo que facilita la aplicación de la transformada inversa de Laplace.
>> La transformada inversa de Laplace permite obtener las soluciones en el dominio del tiempo, revelando cómo el sistema reacciona a estímulos iniciales y cómo sus variables evolucionan en el tiempo, incluyendo oscilaciones, amortiguamiento y estabilidad.

 
 







                                                                                                                                                                                         




