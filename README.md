```asm
; ==============================================================
;  orlando.asm  ·  perfil de Orlando
;  Ingeniería en Teleinformática · costa del Pacífico, México
;  "Lo construyo, lo rompo, y entiendo por qué se rompió."
; ==============================================================

.include "m328Pdef.inc"          ; base: sistemas embebidos + web + redes
```

## CONFIG:

Lo que tengo cargado en la memoria.

```asm
.equ  LANG_MAIN    = "Java"
.equ  LANG_WEB     = "JavaScript · HTML · CSS"
.equ  LANG_LOW     = "AVR Assembly"        ; sí, a mano, sin abstracciones
.equ  BACKEND      = "Node.js · Express"
.equ  DATA         = "MongoDB · MySQL"
.equ  SYSTEMS      = "Linux · Git · Docker"
```

## INICIO:

Proyectos. Cada uno es una subrutina que se ejecuta en el orden de abajo.

```asm
INICIO:
    RCALL  VILLAS_CANGREJO       ; reservaciones full-stack, cuentas, panel admin
    RCALL  HOTEL_COSTA_ALEGRE    ; sitio responsivo con galería y validación de formularios
    RCALL  HOLA_ORLANDO          ; scroller de 7 segmentos en ATmega328p
    RCALL  QR_ASISTENCIA         ; registro de asistencia por código QR (Java)
    RJMP   INICIO                ; el ciclo nunca termina
```

| Rutina | Stack | Repo |
|---|---|---|
| VILLAS_CANGREJO | JavaScript · Node · Express · MongoDB | [link](#) |
| HOTEL_COSTA_ALEGRE | HTML · CSS · JavaScript | [link](#) |
| HOLA_ORLANDO | AVR Assembly · ATmega328p | [link](#) |
| QR_ASISTENCIA | Java | [link](#) |

## RETARDO:

Lo que todavía estoy en el ciclo de aprender. Espera activa, pero con propósito.

```asm
RETARDO:
    ; Java · Linux · Docker · Sistemas operativos · Bases de datos · Microcontroladores
    RET
```

## FIN:

```asm
FIN:
    ; Contacto
    ;   LinkedIn → link
    ;   Correo   → tu@correo.com
    RET
```

```asm
; fin del programa. hecho a mano, un ciclo a la vez.
```
