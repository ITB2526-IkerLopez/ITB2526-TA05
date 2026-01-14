# Portafolio Profesional

![Estado del Proyecto](https://img.shields.io/badge/Estado-Terminado-green)
![Licencia](https://img.shields.io/badge/Licencia-MIT-blue)

Bienvenido al repositorio de mi portafolio profesional. Este proyecto ha sido desarrollado desde cero para presentar mis competencias en **Administración de Sistemas Informáticos en Red (ASIRC)**, Seguridad y Despliegue de Infraestructuras.

El objetivo principal de esta web es ofrecer una experiencia de usuario (UX) fluida, moderna y de alto rendimiento, evitando el uso de plantillas pesadas o frameworks innecesarios.

---

## Demo Online
Puedes visitar el portafolio en funcionamiento aquí:
🔗 **[Enlace a tu GitHub Pages o Dominio]** *(Configura esto en Settings > Pages)*

---

## Tecnologías Utilizadas

El proyecto está construido con un enfoque **"Vanilla"** (sin librerías externas pesadas) para garantizar la máxima velocidad de carga y control total del código.

* ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) **Semántico**: Estructura limpia y accesible.
* ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) **Moderno**: Uso de Flexbox, CSS Grid, variables y animaciones.
* ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) **Vanilla**: Lógica para el menú, scroll suave y visores de PDF.

---

## Características Principales

### 1. Diseño UI/UX "Dark Mode"
* Interfaz moderna basada en tonos oscuros (Slate/Navy) para reducir fatiga visual.
* Efecto **Glassmorphism** en el encabezado de navegación.
* Tipografía **Inter** para mejorar la legibilidad técnica.

### 2. Grid de Proyectos Interactivo
* **Estado Activo:** Los proyectos principales (Windows Server y Linux Monitorización) tienen efectos de *hover*, zoom y elevación.
* **Estado "Coming Soon":** Implementación de una clase CSS `.disabled` que aplica un filtro de escala de grises (`grayscale`) y desactiva eventos del puntero para indicar proyectos futuros.

### 3. Visor de Documentación Integrado
* Páginas de detalle con layout de doble columna.
* **Sticky PDF Viewer:** El visor de PDF se mantiene fijo en la pantalla mientras el usuario hace scroll por la descripción del proyecto, facilitando la lectura simultánea.

### 4. Navegación Dinámica
* Botón "Volver arriba" (Scroll to Top) con aparición condicional mediante JavaScript.
* Menú de navegación fijo con efecto de desenfoque (`backdrop-filter`).

---

## 📂 Estructura del Proyecto

```bash
├── 📁 assets/          # Imágenes y recursos gráficos
├── 📁 pdfs/            # Documentación técnica (Proyecto1.pdf, Proyecto2.pdf)
├── index.html          # Página principal (Landing Page)
├── index.css           # Hoja de estilos global
├── proyecto1.html      # Detalle: Infraestructura Windows Server
├── proyecto2.html      # Detalle: Monitorización Linux/Docker
├── proyectos.html      # Catálogo completo de proyectos
├── formulario.html     # Página de contacto
└── README.md           # Documentación del repositorio
