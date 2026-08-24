# Portfolio Personal — Julián Piedrabuena

Landing de portafolio personal desarrollada para la PFO1 de **Desarrollo de Sistemas Web · Front End** (2do cuatrimestre 2026).

## 🔗 Enlaces

- **Demo en vivo (Vercel):** _pendiente de publicar_
- **Perfil de GitHub:** [github.com/juliganSW](https://github.com/juliganSW)

## 📄 Descripción

Landing responsive de una sola página que presenta mi perfil como desarrollador: quién soy, mi formación y experiencia, mi stack tecnológico, algunos proyectos propios y una vía de contacto. Desarrollada con HTML semántico y CSS puro, con foco en un diseño oscuro, minimalista y con detalles de animación sutiles.
**Aclaración:** En la sección Experiencia existe información ficticia.

## 🛠️ Tecnologías utilizadas

- HTML5 semántico
- CSS3 (Flexbox y Grid)
- Google Fonts (Poppins)
- [Devicon](https://devicon.dev) para los íconos de tecnologías a color
- [Font Awesome](https://fontawesome.com) para íconos de redes sociales y UI

## 🎨 Decisiones de diseño

- **Paleta oscura** (`#081b29` de fondo, `#39f2ae` como color de acento) para un estilo moderno tipo "developer portfolio".
- **Grid** en la sección Home para dividir texto e imagen en dos columnas, con reordenamiento a una columna en mobile.
- **Carrusel de proyectos**: implementado con el truco de `radio inputs` ocultos + selectores `:checked` en CSS puro.
- **Efecto de tipeo** en el título principal (`steps()` + `@keyframes`), desactivado en dispositivos pequeños ya que la técnica no permite hacer wrap de línea de forma prolija.
- **Sección de Skills** con cards agrupadas por Frontend/Backend, usando los íconos de Devicon, para un estilo más visual.
- **Responsive** con breakpoints en 1200px, 991px, 768px, 520px y 371px, ajustando tipografía, layout de grid/flex y tamaños de componentes (incluyendo el carrusel, cuyos controles prev/next se ocultan en mobile).

## 🖼️ Uso de imágenes

- La imagen de la sección Home fue tomada del sitio **unDraw**.
- Las imágenes del carrusel de "Proyectos" son capturas propias de mis proyectos personales, enmarcadas con [shots.so](https://shots.so) para darles un estilo de mockup de navegador.


## 🤖 Declaración de uso de IA

- **Herramienta utilizada:** Claude (Anthropic), plan gratuito.
- **Para qué la usé:** asistencia en la corrección y escritura de bloques de HTML/CSS puntuales (grid del home, modificaciones del carrusel, media queries responsive, efecto de sombras), y detalles visuales en este README, como la incorporacion de los emojis de Unicode. 
- **Experiencia previa:** ya había usado IA (Claude u otras) anteriormente, con algo de experiencia previa en su uso para tareas de desarrollo y programación.
- **Lo que revisé/adapté con criterio propio:** cada bloque sugerido fue probado e integrado a mano en mi propio código; corregí bugs que la IA no detectó a la primera (por ejemplo, IDs duplicados en los inputs del formulario de contacto que rompían la asociación con sus `label`), ajusté nombres y uso de clases, colores, y definí yo mismo el criterio de diseño general (paleta, estructura de secciones, qué proyectos mostrar).
