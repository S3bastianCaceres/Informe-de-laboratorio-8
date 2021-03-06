# Informe-de-laboratorio-8
 
<H2>PRÁCTICA No. 8 CARACTERÍSTICAS DE LA ONDA SENOIDAL</H2>

**<H3>1. OBJETIVOS</H3>**

**Objetivo General**

Identificar las partes del osciloscopio y que funcionamiento tienen, para analizar las ondas sinusoidales representadas en el osiciloscopio, y asi respender a las interrogantes sobre este análisis y exponer el el concepto de la onda sinusoidal teoricamente como matemáticamente.

**Objetivos Especificos**

- Investigar la representacion dela onda senoidal graficamente como matemáticamente

- Determinar si la medida del voltaje de salida (RL) es igual en el osciloscopio como en el multimetro.

<H3>2. MARCO TEÓRICO</H3>

![Onda Senoidal](https://user-images.githubusercontent.com/93739242/153995467-23a43742-816c-46d6-9026-1cd043059f44.png)

![image](https://user-images.githubusercontent.com/93739242/153995706-8975e8ac-ec00-4e14-8fe1-acd61f6387ca.png)


**<H3>3. EXPLICACIÓN DEL PROCEDIMIENTO</H3>**

**<H3>8.2. REQUISITOS PREVIOS.</H3>**

Investigue la representación de la onda senoidal, tanto en su forma gráfica como 
en su forma matemática.

**<H3>8.3. INFORMACIÓN GENERAL</H3>**

Se denomina corriente alterna (ca) a la corriente eléctrica en la que la magnitud y 
dirección varían periódicamente. La forma de onda de la corriente alterna más 
comúnmente utilizada es la de una onda senoidal, puesto que se consigue una transmisión 
más eficiente de la energía.
Generalmente, la corriente alterna se refiere a la forma en la cual la electricidad 
llega a los hogares y a las empresas. Sin embargo, las señales de audio y de radio 
transmitidas por los cables eléctricos, son también ejemplos de corriente alterna.

**<H3>8.4. MATERIAL Y EQUIPO REQUERIDO</H3>**

Cantidad Elemento
- 1 Generador de Funciones
- 1 Osciloscopio
- 1 Multímetro Digital 
- 1 Resistor de 1 kΩ
- 1 Resistor de 2.2 kΩ
- 1 Protoboard 


**<H3>8.5. PROCEDIMIENTO</H3>**


<b>8.5.1. Implemente el circuito que se presenta en la figura 7.1</b>

[![01.png](https://i.postimg.cc/RCkFcCxs/01.png)](https://postimg.cc/F1xNv4R3)

Circuito en multisim

[![circuito02.png](https://i.postimg.cc/L5j6x0rg/circuito02.png)](https://postimg.cc/D4yTZ5f7)


<b>8.5.2.. Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 Khz.</b>

![lagrida_latex_editor](https://user-images.githubusercontent.com/93739242/153795331-0b03c34d-f25f-4fe5-9136-8583f470a506.png)

Ajuste en multisim

[![Fuente.png](https://i.postimg.cc/wj6kHKx2/Fuente.png)](https://postimg.cc/YhsFfsWL)


<b>8.5.3. Conecte el osciloscopio al resistor de carga RL. Observe la señal que aparece en el osciloscopio.</b>

[![CIRCUITO.png](https://i.postimg.cc/4yDV9VsX/CIRCUITO.png)](https://postimg.cc/kRy2rV2H)

**<H3>4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR</H3>**


<b>8.5.4. Responda las siguientes preguntas:</b>


<i>- ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?</i>

La ampplitud abarca 3.5 cuadros por division

<i>- ¿En qué valor está posicionada la perilla VOLTS/DIV?</i>

Se encuentra posicionada en 2V

<i>- ¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?</i>

Un ciclo completo abarca 4 cuadrados por division


<i>- ¿En qué valor está posicionada la perilla TIME/DIV?</i>

Se encuentra posicionada en 100 micro segundos

<b>8.5.5.¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?</b>


![image](https://user-images.githubusercontent.com/93739242/153794511-84355cd8-f73a-44bc-b721-9656abefe1d6.png)

<i>- Amplitud de voltaje: 6.83(V)</i>


![image](https://user-images.githubusercontent.com/93739242/153794445-5d358ecc-b7a8-45bd-ba7e-8be0cdc13f3b.png)

<i>- Periodo: 400(μs)=>0.0004(s)</i>

<b>8.5.6. Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.</b>

<i>- f: (Hz)</i>

![lagrida_latex_editor (8)](https://user-images.githubusercontent.com/93739242/153796077-909dbfcd-bcbe-4d89-a169-a463c370c12e.png)


<i>- ω: (rad/s)</i>

![lagrida_latex_editor (9)](https://user-images.githubusercontent.com/93739242/153796216-b94ccc59-62e8-4e1e-bfbb-417bb2997aa6.png)


<b>8.5.7. Con el multímetro digital mida el voltaje de salida en RL:</b>


![image](https://user-images.githubusercontent.com/93739242/153794086-3ab008d8-fffb-4999-a963-f9c046785889.png)


<b>8.5.8. Compare el voltaje medido en el punto 7.5.5. y el obtenido en el punto 7.5.7.</b>
 
 <b>¿Coinciden?</b>
 
 No coinciden.
 
<b>¿Por qué?</b>

Estos no coinciden ya que el osciloscopio mide el voltaje pico por lo que nos muestra este dato, mientras que el voltimetro mide el voltaje eficaz es decir el voltaje rms.

**<H3>5. VIDEO</H3>**

https://youtu.be/sfQMTBL-Ifc

**<H3>6. CONCLUSIONES</H3>**

- Para poder manipular la onda seno debemos tener en claro que la perilla de SEC/DIV es la que cambia el periodo de la onsa seninusoidal en el eje de las abscisas y la perilla de VOLT/DIV es la que cambia la amplitud de la onda sinusoidal en el eje de las ordenadas.

- La onda sinunsoidal representa el valor de la tensión de la corriente alterna a través de un tiempo continuamente variable y este puede variar dependiendo de como se posiciones las perrillas del osciloscopio y el análisis que se hace al observar la onda sinusoidal.


**<H3>7. BIBLIOGRAFÍA</H3>**

- Zapata, F. (2019, 22 agosto). Onda senoidal: características, partes, cálculo, ejemplos. Lifeder. https://www.lifeder.com/onda-senoidal/
- EcuRed. (s. f.). Onda senoidal - EcuRed. https://www.ecured.cu/Onda_senoidal
