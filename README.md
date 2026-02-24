**Blog-01 — Proyecto de ejemplo**

Una pequeña página web estática creada como proyecto de práctica para el curso. Este README explica de forma clara y estética qué contiene el repositorio, cómo ejecutarlo localmente y cómo contribuir.

**Resumen**
- **Propósito:**: Página de blog estática de ejemplo para aprender HTML y CSS.
- **Tecnologías:**: HTML, CSS.
- **Estado:**: Proyecto mínimo listo para personalizar.

**Demo Rápida**
- **Abrir localmente:**: Abre [blog.html](blog.html) en tu navegador.
- **Servidor ligero (recomendado):**:

```bash
# Servir en http://localhost:8000
python3 -m http.server 8000
```

**Estructura del Proyecto**
- **Archivo principal:**: [blog.html](blog.html) — marcado y contenido de la página.
- **Estilos:**: [style.css](style.css) — hoja de estilos principal.

**Instalación y uso**
- **Clonar el repositorio:**:

```bash
git clone <URL-del-repo>
cd blog-01
```
- **Abrir directamente:**: Haz doble clic en [blog.html](blog.html) o arrástralo a tu navegador.
- **Servir con Python:**: Ejecuta el comando de servidor ligero mostrado arriba y visita `http://localhost:8000/blog.html`.

**Editar y personalizar**
- **Cambiar contenido:**: Edita `blog.html` para modificar títulos, entradas y estructura.
- **Modificar estilos:**: Edita `style.css` para ajustar paleta, tipografías y disposición.
- **Sugerencia rápida:**: Para probar cambios sin recargar manualmente, usa una extensión de live-reload en tu editor o ejecuta un servidor con recarga automática (por ejemplo `live-server`).

**Buenas prácticas recomendadas**
- **Separar contenido/estilos:**: Mantén HTML para contenido y CSS para estilos.
- **Accesibilidad:**: Usa etiquetas semánticas (`header`, `main`, `article`, `footer`) y atributos `alt` en imágenes.
- **Optimización:**: Comprime imágenes y minimiza CSS en producción.

**Contribuir**
- **Reporte de errores:**: Abre un issue explicando el problema y pasos para reproducir.
- **Pull requests:**: Crea una rama descriptiva (`feature/nombre` o `fix/nombre`), añade cambios y abre PR con una explicación clara.

**Licencia**
- Este proyecto está bajo la licencia MIT — puedes adaptarlo libremente. Añade un archivo `LICENSE` si lo deseas.

**Contacto**
- **Autor / Mantenedor:**: Añade tu nombre y correo aquí si quieres que otros te contacten.

---

Si quieres, puedo:
- Crear un archivo `LICENSE` (MIT) y un `.gitignore` básico.
- Hacer commit y push del `README.md` por ti.
