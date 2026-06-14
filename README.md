# 🤖 MOBILE ROBOTS LAB SESSIONS

Bienvenido al repositorio central de prácticas de Ingeniería de Electrónica, Robótica y Mecatrónica (Universidad de Málaga). Este repositorio sirve como índice general para acceder a los distintos repositorios desarrollados para la sección de Robots Móviles de la asignatura de Ampliación de Robótica. En estos proyectos se explora desde el control cinemático básico y la percepción del entorno mediante láser, hasta la planificación global de caminos en grafos y su integración con algoritmos de navegación local reactiva.

---

## 📚 Índice de Prácticas y Repositorios

A continuación se listan los repositorios que agrupan las diferentes sesiones de laboratorio. Cada uno contiene el código fuente, las instrucciones de ejecución y documentación detallada con el análisis teórico y los resultados experimentales.

### 1. [Prácticas 1, 2 y 3: Navegación y Percepción en ROS 2](https://github.com/rumonru05-byte/practicas_robots_moviles.git)
* **Descripción:** Implementación de nodos en ROS 2 (C++) para el control y la percepción de un robot móvil (Pioneer P3DX) en el simulador CoppeliaSim. Abarca el seguimiento de caminos explícitos, la navegación implícita por pasillos y la extracción geométrica del entorno a partir de datos láser.
* **Conceptos clave:** ROS 2 (Humble), CoppeliaSim, Control Cinemático Punto a Punto (P2P), Persecución Pura (Pure Pursuit), Regresión Lineal por Mínimos Cuadrados, Percepción Láser (LiDAR).

### 2. [Práctica 4: Navegación Local con Campos Potenciales](https://github.com/rumonru05-byte/nav_campos_potenciales.git)
* **Descripción:** Desarrollo en MATLAB de un módulo de navegación reactiva en tiempo real para la evasión de obstáculos. El robot se guía calculando fuerzas virtuales (atracción hacia el destino y repulsión de las paredes) basándose en las lecturas simuladas de sus sensores.
* **Conceptos clave:** Navegación Local, Campos Potenciales Artificiales, Sintonización de Parámetros ($\alpha$, $\beta$, $D$), Equilibrio de Fuerzas, Identificación de Mínimos Locales.

### 3. [Prácticas 5, 6 y 7: Planificación de Caminos y Navegación Autónoma](https://github.com/rumonru05-byte/planificacion_caminos.git)
* **Descripción:** Estudio e implementación en MATLAB de algoritmos de búsqueda en grafos para la planificación global de trayectorias. El proyecto culmina con la integración del planificador óptimo y el ejecutor local (Campos Potenciales) para lograr un sistema completo de navegación autónoma en mapas laberínticos.
* **Conceptos clave:** Búsqueda Desinformada (Dijkstra), Búsqueda Informada (A*), Admisibilidad y Consistencia Heurística, Distancia Euclídea, Grafos Asimétricos, Arquitectura de Integración Global-Local.

---

## 👨‍💻 Autor
**Rubén Montero Ruiz** *Universidad de Málaga (UMA)* | *[Enlace al perfil de GitHub](https://github.com/rumonru05-byte)*
