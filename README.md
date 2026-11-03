<p align="center">
  <img src="./display.svg" alt="HOLA ORLANDO" width="100%">
</p>

```asm
.include "m328Pdef.inc"

; Orlando Jared Martínez García
; Ingeniería en Teleinformática · costa del Pacífico, México
; Lo construyo, lo rompo, y entiendo por qué se rompió.
```

### CONFIG:

```asm
.equ  LOW_LEVEL = "AVR Assembly · C/C++ · ATmega328p"
.equ  BACKEND   = "Java · Node.js · Express"
.equ  FRONTEND  = "JavaScript · HTML · CSS"
.equ  DATA      = "MongoDB · MySQL"
.equ  SYSTEMS   = "Linux · Git · Docker"
```

### INICIO:

```asm
INICIO:
    RCALL  VILLAS_CANGREJO
    RCALL  HOTEL_COSTA_ALEGRE
    RCALL  HOLA_ORLANDO
    RCALL  QR_ASISTENCIA
    RJMP   INICIO
```

| Rutina | Stack | Repo |
|---|---|---|
| `VILLAS_CANGREJO` | JavaScript · Node · Express · MongoDB | [ver](#) |
| `HOTEL_COSTA_ALEGRE` | HTML · CSS · JavaScript | [ver](#) |
| `HOLA_ORLANDO` | AVR Assembly · ATmega328p | [ver](#) |
| `QR_ASISTENCIA` | Java | [ver](#) |

### RETARDO:

```asm
RETARDO:
    ; Sistemas operativos · Redes inalámbricas · Docker · Bases de datos
    RET                          ; espera activa, pero con propósito
```

### FIN:

```asm
FIN:
    ;   LinkedIn → link
    ;   Correo   → orlandojamaga@outlook.com
    RET
```
