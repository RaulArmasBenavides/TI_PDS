# TI_PDS
TI_PDS using App designer
DISEÑO DE LA INTERFAZ
a)	Seleccionar los tres sonidos de interés de algún sitio de internet (no más de 10 segundos de duración). Además, deben tener una Fs=16 KHz, un solo canal y codificado con 8 o 16 bits/muestra.	(04 puntos).		                                                                        
Para la elaboración del presente trabajo de investigación, se va a reconocer instrumentos musicales como la flauta, la guitarra, así como también el sonido de dos frecuencias, 1600 Hz y 2400 Hz.
El primer sonido es una flauta, que acciona un led verde. Por otro lado, el segundo sonido es una guitarra acústica, la cual acciona un micro servomotor. Además, el tercer sonido es la frecuencia de 1600 Hz, que acciona un puntero láser. Finalmente, el cuarto sonido es la frecuencia de 2500 Hz, que acciona un buzzer. Se programó el código para la elección de 8 o 16 bits por muestra; sin embargo, en esta ocasión hemos escogido 8 bits por muestra.
b)	Desarrollar un código de programación en el App Designer del Matlab, que permita recibir en tiempo real los sonidos seleccionados, para luego procesarlos en el dominio de la frecuencia y lograr el reconocimiento de cada uno.	
c)	Encender el actuador 1 conectado al módulo Arduino Uno, cada vez que se reconozca el primer sonido, el actuador 2 cuando se reconozca el segundo sonido, el actuador 3 cuando se reconozco el tercer sonido, y el actuador 4 cuando no se trate de ninguno de los sonidos seleccionadas para este trabajo.							(08 puntos).

![interfaz](https://github.com/RaulArmasBenavides/TI_PDS/assets/20383126/94c59e3e-494d-40e6-93e3-0949bc70fa8e)

Encendemos el Arduino Uno:
	Sonido de flauta
Grabamos y reproducimos la flauta sin filtrar:


![flauta2](https://github.com/RaulArmasBenavides/TI_PDS/assets/20383126/09a43f0a-6ddb-484a-9ab0-7dae1d10a705)

Procesamos y reproducimos la flauta filtrada:

![flauta3](https://github.com/RaulArmasBenavides/TI_PDS/assets/20383126/3e644512-eb44-4d6d-88ae-1668291798f1)

Se enciende el led verde:

![faluta4](https://github.com/RaulArmasBenavides/TI_PDS/assets/20383126/2d8d03b8-86c6-4646-b80d-c2d0f69217ad)

	Sonido de guitarra

Grabamos y reproducimos la guitarra sin filtrar:

![guitarra1](https://github.com/RaulArmasBenavides/TI_PDS/assets/20383126/9279e7e8-5df2-4f89-8835-b31b9b9eda70)


Procesamos y reproducimos la guitarra filtrada:
Movimientos del micro servomotor

![servo1](https://github.com/RaulArmasBenavides/TI_PDS/assets/20383126/fe7ab1cb-6e08-43f8-905c-cab001ce5a1a)



	Sonido de 1600 Hz
Grabamos y reproducimos el sonido de 1600 Hz sin filtrar:
Procesamos y reproducimos el sonido de 1600 Hz filtrado:
Se proyecta el puntero láser:



	Sonido de 2500 Hz

Grabamos y reproducimos el sonido de 2500 Hz sin filtrar:
Procesamos y reproducimos el sonido de 2500 Hz filtrado:
Se escucha el pitido del buzzer:
