# Guía Cuzco

Guía Cuzco es una página web informativa y dinámica hecha en **HTML**, **Bootstrap 5** y **JavaScript propio**. El sitio muestra contenido sobre Cuzco: sitios turísticos, platos típicos, historia, cultura y una sección visual para publicar reseñas.

Toda la aplicación funciona dentro de un solo archivo **index.html** que carga el contenido de las secciones de forma dinámica usando JavaScript.

---

## ✨ Características principales

- **Sidebar fijo** con navegación entre secciones.
- **Contenido dinámico:** el JavaScript inserta cada página (Inicio, Sitios, Platos, Historia, Reseñas) dentro del `<main>`.
- **Modales funcionales:**  
  - Iniciar sesión  
  - Crear cuenta  
  - Editar perfil  
  - Cambiar contraseña  
  - Escribir reseñas  
- **Sistema básico de usuario (sin backend):**  
  - Registro  
  - Login visual  
  - Edición de perfil y foto  
  - Estado persistente en la interfaz  
- **Publicación de reseñas dentro de la página.**
- **Modo oscuro (título + switch, actualmente activado pero marcado como función no final).**
- **Bootstrap Icons** para iconografía limpia.
- **Uso de imágenes y secciones completas con información, tarjetas, sliders y contenido educativo.**

---

## 🛠 Tecnologías utilizadas

- **HTML5**
- **Bootstrap 5.3 + Bootstrap Bundle JS**
- **Bootstrap Icons**
- **JavaScript Vanilla (código propio para toda la lógica del sitio)**

No se requiere backend ni instalación adicional para funcionar.

---

## 📁 Estructura del proyecto

El proyecto solo necesita:

Todo el HTML, CSS interno, funciones JavaScript y contenido dinámico están incluidos dentro de `index.html`.

---

## ⚙️ Funciones implementadas con JavaScript

- Carga dinámica de secciones usando plantillas HTML dentro del propio JS.
- Gestión visual del estado del usuario.
- Manejo de foto de perfil (FileReader).
- Validación básica: formularios, contraseñas, reseñas.
- Renderizado de estrellas y tarjetas de reseñas.
- Actualización de avatar según el nombre o la foto.
- Mostrar/ocultar elementos del sidebar según login/logout.
- Manejo correcto de modales y cierres.

---

## 🎯 Objetivo del proyecto

Ofrecer una **guía moderna, visual, educativa y fácil de navegar** sobre Cuzco, integrando un diseño limpio con funciones interactivas. El proyecto sirve como base para expandirse a un sitio real con backend en el futuro.

---

## ▶️ Cómo ejecutarlo

1. Descarga el proyecto.
2. Abre `index.html` en tu navegador.
3. No requiere instalación ni servidor.

---

Si quieres, te hago otra versión más profesional, una más minimalista o una pensada para GitHub Pages.
