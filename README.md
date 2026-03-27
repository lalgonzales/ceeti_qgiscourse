# Curso de QGIS y Herramientas Python para el Análisis Geoespacial

Sitio web del **Curso básico-intermedio de QGIS** ofrecido por el
Centro de Excelencia para la Educación en Tecnologías de la Información
(**CEETI**) de la Universidad Nacional Autónoma de Honduras (**UNAH**).

## 📋 Descripción

- **Modalidad**: Virtual
- **Horario**: Lunes a Jueves, 6:00 PM – 7:30 PM (hora Honduras)
- **Duración**: 20 horas (sesiones de 1.5 h)

## 📚 Contenido

| Módulo | Tema |
|:------:|:-----|
| 1 | Introducción a QGIS y SIG |
| 2 | Carga y manejo de datos |
| 3 | Edición y geoprocesamiento básico |
| 4 | Análisis espacial para rutas |
| 5 | Automatización con Python y PyQGIS |
| 6 | Visualización avanzada y mapas finales |
| 7 | Integración y casos prácticos |

## 🛠️ Tecnología

El sitio está construido con [Quarto](https://quarto.org), una plataforma
de publicación científica de código abierto.

### Requisitos para desarrollo local

- [Quarto CLI](https://quarto.org/docs/get-started/) ≥ 1.4

### Comandos

```bash
# Previsualizar el sitio localmente
quarto preview

# Generar el sitio estático
quarto render

# Publicar en GitHub Pages
quarto publish gh-pages
```

## 📁 Estructura del proyecto

```
ceeti_qgiscourse/
├── _quarto.yml              # Configuración del sitio Quarto
├── index.qmd                # Página de inicio
├── content/
│   ├── sobre/               # Información general del curso
│   │   ├── syllabus.qmd     # Temario completo del curso
│   │   └── instructor.qmd   # Perfil del instructor
│   └── modulos/             # Contenido por módulo
│       ├── modulo1.qmd      # Módulo 1: Introducción a QGIS y SIG
│       ├── modulo2.qmd      # Módulo 2: Carga y manejo de datos
│       ├── modulo3.qmd      # Módulo 3: Edición y geoprocesamiento básico
│       ├── modulo4.qmd      # Módulo 4: Análisis espacial para rutas
│       ├── modulo5.qmd      # Módulo 5: Automatización con Python y PyQGIS
│       ├── modulo6.qmd      # Módulo 6: Visualización avanzada y mapas finales
│       └── modulo7.qmd      # Módulo 7: Integración y casos prácticos
└── assets/                  # Recursos estáticos
    ├── styles.css            # Estilos personalizados (tema claro)
    ├── styles-dark.css       # Estilos personalizados (tema oscuro)
    └── images/               # Imágenes y recursos gráficos
```

## 📄 Licencia

[LICENSE](LICENSE)
