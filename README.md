# Podcast: Docentes Adultos en Entornos Virtuales

Sitio web (GitHub Pages) del podcast académico que acompaña el estudio cualitativo sobre cómo los docentes adultos, que cursan una segunda especialidad en modalidad **e-learning**, construyen significados sobre su experiencia formativa.

## 🎧 Contenido

- **Caso de estudio**: Docentes adultos con responsabilidades laborales, familiares y académicas concurrentes.
- **Promesa**: Autonomía y flexibilidad que ofrece la modalidad e-learning.
- **Fricción**: Barreras sociotécnicas (conectividad, sobrecarga, privacidad).
- **Unidad de análisis**: Los significados expresados por los participantes (no la satisfacción).

## 🧩 Arquitectura del corpus

| Instrumento              | Volumen                       |
|--------------------------|-------------------------------|
| Entrevistas semiestructuradas | 12 entrevistas (75 páginas) |
| Grupos focales virtuales  | 2 sesiones (30 páginas)       |
| Foro académico           | 24 intervenciones (10 páginas) |
| Notas reflexivas          | 8 memos + 4 notas de decisión |

## 🔬 Fundamentación

- **Análisis Temático Reflexivo** (Braun & Clarke, 2006).
- Rol del investigador: reflexividad y rigurosidad interpretativa.
- Rol de **ATLAS.ti Web** (soporte): gestión documental, codificación abierta e in vivo, memos, colaboración en tiempo real.

## 🗂️ Estructura del repositorio

```
.
├── index.html              # Página principal del podcast (GitHub Pages)
├── README.md               # Este archivo
├── podcast.aac             # Audio del podcast
└── slides/
    ├── slide-01.html       # El Caso
    ├── slide-02.html       # Arquitectura del Corpus Cualitativo
    ├── slide-03.html       # Fundamentación: Análisis Temático Reflexivo
    └── slide-04.html       # ATLAS.ti Web: Entorno de Análisis en la Nube
```

## 🚀 Despliegue

El sitio se publica automáticamente con **GitHub Pages** desde la rama `main`. Cualquier cambio en `index.html` o en la carpeta `slides/` se refleja en el sitio público al hacer `git push`.

## 🛠️ Stack

- HTML5 + CSS3 (sin frameworks, sin build step).
- Font Awesome 6 vía CDN.
- Diseño responsivo con scroll-snap horizontal para las diapositivas.

---

© 2026 Universidad César Vallejo · Investigación cualitativa en entornos virtuales de aprendizaje
