# Perfil de Usuario - Portafolio HTML y CSS

## Descripción
Este proyecto es una página web estática que muestra una tarjeta de perfil de usuario con un diseño moderno y atractivo, creada para demostrar mis habilidades en **HTML5** y **CSS3** como parte de mi portafolio profesional. La página presenta información personal (nombre, correo, ciudad) y métricas sociales (seguidores, publicaciones, "me gusta") en un formato inspirado en perfiles de redes sociales. Con un diseño responsivo, efectos visuales elegantes y un esquema de colores en tonos rosa, este proyecto refleja mi capacidad para construir interfaces limpias, funcionales y visualmente atractivas, ideal para mi búsqueda de un primer empleo como desarrollador frontend.

## Objetivo
Desarrollé este proyecto para:
- Exhibir mi dominio de **HTML semántico** y **CSS avanzado** (flexbox, animaciones, diseño responsivo).
- Demostrar mi atención al detalle en la creación de interfaces de usuario atractivas y accesibles.
- Construir una pieza de portafolio que muestre a posibles empleadores mi preparación para contribuir en proyectos de desarrollo web.

## Características
- **Diseño responsivo**: Adaptado a dispositivos móviles y de escritorio mediante unidades relativas y flexbox.
- **Estilo visual moderno**: Fondo rosa (#E57C92), tarjeta blanca con sombra (#E95270), bordes redondeados y efectos hover interactivos.
- **HTML semántico**: Estructura clara y bien organizada para mejorar la accesibilidad y el SEO.
- **CSS modular**: Estilos organizados para facilitar el mantenimiento y la escalabilidad.
- **Personalizable**: Fácil de adaptar para otros perfiles modificando el contenido en `index.html` o los estilos en `style.css`.
- **Alojado en GitHub Pages**: Desplegado para acceso público y demostración en tiempo real.

## Tecnologías utilizadas
- **HTML5**: Estructura semántica para un código limpio y accesible.
- **CSS3**: Diseño responsivo, flexbox, transiciones hover, sombras y bordes redondeados.
- **Google Fonts**: Fuente `Montserrat` para un estilo tipográfico profesional.

## Instalación
Para explorar o personalizar el proyecto localmente, sigue estos pasos:

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/<tu-usuario>/<nombre-repositorio>.git
   ```
   Reemplaza `<tu-usuario>` y `<nombre-repositorio>` con los detalles de tu repositorio (por ejemplo, `<tu-usuario>.github.io`).

2. **Navega al directorio del proyecto**:
   ```bash
   cd <nombre-repositorio>
   ```

3. **Asegúrate de tener los archivos necesarios**:
   - `index.html`: Estructura HTML del perfil.
   - `style.css`: Estilos CSS del diseño.
   - (Opcional) Una imagen de perfil para `.user__img`.

4. **Abre el proyecto localmente**:
   - Abre `index.html` en un navegador para previsualizar, o usa un servidor local:
     ```bash
     python -m http.server 8000
     ```
     Visita `http://localhost:8000` en tu navegador.

## Uso
1. **Personaliza el contenido**:
   - Edita `index.html` para actualizar el nombre (`JesusBustos77`), correo (`@gmail.com`), ciudad (`Ciudad de Cordoba`), y métricas (`17k` seguidores, `1.5k` posts, `68k` me gusta).
   - Añade una imagen de perfil en `.user__container-img`, por ejemplo:
     ```html
     <div class="user__container-img">
         <img src="ruta/a/tu/imagen.jpg" class="user__img" alt="Foto de perfil">
     </div>
     ```

2. **Personaliza los estilos**:
   - Modifica `style.css` para cambiar colores (por ejemplo, `#E57C92` para el fondo o `#E95270` para la tarjeta), fuentes, o márgenes.

3. **Despliega en GitHub Pages**:
   - Sube los archivos al repositorio:
     ```bash
     git add index.html style.css
     git commit -m "Añade tarjeta de perfil para GitHub Pages"
     git push origin main
     ```
   - Habilita GitHub Pages:
     - Ve a tu repositorio en GitHub.
     - Navega a **Settings > Pages**.
     - En **Build and deployment**, selecciona **Deploy from a branch**, elige la rama `main` y la carpeta `/ (root)`.
     - Haz clic en **Save**.
   - El sitio estará disponible en `https://<tu-usuario>.github.io` o `https://<tu-usuario>.github.io/<nombre-repositorio>`.

4. **Desactiva Jekyll (recomendado)**:
   - Crea un archivo `.nojekyll` para evitar el procesamiento de Jekyll:
     ```bash
     touch .nojekyll
     git add .nojekyll
     git commit -m "Desactiva Jekyll"
     git push origin main
     ```

## Estructura del proyecto
```
<nombre-repositorio>/
├── index.html        # Estructura HTML de la tarjeta de perfil
├── style.css         # Estilos CSS del diseño
└── README.md         # Documentación del proyecto
```

## Habilidades demostradas
Este proyecto destaca las siguientes competencias técnicas:
- **HTML5**: Uso de elementos semánticos (`div`, `img`, `section`) para una estructura clara y accesible.
- **CSS3**: Implementación de flexbox para diseños responsivos, transiciones hover, sombras, bordes redondeados y tipografía personalizada.
- **Diseño visual**: Creación de una interfaz atractiva con un esquema de colores coherente y efectos modernos.
- **Control de versiones**: Uso de Git y GitHub para gestionar el código.
- **Despliegue web**: Configuración de GitHub Pages para alojamiento público.

## Notas para empleadores
Este proyecto es una muestra de mi capacidad para:
- Diseñar y desarrollar interfaces de usuario desde cero usando HTML y CSS.
- Aplicar principios de diseño responsivo y accesibilidad.
- Gestionar proyectos de desarrollo web de manera organizada y eficiente.
Estoy entusiasmado por aplicar estas habilidades en un entorno profesional y contribuir al éxito de su equipo. Si desea discutir mi experiencia o explorar otros proyectos de mi portafolio, contácteme a través de los detalles proporcionados abajo.

## Contribuir
Si deseas sugerir mejoras:
1. Haz un fork del repositorio.
2. Crea una rama para tus cambios:
   ```bash
   git checkout -b mi-rama
   ```
3. Realiza tus cambios y haz commit:
   ```bash
   git commit -m "Descripción de los cambios"
   ```
4. Sube los cambios a tu fork:
   ```bash
   git push origin mi-rama
   ```
5. Crea un Pull Request en GitHub.

## Licencia
Este proyecto está bajo la [Licencia MIT](LICENSE). Siéntete libre de usarlo como referencia o adaptarlo.

## Contacto
- **Correo**: [tu-correo@ejemplo.com](mailto:tu-correo@ejemplo.com) (reemplaza con tu correo real)
- **GitHub**: [github.com/<tu-usuario>](https://github.com/<tu-usuario>) (reemplaza con tu perfil)
- **Sitio del proyecto**: (Añade la URL de GitHub Pages una vez desplegado, por ejemplo, `https://<tu-usuario>.github.io`)

---

**¡Gracias por revisar mi trabajo!** Estoy emocionado por la oportunidad de iniciar mi carrera como desarrollador frontend.