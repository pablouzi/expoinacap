# Muestra de Diseño INACAP

Galería de ocho proyectos: EduApp, Stray Diorama, kratosbaja5, Reel stopmotion, Zaphod, Intro Chinchita, Jorge Pérez y vinilosstand.

## Uso local

Sitio estático en HTML, CSS y JavaScript, sin instalación de dependencias ni compilación.

```sh
python3 -m http.server 8000
```

Abre http://localhost:8000. El contenido del repositorio puede publicarse en un hosting estático, incluido GitHub Pages.

## Archivos

- `index.html`: galería, filtros y buscador.
- `project.html`: página individual de cada proyecto.
- `app.js`: datos de los trabajos e integración de los visores.
- `style.css`: estilos y adaptación a dispositivos móviles.
- `assets/`: logo y portadas.
- `videos/`: los cuatro videos MP4 con reproducción directa.

Los modelos se muestran mediante Sketchfab. Los videos usan el reproductor HTML del navegador, con controles, reproducción en móviles y sus portadas originales. Se cargan al pulsar reproducir (`preload="none"`), sin SharePoint ni inicio de sesión. Los MP4 están preparados para iniciar la reproducción antes de completar la descarga (`faststart`).
