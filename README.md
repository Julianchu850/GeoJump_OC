# 🚀 Geometry Jump (GeoJump OC)

**Geometry Jump** es un juego de plataformas estilo _endless runner_ de ritmo rápido, desarrollado en el lenguaje **Jack** para la arquitectura de computadores Hack (Nand2Tetris). El juego está inspirado en el clásico _Geometry Dash_.

---

## 🕹️ Descripción y Mecánicas del Juego

**Concepto:** Controla un cubo geométrico que se desplaza automáticamente hacia la derecha. El objetivo es evitar obstáculos por tiempo indefinido, acumulando puntaje.

### 🎮 Controles

| Tecla | Acción | Nota |
| :--- | :--- | :--- |
| **ESPACIO / Flecha Arriba (↑)** | Saltar | Mecánica principal de evasión. |
| **Flecha Abajo (↓)** | Invertir Gravedad | Solo funciona cuando el cubo no está en el suelo ni en el techo. |
| **Flechas Izq/Der** | Ajustar Salto | Permite aumentar o disminuir la potencia del salto. |
| **Dígitos (0–9)** | Ajustar Velocidad | Cambia la velocidad general del juego. |
| **Q** | Salir del Juego | Cierra la sesión de juego actual. |

### ⚙️ Mecánicas Clave

- **Inversión de Gravedad:** Permite cambiar la dirección de la gravedad en el aire, navegando también por la parte superior de la pantalla.
- **Obstáculos Duales:** Aparecen enemigos voladores (*Spaceships*) tanto arriba como abajo, exigiendo uso estratégico de la gravedad.
- **Blindaje de Memoria:** El código del cubo incluye límites para evitar saltos fuera de pantalla que puedan corromper memoria en Hack.

---

## 🛠️ Compilación y Ejecución (Nand2Tetris Tools)

Para compilar y ejecutar el juego, utiliza las herramientas oficiales de Nand2Tetris.

### 1️⃣ Compilación (Jack Compiler)

Asegúrate de que todos los archivos `.jack` del proyecto (`Cube.jack`, `GeometryGame.jack`, `Spaceship.jack`, etc.) estén en una única carpeta — por ejemplo: `GeoJump_OC`.

En la terminal, ejecuta:

```bash
JackCompiler.bat [NombreDeTuCarpeta]
```

Ejemplo:

```bash
JackCompiler.bat GeoJump_OC
```

**Resultado esperado:** Se generará un archivo `.vm` por cada archivo `.jack` dentro de la misma carpeta.

---

### 2️⃣ Ejecución en el VMEmulator

1. Abre el IDE de Nand2Tetris y ejecuta la herramienta **VM Emulator**.
2. Ve a **File → Load Program...**
3. Selecciona la carpeta donde se encuentran los archivos `.vm`.
4. Ajusta la velocidad del reloj si lo deseas.
5. Presiona **Run** (o `Ctrl + R`) para iniciar la pantalla de bienvenida.
6. Presiona cualquier tecla para comenzar la partida.


---

## Video Explicativo:
https://youtu.be/GjSy40RnPC8
