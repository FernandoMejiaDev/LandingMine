![LandingMineLogo](https://github.com/FernandoMejiaDev/LandingMine/blob/main/ImageReadme/LandingMineLogo.webp)

# **LandingMine**

Catálogo de **19 landing pages** con temáticas variadas **(restaurantes, e-commerce, inmobiliarias, y más)**, diseñado para mostrar interfaces modernas y adaptadas a distintos tipos de negocio.

Ideal para reclutadores o clientes que buscan ver ejemplos reales de diseño profesional aplicado a distintos sectores.

## Tecnologías utilizadas

<div align="left">

![javascript](https://img.shields.io/static/v1?message=javascript&logo=javascript&label=&color=F7DF1E&logoColor=black&labelColor=&style=for-the-badge)
![react](https://img.shields.io/static/v1?message=react&logo=react&label=&color=61DAFB&logoColor=black&labelColor=&style=for-the-badge)
![tailwind](https://img.shields.io/static/v1?message=tailwindCSS&logo=tailwindcss&label=&color=06B6D4&logoColor=white&labelColor=&style=for-the-badge)
![vite](https://img.shields.io/static/v1?message=vite&logo=vite&label=&color=646CFF&logoColor=white&labelColor=&style=for-the-badge)
![pnpm](https://img.shields.io/static/v1?message=pnpm&logo=pnpm&label=&color=F69220&logoColor=white&labelColor=&style=for-the-badge)

</div>

 ## Instalación y Uso

Para ejecutar **LandingMine**, sigue estos pasos:

1. Clona el repositorio
2. Inicia el proyecto desde la terminal con
     ```
     npm start
## ¿Por qué usar npm start?
LandingMine está construido con **React**, un framework que requiere un entorno de desarrollo para compilar y ejecutar la aplicación correctamente.
El comando **npm start** ejecuta el servidor de desarrollo de React, permitiendo visualizar los cambios en tiempo real mientras trabajas en el proyecto.

## Interfaz y Características
Al ejecutar el proyecto, verás la página principal de LandingMine, donde encontrarás una colección de 18 landing pages de diferentes temáticas.

- 100% responsive y adaptadas a distintos dispositivos.
- Diseños modernos y optimizados con Tailwind CSS.
- Desarrolladas con React, lo que permite componentes reutilizables y mejor mantenimiento del código.
  
![imgN1](https://github.com/FernandoMejiaDev/LandingMine/blob/main/ImageReadme/imgReadmeN1.webp)

## Diseño y Temáticas de las Landing Pages  

Cada landing page en **LandingMine** está diseñada con una temática única y completamente **responsive**, adaptándose a distintos dispositivos y tamaños de pantalla.  
El objetivo principal es explorar y mejorar en **Front-End**, creando interfaces variadas que se ajusten a diferentes industrias y estilos visuales.  

Cada landing tiene su propio diseño y características especiales:  

- **Diseño personalizado:** Cada página sigue un estilo acorde a su temática.  
- **Modos de color:** Algunas incluyen **Dark Mode** para mejorar la experiencia visual.  
- **Interactividad:** Se han agregado **Interactividad a cada landing ** para hacerlas más dinámicas.  

Por ejemplo:  

### DreamHouse (Landing N°7) - *Inmobiliaria 
 Su diseño está inspirado en el sector inmobiliario, con un header atractivo y una paleta de colores sobria y elegante, con un paginación.  

### CastorBook (Landing N°17) - 📖 Librería y editorial 
 Esta landing incluye un efecto **hover** en los libros, simulando un estante donde al pasar el mouse se revela el contenido de cada uno y en cada tarjeta de libro abre un modal con la descripción de dicho libro.  

Cada una de estas páginas permite experimentar con distintos enfoques de diseño y **crear interfaces Front-End adaptadas a diversas necesidades**.  

![imgN2](https://github.com/FernandoMejiaDev/LandingMine/blob/main/ImageReadme/imgReadmeN2.webp)
![imgN3](https://github.com/FernandoMejiaDev/LandingMine/blob/main/ImageReadme/imgReadmeN3.webp)

## Organización del Proyecto  

Para mantener un código limpio y estructurado, cada landing page en **LandingMine** sigue una organización bien definida dentro de la carpeta `src`.  

## Estructura de archivos  

Dentro de **src**, encontrarás la carpeta **LandingPage,** donde cada landing está organizada en su propia carpeta. Además, hay carpetas de **componentes globales** y **hooks**:  

![imgN4](https://github.com/FernandoMejiaDev/LandingMine/blob/main/ImageReadme/imgReadmeN4.png)

- **LandingPage/** → Contiene todas las landing pages, cada una en su propia carpeta.  
- **GlobalComponents/** → Contiene componentes reutilizables como `DarkMode` y `MenuMovile`.  

Cada landing tiene su estructura específica para facilitar su mantenimiento y escalabilidad.  

## Estructura de una Landing Page  

Todas las landing pages del proyecto adoptan una estructura modular y organizada, lo que facilita su mantenimiento y escalabilidad. Cada landing sigue esta estructura de carpetas:

![imgN5](https://github.com/FernandoMejiaDev/LandingMine/blob/main/ImageReadme/imgReadmeN5.png)

   ```
/LandingPage
│── /components
│   │── /layout       # Estructura base: Header, Main y Footer
│   │   ├── Header.jsx
│   │   ├── Main.jsx
│   │   ├── Footer.jsx
│   │── /ui           # Componentes reutilizables (botones, tarjetas, etc.)
│   │── /sections     # Secciones completas del contenido de la página
│── /pages
│   └── Home.jsx      # Página principal que renderiza toda la landing
│── /assets           # Imágenes, íconos, fuentes, etc.
```

###  Descripción rápida

1. `layout/`: Contiene la estructura principal de la página (cabecera, contenido y pie).
2. `sections/`: Cada sección de contenido está separada como componente independiente. Esto permite:
   - Agregar, quitar o reorganizar secciones fácilmente.
   - Reutilizar secciones entre diferentes landings.
3. `ui/`: Elementos pequeños y reutilizables como botones, íconos, etc.
4. `pages/`: Componente principal que arma la página `(Home.jsx)`.
5. `assets/`: Archivos estáticos como imágenes, íconos, logos, fuentes personalizadas, etc.


## Conexión con App.js
El archivo `App.js` es el que maneja la navegación entre las landing pages.

- **Cada landing está registrada con una ruta usando su nombre en la URL.**
- **Las rutas están organizadas con comentarios para facilitar su lectura.**

![imgN6](https://github.com/FernandoMejiaDev/LandingMine/blob/main/ImageReadme/imgReadmeN6.png)


### Componentes Globales
Dentro de la carpeta LandingPages, hay una subcarpeta llamada GlobalComponents. Aquí se encuentran componentes que son utilizados en todas las landing pages del proyecto.

Estos componentes tienen una lógica simple pero útil para mejorar la experiencia del usuario y la personalización del diseño en cada landing.

### DarkMode.jsx
Este archivo contiene la lógica que permite cambiar entre el modo claro y oscuro en las landing pages. Con este componente, los usuarios pueden alternar entre ambos modos sin afectar la estructura del sitio.

![imgN7](https://github.com/FernandoMejiaDev/LandingMine/blob/main/ImageReadme/imgReadmeN7.png)

### MobileMenu.jsx
Este componente maneja el menú móvil, que aparece en pantallas menores a md (768px en Tailwind CSS). Sin embargo, dado que cada landing page tiene un diseño y una combinación de colores distinta, no se puede definir un color único para todos los menús.

![imgN8](https://github.com/FernandoMejiaDev/LandingMine/blob/main/ImageReadme/imgReadmeN8.png)

Para solucionar esto, MobileMenu.jsx permite personalizar ciertos estilos a través de propiedades dinámicas. Cada landing puede ajustar estos valores para que el menú encaje perfectamente con su diseño.

Por ejemplo, en la landing **CampingNight**, se llama al componente **MobileMenu** con propiedades específicas para modificar colores y efectos:

![imgN9](https://github.com/FernandoMejiaDev/LandingMine/blob/main/ImageReadme/imgReadmeN9.png)

Estas propiedades permiten que el menú:
- **Tenga colores adaptados al diseño de cada landing.**
- **Mantenga una buena visibilidad sin importar el fondo de la página.**
- **Se integre de forma fluida con la experiencia del usuario.**

Gracias a esta estructura, cada landing page tiene su propio estilo sin perder consistencia en la navegación y funcionalidad.

---
