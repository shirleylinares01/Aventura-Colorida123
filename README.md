# Fase-No.4
# Mi Videojuego en Python

# Descripción del proyecto

Este proyecto consiste en la creación de un videojuego sencillo desarrollado en Python utilizando programación orientada a objetos.

El videojuego cuenta con un menú principal desde donde el jugador puede iniciar una partida, consultar los ajustes, ver los créditos o salir del juego.

El objetivo principal es demostrar el uso de clases, objetos, herencia y polimorfismo en Python.

---

# Objetivo

Crear un videojuego funcional utilizando los conocimientos adquiridos durante las diferentes fases del proyecto.

El programa permite al usuario interactuar mediante un menú y responder preguntas para obtener puntos.

---

# ¿Cómo se juega?

Al iniciar el programa aparecerá el menú principal:

1. Jugar
2. Ajustes
3. Créditos
4. Salir

# Opción 1: Jugar

El jugador debe responder una pregunta matemática:

**¿Cuánto es 2 + 2?**

Si la respuesta es correcta, obtiene:

**+100 puntos**

Si la respuesta es incorrecta, no obtiene puntos.

# Opción 2: Ajustes

Muestra la configuración actual del videojuego:

- Sonido: Activado
- Gráficos: Medios

# Opción 3: Créditos

Muestra información sobre la creación del videojuego.

# Opción 4: Salir

El programa solicita confirmar la salida.

Si el jugador responde "s", aparece:

**¡Hasta pronto! Gracias por jugar a mi videojuego.**

---

# Programación orientada a objetos

En este proyecto se utilizaron diferentes conceptos de programación orientada a objetos.

# Clase padre

La clase `Juego` funciona como clase padre o superclase.

Contiene:

- Puntos
- Nivel
- Método `jugar()`

# Herencia

La clase `Menu` hereda de `Juego`.

También las clases:

- `Jugar`
- `Ajustes`
- `Creditos`

heredan de `Menu`.

# Polimorfismo

El método `jugar()` se redefine en las diferentes clases.

Cada clase utiliza el método de una manera diferente.

Por ejemplo:

- `Jugar` inicia una partida.
- `Ajustes` muestra las configuraciones.
- `Creditos` muestra los créditos.

---

# Tecnologías utilizadas

- Python
- Programación Orientada a Objetos
- GitHub
- Consola de Python

---

# Estructura del proyecto

```text
Mi-Videojuego-Python/
│
├── README.md
│
├── videojuego.py
│
└── evidencias/
    ├── menu.png


# Fase 1- Análisis
En esta fase se identificó la idea principal del videojuego, su objetivo, funcionamiento y características.

# Fase 2- Diseño
Se diseñó la estructura del videojuego, incluyendo las clases, el menú y las diferentes opciones.

# Fase 3- Desarrollo
Se programó el videojuego utilizando Python y programación orientada a objetos.

Se implementaron:

Clases
Objetos
Herencia
Polimorfismo
Menú
Sistema de puntos
Entrada de datos
Control de errores

# Fase 4- Presentación
Finalmente, el proyecto se presenta mediante GitHub.

Se incluyen:

Código fuente
README
Evidencias del funcionamiento
Organización de las diferentes fases del proyecto




    ├── partida.png
    ├── ajustes.png
    └── creditos.png
