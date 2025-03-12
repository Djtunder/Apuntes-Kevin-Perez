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
<center>
$$\frac{d^2x}{dt^2} + \sin(x) = 0$$
</center>


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

### TRANSFROMADA INVERSA DE LAPLACE 
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








                                                                                                                                                                                         




