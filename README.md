# morena.dev - Sitio Web

Este proyecto es el sitio web profesional para **morena.dev**, creado por **Jesmar Rojas**. Sirve como un portafolio y punto de contacto para ofrecer servicios de desarrollo de software a medida para pequeños y medianos negocios.

El sitio está diseñado para ser rápido, seguro, visualmente atractivo (con un diseño premium oscuro y detalles en dorado) y muy directo: se enfoca en el **problema del cliente** y en la **solución aportada**, sin abrumar con detalles técnicos.

## 🚀 Características

- **Diseño Premium:** Interfaz oscura moderna (`#000000` y `#1b1b1d`) con acentos elegates en dorado (`#e2c373`).
- **Responsive:** Totalmente adaptable a dispositivos móviles, tablets y pantallas de escritorio. Menú hamburguesa interactivo.
- **Enfoque en el Negocio:** Textos orientados a resolver los problemas del día a día de los comercios (ventas, stock, turnos, reparaciones).
- **Ligero y Rápido:** Construido sin frameworks pesados, garantizando tiempos de carga casi instantáneos.
- **Ruteo Simple:** Navegación tradicional entre múltiples páginas HTML bien estructuradas.

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Estructura semántica.
- **CSS3 (Vanilla):** Estilos globales, variables CSS (`:root`), Flexbox y CSS Grid.
- **JavaScript (Vanilla):** Lógica mínima para el menú móvil móvil, animaciones de *scroll* (Intersection Observer) y actualización dinámica del pie de página.
- **Fuentes:** Inter (Google Fonts).

## 📂 Estructura del Proyecto

```text
/
├── index.html          # Página principal (Inicio, Servicios destacados)
├── proyectos.html      # Catálogo de proyectos detallados (Clean Master, BIKERLP, BROSS)
├── sobre-mi.html       # Presentación personal y filosofía de trabajo
├── contacto.html       # Información de contacto y formulario (mailto)
├── README.md           # Este archivo
├── css/
│   └── styles.css      # Hoja de estilos principal y única
├── js/
│   └── main.js         # Interacciones y animaciones
└── images/
    ├── icons/          # Favicon y otros íconos (icono.png)
    └── logo/           # Logotipo principal del sitio (logo.png)
```

## 💻 Cómo ver el sitio

No se requiere ningún tipo de instalación, servidor local, ni dependencias (como Node.js o Python). 

1. Clona o descarga el repositorio en tu computadora.
2. Navega a la carpeta principal del proyecto.
3. Haz **doble clic** en el archivo `index.html`.
4. El sitio se abrirá automáticamente en tu navegador web predeterminado (Chrome, Firefox, Edge, Safari, etc.).

## ✉️ Contacto y Formulario

Actualmente, el formulario en `contacto.html` funciona mediante el protocolo `mailto:`. Al completar los datos y presionar enviar, se abrirá el cliente de correo predeterminado del usuario (ej. Outlook, Mail de Windows, Gmail) con el cuerpo del mensaje pre-armado, listo para ser enviado a **rojasjesmar.jbs@outlook.com**.

## 🎨 Personalización y Futuro

- **Imágenes de Proyectos:** Actualmente los proyectos tienen "placeholders" (cajas con íconos). El siguiente paso natural es agregar fotos o capturas de pantalla reales de los sistemas en la carpeta `images/proyectos/` y actualizar las etiquetas `<img>` en `proyectos.html` y `index.html`.
- **Backend (Opcional):** Si en el futuro se desea evitar el cliente de correo del usuario, el formulario de contacto podría vincularse a un backend ligero (como Flask, FastAPI, o un servicio de formularios como Formspree).
