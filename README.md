Round Robin Scheduler — Java NetBeans
Descripción

Simulador del algoritmo de planificación Round Robin desarrollado en Java utilizando NetBeans IDE.
El proyecto permite administrar procesos mediante colas y ejecutar cada proceso según un Quantum definido, simulando el comportamiento de un sistema operativo en la asignación de CPU.

Características
Simulación completa del algoritmo Round Robin
Gestión dinámica de procesos
Configuración personalizada del Quantum
Interfaz gráfica desarrollada con Java Swing
Visualización de:
Tiempo de espera
Tiempo de retorno
Tiempo de ejecución
Estado de procesos
Cola de procesos en tiempo real
Ejecución paso a paso del scheduler
Tecnologías Utilizadas
Java
Java Swing
NetBeans IDE
Estructuras de datos (colas)
Funcionamiento del Algoritmo

El algoritmo Round Robin asigna un tiempo fijo de CPU llamado Quantum a cada proceso.

Si el proceso no termina durante ese tiempo:

Se pausa.
Vuelve al final de la cola.
El siguiente proceso toma la CPU.

Esto garantiza:

Equidad entre procesos
Mejor respuesta en sistemas multitarea
Evitar bloqueos por monopolio de CPU
Estructura del Proyecto
RoundRobin/
│
├── src/
│   ├── Main.java
│   ├── Scheduler.java
│   ├── Process.java
│   ├── Queue.java
│   └── UI/
│
├── build/
├── dist/
└── README.md
Instalación
1. Clonar el repositorio
git clone https://github.com/TU-USUARIO/round-robin-java.git
2. Abrir en NetBeans
Abrir NetBeans
File → Open Project
Seleccionar la carpeta del proyecto
3. Ejecutar

Presiona:

Shift + F6

o el botón Run Project.

Capturas del Proyecto

Aquí puedes agregar imágenes de:

Interfaz principal
Cola de procesos
Resultados de ejecución
Estadísticas del scheduler
Objetivo Académico

Este proyecto fue desarrollado con fines educativos para comprender:

Planificación de procesos
Manejo de CPU
Estructuras de colas
Algoritmos de sistemas operativos
Autor

Desarrollado por Sebastián
