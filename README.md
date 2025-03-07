# Apuntes-Kevin-Perez

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
>> 🔑*Modelos Dinamicos*: Hay modelos matemticos que varian en funcion del tiempo, entonces tenemos simplemente:
>>  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=f(t)"><img src="http://www.alciro.org/cgi/tex.cgi?f(t)" title="f(t)" border="0" /></a>
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

#### APUNTES CLASE 3
## SOLUCION DE EJERCICIOS
> Ejercicio: Obtenga la trnaformada inversa de la siguiente funcion
>🔑*Caso 3*: Q(s), tiene raices complejas conjugadas, se aplica a este ejercicio:
>
<center>
 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G(s)=\frac{s^2+2s+3}{(s^2+2S+2)(s^2+2s+5)}"><img src="http://www.alciro.org/cgi/tex.cgi?G(s)=\frac{s^2+2s+3}{(s^2+2S+2)(s^2+2s+5)}" title="G(s)=\frac{s^2+2s+3}{(s^2+2S+2)(s^2+2s+5)}" border="0" /></a> 
</center>
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transformada Inversa de Laplace</title>
    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/mathjax@2.7.7/MathJax.js?config=TeX-MML-AM_CHTML"></script>
</head>
<body>
    <h1>Transformada Inversa de Laplace</h1>
    <p><strong>Función:</strong></p>
    <p>
        \( G(s) = \frac{s^2 + 2s + 3}{(s^2 + 2s + 2)(s^2 + 2s + 5)} \)
    </p>
    
    <p><strong>Descomposición en fracciones parciales:</strong></p>
    <p>
        \( \frac{s^2 + 2s + 3}{(s^2 + 2s + 2)(s^2 + 2s + 5)} = \frac{-s + 1}{s^2 + 2s + 2} + \frac{\frac{1}{2}s + \frac{1}{2}}{s^2 + 2s + 5} \)
    </p>
    
    <p><strong>Transformada Inversa de Laplace:</strong></p>
    <p>
        La transformada inversa de Laplace de cada término es:
    </p>
    <p>
        \( \mathcal{L}^{-1}\left\{\frac{-s + 1}{s^2 + 2s + 2}\right\} = e^{-t} \cos(t)
    \)
    </p>
    <p>
        \( \mathcal{L}^{-1}\left\{\frac{\frac{1}{2}s + \frac{1}{2}}{s^2 + 2s + 5}\right\} = \frac{1}{2} e^{-2t} \cos(t)
    \)
    </p>

    <p><strong>Solución Final:</strong></p>
    <p>
        La solución final es:
    </p>
    <p>
        \( g(t) = e^{-t} \cos(t) + \frac{1}{2} e^{-2t} \cos(t) \)
    </p>
</body>
</html>





                                                                                                                                                                                         




