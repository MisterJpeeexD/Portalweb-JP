# Responsive Web CV 📄💼

Estructura de currículum profesional adaptada a la web, diseñada bajo un enfoque de arquitectura limpia y estructuración de datos semántica. Este proyecto consolida las capacidades de maquetación avanzada mediante el uso de layouts asimétricos y componentes gráficos dinámicos con CSS puro.

---

### 📋 Características Técnicas de Arquitectura

- **Layout Asimétrico (Grid de Dos Columnas):** Implementación de una estructura dividida mediante contenedores independientes (`<aside>` para datos duros/perfil y `<section>` para bloques cronológicos), asegurando un flujo de lectura óptimo y un diseño balanceado.
- **Barras de Progreso Gráficas (CSS Pure Elements):** Sustitución de componentes de texto por elementos gráficos encapsulados. Utiliza contenedores elásticos (`.progress-bar`) con rellenos dinámicos basados en porcentajes (`width`) y optimizados visualmente mediante gradientes lineales complejos (`linear-gradient`).
- **Línea de Tiempo Estructurada:** Maquetación cronológica uniforme mediante clases reutilizables (`.timeline-item`) que separan estrictamente los selectores temporales de las descripciones de cargo, facilitando el escaneo visual.
- **Tipografía y Normalización:** Control total del modelo de caja (`box-sizing: border-box`) y uso de variables CSS (`:root`) para centralizar la paleta de colores y simplificar el mantenimiento del código.

---

### 📂 Estructura del Proyecto

```text
├── index.html   # Estructura semántica (Estructuración de Perfil, Proyectos, Educación y Experiencia)
├── style.css    # Normalización, variables de entorno, maquetación Grid/Flexbox y lógica de barras
└── img/         # Recursos estáticos de identidad visual (Foto de perfil, códigos QR, etc.)