# Game Vault: Enciclopedia Digital de Plataformas de Videojuegos

## Descripción del Proyecto
Game Vault es una plataforma web estática desarrollada para servir como un archivo documental sobre las franquicias y personajes más icónicos de la industria de los videojuegos. El sistema organiza la información en torno a cuatro ecosistemas principales: Nintendo, SEGA, PlayStation y Xbox, proporcionando una interfaz temática que se adapta visualmente a la identidad de cada marca.

El proyecto pone énfasis en la navegación intuitiva y en la presentación de contenidos biográficos mediante una estructura técnica limpia y eficiente.

## Especificaciones Técnicas

### 1. Interfaz y Experiencia de Usuario (UI/UX)
* **Tematización Dinámica:** Implementación de selectores CSS específicos para cada marca, permitiendo cambios automáticos de paletas de colores, gradientes y efectos de iluminación (*glow effects*) según el contexto de la plataforma.
* **Navegación Fluida:** Uso de *Smooth Scrolling* para referencias internas y una jerarquía de navegación clara entre el índice global y las enciclopedias individuales.
* **Diseño Adaptable:** Desarrollo basado en principios de *Responsive Design*, asegurando la integridad del layout y la legibilidad de los textos en dispositivos móviles y de escritorio.

### 2. Desarrollo Frontend
* **Layout Engine:** Uso combinado de **CSS Grid** para la estructura principal y **Flexbox** para la alineación de elementos dinámicos y galerías de personajes.
* **Tipografía Técnica:** Integración de fuentes especializadas mediante Google Fonts para evocar distintas eras tecnológicas: *Orbitron* para encabezados futuristas, *Press Start 2P* para elementos retro y *Kanit* para lectura de cuerpo de texto.
* **Optimización de Contenido:** Superposición de capas de gradientes lineales sobre imágenes de fondo para garantizar un contraste de lectura óptimo (WCAG compliance) sin sacrificar la estética visual.

## Estructura del Software
El proyecto se organiza de forma modular para facilitar su mantenimiento:

* `index.html`: Dashboard principal y punto de acceso jerárquico.
* `nintendo.html`: Enciclopedia de personajes y mitología de Nintendo.
* `sega.html`: Enciclopedia de personajes y mitología de SEGA.
* `playstation.html`: Enciclopedia de personajes y mitología de PlayStation.
* `xbox.html`: Enciclopedia de personajes y mitología de Xbox.
* `styles.css`: Núcleo de estilos centralizado que gestiona la lógica visual y el diseño responsivo de toda la aplicación.

## Requisitos de Ejecución
Al ser una aplicación web estática, no requiere de un entorno de ejecución de servidor complejo. Puede ser visualizada directamente abriendo el archivo `index.html` en cualquier navegador moderno con soporte para estándares HTML5 y CSS3.
