# Oscar Mauricio Kreszczuk

Estudiante avanzado de la Licenciatura en Ciencia de Datos en la Universidad Nacional de San Martín (UNSAM). Mi enfoque está orientado al desarrollo de software fuertemente tipado, la optimización de arquitecturas de bases de datos y el modelado analítico y probabilístico.

---

## Proyectos Destacados

### [CotizAR - Backend de Instrumentos Financieros](https://github.com/MauricioKreszczuk/CotizAR-TPI-Programacion-2)
* **Descripción:** API REST funcional diseñada para la extracción, persistencia y exposición de cotizaciones de activos del mercado argentino en tiempo real.
* **Componentes clave:** Módulo de web scraping automatizado para ingesta de datos crudos (bonos, letras, plazos fijos, dólares y bandas cambiarias), subsistema de autenticación de usuarios y arquitectura orientada a eventos para alertas de variaciones.
* **Stack:** Python, FastAPI, Docker, PostgreSQL, Contenedores listos para despliegue en Render.

### [Simpsons Bounding-Box Localizer & Classifier — Modelo Multi-Output](https://github.com/MauricioKreszczuk/simpsons-computer-vision)
* **Descripción:** Diseño e implementación de una arquitectura de red neuronal convolucional *multi-output* para realizar simultáneamente tareas de clasificación y localización espacial (*bounding boxes*) de objetos en imágenes complejas[cite: 2].
* **Componentes clave:** Uso de *Transfer Learning* (`MobileNetV2` congelada como extractor de características abstractas) acoplado a una función de pérdida ponderada personalizada ($\text{Loss}_{\text{Total}} = 1.0 \cdot \text{Loss}_{\text{Clase}} + 2.0 \cdot \text{Loss}_{\text{Caja}}$) para equilibrar la convergencia de variables continuas y discretas[cite: 2]. Tratamiento, balanceo y estratificación de un dataset con alta proximidad cromática y ruido visual de fondo[cite: 2].
* **Stack:** Python, TensorFlow, Keras, OpenCV (cv2), Scikit-Learn[cite: 1].

### [Java DataFrame Engine](https://github.com/MauricioKreszczuk/Estructura-Tabular-en-Java-TPI-Algoritmos-1)
* **Descripción:** Diseño e implementación integral desde cero de una biblioteca nativa para la manipulación, filtrado y limpieza de estructuras de datos tabulares bidimensionales sin dependencias externas.
* **Componentes clave:** Uso estricto de genéricos y polimorfismo para modelar columnas fuertemente tipadas, tratamiento preciso de datos faltantes (*Missing Data*), motores de inferencia para parseo de archivos CSV y algoritmos de imputación dinámica.
* **Stack:** Java, Programación Orientada a Objetos, Control Avanzado de Excepciones.

### Agrotech (En desarrollo)
* **Descripción:** Diseño de arquitectura de software y modelado conceptual orientado a la optimización de métricas de rendimiento y gestión de datos agrícolas.
* **Componentes clave:** Planificación de un sistema de almacenamiento híbrido avanzado que combina bases de datos relacionales estructuradas para consistencia crítica y esquemas NoSQL (documentales y en memoria) para lecturas de baja latencia.
* **Stack proyectado:** Python, SQL, MongoDB, Redis, Arquitectura de Software.

---

## Prácticas Académicas y Laboratorios

* **[Inferencia y Modelado Estadístico Avanzado](https://github.com/MauricioKreszczuk/estadistica-inferencia-1-practicas):** Repositorio analítico enfocado en simulaciones numéricas, estimación de parámetros (frecuentista), diagnóstico de multicolinealidad en regresión múltiple y modelado probabilístico bajo el paradigma bayesiano (Prior Predictiva y Likelihood) usando `scipy.stats` y `matplotlib`.
* **[Patrones de Diseño de Software](https://github.com/MauricioKreszczuk/design-patterns-python):** Suite de laboratorios enfocada en la implementación de patrones de arquitectura (*Factory Method, Abstract Factory, Decorator, Observer*) bajo principios SOLID, optimizando el desacoplamiento mediante composición y migración de modelos de comunicación de estado (Push a Pull).
* **[Procesamiento Digital de Imágenes](https://github.com/MauricioKreszczuk/practicas-vision-por-computadora):** Ejercicios de exploración base, transformaciones matriciales de color y análisis de canales de imágenes utilizando `OpenCV` y computación científica en cuadernos de Jupyter.

---

## Tecnologías y Herramientas

* **Lenguajes:** Python, Java, SQL, R.
* **Bases de Datos & Cloud:** PostgreSQL, MySQL, MongoDB, Redis, Supabase, Google Cloud Platform (GCP).
* **Data Science & ML:** Pandas, NumPy, Scikit-learn, SciPy, ArviZ, OpenCV (cv2).
* **Herramientas de Desarrollo:** Git, GitHub, Docker, VS Code, Jupyter Notebooks.

---
[LinkedIn](https://linkedin.com/in/mauricio-kreszczuk)
