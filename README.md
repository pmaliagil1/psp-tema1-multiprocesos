# PSP · Multiprocesos y multihilos

Web interactiva para estudiar **Programación de Servicios y Procesos** (2.º DAM, IES Rafael Alberti).

## 👉 [Abrir la web](https://pmaliagil1.github.io/psp-tema1-multiprocesos/)

https://pmaliagil1.github.io/psp-tema1-multiprocesos/

## Ruta paso a paso (empieza aquí)

Once niveles para aprender PSP sin dominar Java antes. Cada nivel explica solo el Java que hace falta y trae un ejemplo comentado y cuatro ejercicios: ordenar líneas, rellenar huecos, cazar el fallo y escribir el programa entero (el "jefe" del nivel). Al final hay un simulacro de examen. Todos los ejemplos y soluciones se han compilado y ejecutado con JDK 21.

1. Tu primer proceso · 2. Un hijo escrito por ti · 3. Escucha al hijo · 4. Habla con el hijo · 5. Muchos hijos a la vez · 6. Vigila y corta · 7. Tu primer hilo · 8. Muchos hilos · 9. Datos compartidos (`synchronized`, `AtomicInteger`) · 10. Productor y consumidor (`wait`/`notifyAll`, `BlockingQueue`) · 11. Semáforos, pools e interbloqueo · Simulacro de examen.

Incluye un mapa de niveles con el progreso y un calendario hasta la prueba de la 1.ª evaluación.

## Tema 1 · Multiprocesos

- Programa, proceso, servicio e hilo · concurrente, paralela y distribuida (con CPU-bound / I/O-bound, paralelismo trivial y calculadora de la ley de Amdahl) · estados de un proceso · planificación de la CPU · procesos en Java · comunicar y controlar procesos (incluye lanzar varios hijos y contarlos con `children()`).
- Simulador de diagramas de Gantt (FCFS, SJF y Round Robin con llegadas) con modo práctica, incluido el ejercicio 4 del boletín.
- Comprobador de transiciones entre estados y lista de requisitos de la práctica final (el lanzador de tareas).

## Tema 2 · Multihilos

- Proceso frente a hilo · crear hilos (`Thread`, `Runnable`, lambda, `start` frente a `run`) · ciclo de vida (`Thread.State`) · controlar hilos (`join`, `sleep`, `interrupt`, demonios) · hilos virtuales de Java 21.
- Ejercicio para predecir estados, ejercicios de código (cocina con tres cocineros, cronómetro con Enter, cancelar descargas a los 3 s) y simulador del gestor de descargas paso a paso.

Todo tiene tests con corrección al momento. Funciona en el navegador, sin instalar nada, y el progreso se guarda en el navegador que uses.
