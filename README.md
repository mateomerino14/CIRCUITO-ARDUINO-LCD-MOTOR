==========CIRCUITO ARDUINO CON LCD Y MOTOR - PROTEUS==========

====DESCRIPCIÓN====
Circuito electrónico diseñado en **Proteus** que integra un microcontrolador (Arduino Nano), display LCD 16x2, y control de motor DC mediante transistor TIP41. 
Incluye múltiples componentes discretos y una extensa red de conexiones.

====COMPONENTES PRINCIPALES====

----Microcontrolador----
- Arduino Nano (o compatible)

----Display----
- LCD LM016L 16x2
- Potenciómetro para ajuste de contraste
- Resistencias de pull-up (1k)

----Control de Motor----
- Transistor TIP41 (NPN de potencia)
- Motor DC 12V (M1)
- Diodo 1N4004 (protección flyback)
- Resistencias de base (2k)

----Red de Componentes----
- R1, R2: 1k (pull-up LCD)
- R3-R6: 220R (limitadores de corriente)
- R7: 2k (base del transistor)
- Diodo D5: 1N4004
- Conexiones desde D13 hasta D993 (red extensa)

====FUNCIONALIDAD DEL CIRCUITO====

1. **Visualización**: LCD muestra información del sistema
2. **Control**: El microcontrolador gestiona la lógica
3. **Actuación**: Transistor TIP41 activa motor DC 12V
4. **Protección**: Diodo 1N4004 evita picos de tensión

====REQUISITOS PARA ABRIR====

- **Software**: Proteus 8 Professional o superior
- **Librerías**: Librerías de Arduino para Proteus
