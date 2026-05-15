# sesion-08a

**Clase 28 de abril**

## **CLASE INTRODUCCION KICAD**

kicad
descargar-window-github
configuracion predeterminada
*start whit the...(descargar esa opcion)*
*PCB= Es como una “tabla” donde se conectan y sujetan los componentes electrónicos*

*Defult=crear carpeta kicad

Archivos kicad= **_Pro**

*hacer una atari punk*

|pasos| Que hacer|
|--------|------|
|Paso 1°|Dibujar esquematico(kicad_sch|
|Paso 2°|Asociar huellas a simbolos|
|Paso 3°|Abrir PCB new (crear la pcb)interprete del esquematico|
|Paso 4°|definir tamaño de las pistas|
|Paso 5°|Repartir componentes fisicamente|
|Paso 6°|rutear|
|Paso 7°|Adornar|

*Quizas tenga que crear/descargar mis huellas*

![simbolo](./imagenes/simbolo.png)
A=todos los componentes

como editar hoja=doble click en viñeta

c_p =polaridad

**NE555P**

kicanvas
Footprint(videos)

R=6.3mm (lo que mas usamos de resistencia)

capacitor THT
c= Disc D 3.8mm
w= ancho P=2.5 mm
(no polarizado)

Catalogo= Vishay.com

(victroncs.cl)

SIEMPRE
R_axial_L6.3mm_D2.5mm_P
          |      |
        largo   Fijo
Pitch= Distancia entre patas
(puede variar)

polarizados 
5x11x2.5mm
D.ALTO.P
D0.5

LED=D 5.0MM

ALT + 3= VISIOR 3D

Capa contorno=Edge.cuts

| Componente | Huella KiCad | Uso típico |
|---|---|---|
| Resistencia | `Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal` | Resistencias through-hole |
| Potenciómetro horizontal | `Potentiometer_THT:Potentiometer_Alps_RK163_Single_Horizontal` | Potenciómetro de panel |
| Potenciómetro vertical | `Potentiometer_THT:Potentiometer_WH148_Vertical` | Potenciómetro típico de audio |
| Potenciómetro logarítmico | `Potentiometer_THT:Potentiometer_WH148_Vertical` | Control de volumen/audio |
| Capacitor cerámico | `Capacitor_THT:C_Disc_D5.0mm_W2.5mm_P5.00mm` | Capacitores no polarizados |
| Capacitor electrolítico pequeño | `Capacitor_THT:CP_Radial_D5.0mm_P2.50mm` | Capacitores polarizados |
| Capacitor electrolítico mediano | `Capacitor_THT:CP_Radial_D6.3mm_P2.50mm` | Capacitores polarizados grandes |
| LED 5 mm | `LED_THT:LED_D5.0mm` | LEDs estándar |
| Integrado DIP-8 | `Package_DIP:DIP-8_W7.62mm` | NE555, LM386, etc. |
| CD4017 | `Package_DIP:DIP-16_W7.62mm` | Contador decimal 4017 |
| Bornera 2 pines | `TerminalBlock:TerminalBlock_bornier-2_P5.08mm` | Conexión de parlante o alimentación |
| Header 2 pines | `Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical` | Conexiones simples |
| Header 1 pin | `Connector_PinHeader_2.54mm:PinHeader_1x01_P2.54mm_Vertical` | Entrada o señal individual |
| Header 4 pines | `Connector_PinHeader_2.54mm:PinHeader_1x04_P2.54mm_Vertical` | Salidas Step1-Step4 |
