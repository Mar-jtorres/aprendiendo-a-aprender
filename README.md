*Empezamos con este proyecto de apoyo adicional, con el motivo de crear portafolio y pulir mi habilidad como desarrolladora web*
MARKDOWN:
# 📌 Aprendiendo a Aprender
Landing page educativa sobre técnicas de aprendizaje eficiente, inspirada en métodos como la Técnica Feynman y los principios de Josh Kaufman. El objetivo es presentar información clara y atractiva sobre cómo aprender mejor, utilizando un diseño moderno y estructurado. Se desarrolló con HTML5 y CSS3, aplicando la metodología BEM para mantener el código organizado y escalable.

---

## 🚀 Tecnologías utilizadas
- **HTML5**
- **CSS3 / Flexbox / Grid**
- **Metodología BEM**
- **JavaScript** (si aplica)
- **Git / GitHub**

---

## ✨ Características destacadas
-- Header hero con título grande, subtítulo y enlace CTA, superpuesto sobre imagen ilustrativa y elemento decorativo cuadrado.
--Sección de descripción con layout de dos columnas usando Flexbox, incluyendo texto acentuado y párrafos jerárquicos.
--Sección Feynman con imagen posicionada absolutamente en la esquina inferior, título oversized y enlace flotante para más info.
--Sección Kaufman en tema oscuro con grid de 5 columnas para principios, triángulo decorativo y z-index para superposiciones.
--Footer responsive con tres columnas: logo/copyright, enlaces de navegación y íconos sociales SVG con hover interactivo  

---

## 🏆 Retos superados
- Desafío técnico #1 (superposición en footer): Se corrigió el posicionamiento del logo reutilizado del header (de absolute a static) y se agregó margen inferior para separar del texto de copyright, evitando que el author se pegara al logo.  
- Desafío técnico #2 (imagen flotante en Feynman): Se ajustó el posicionamiento absolute con coordenadas bottom/left y se controló la altura del contenedor con min-height y justify-content para eliminar el "padding invisible" causado por flex y márgenes. 
- Desafío técnico #3 (estructura BEM en footer): Se implementaron clases correctas para contenedores sociales (footer__social-icons), enlaces (footer__social-icon) e imágenes (footer__social-icon-img), con flex para alinear íconos y texto, y gap para espaciado consistente.

---

## 💡 Planes de mejora
🔹 Agregar gradientes sutiles en el header y secciones (ej. de #f2f2f2 a un azul claro) para profundidad visual, usando linear-gradient en fondos y mejorando la transición entre secciones claras y oscuras.
🔹 Implementar sombras suaves (box-shadow) en tarjetas de la sección table/grid y en el footer para dar sensación de elevación, como box-shadow: 0 4px 8px rgba(0,0,0,0.1), haciendo el diseño más moderno y menos plano.
🔹 Incorporar animaciones CSS en elementos interactivos, como fade-in al scroll para la imagen de Feynman o scale en hover para íconos sociales, usando @keyframes y transform para mayor dinamismo sin sobrecargar el rendimiento.  
🔹 Hacerlo totalmente responsive y adaptable para varios tamaños de pantalla, implementando media queries completas para móviles, tablets y desktops, ajustando grids, flex y posicionamientos absolutos para una experiencia fluida en todos los dispositivos.