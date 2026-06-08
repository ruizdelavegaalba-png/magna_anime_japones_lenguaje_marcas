# 👾 Zona Manga Digital

> *"Tu biblioteca de manga y anime, con estética retro-pixelada"*

Repositorio del proyecto **Zona Manga Digital**, un catálogo de manga y anime desarrollado como proyecto individual de DAW. El objetivo fue trabajar con datos estructurados en **XML con namespace propio** y presentarlos en una interfaz web de diseño retro inspirada en la cultura pixel-art japonesa.

---

## 📌 Descripción del proyecto

La aplicación muestra una colección de títulos de manga y anime (One Piece, Fullmetal Alchemist…) con información sobre autor, género, demografía, número de publicaciones y estado. Los datos se definen en un fichero `magna.xml` con namespace personalizado y se visualizan desde la página `index.html`.

---

## 🚀 Características principales

- 🎨 **Diseño retro-pixelado** — paleta oscura con neones (verde `#00ff9d`, magenta `#ff00ff`, cyan `#00ffff`) y tipografía monoespaciada `VT323`
- 📄 **Datos en XML** — estructura con namespace `manga:` propio, accesible directamente desde el botón "Ver archivo XML"
- 🖼️ **Imágenes en Cloudinary** — CDN externo para las portadas de los títulos
- 📱 Layout con **sidebar de navegación** y contenedor de cartas responsive

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura semántica de la página |
| CSS3 | Estilo retro, layout flex, efectos hover |
| XML + Namespace | Almacenamiento estructurado de datos |
| Cloudinary | CDN para imágenes de portadas |

---

## 📂 Estructura del proyecto

```
├── index.html      # Página principal con el catálogo
├── magna.xml       # Datos de los títulos en XML con namespace
└── style.css       # Estilos retro-pixelados
```

---

## 🔧 Cómo visualizarlo

1. Clona el repositorio:
   ```bash
   git clone https://github.com/ruizdelavegaalba-png/magna_anime_japones.git
   ```
2. Abre `index.html` directamente en el navegador.
3. Puedes consultar el XML pulsando el botón **"Ver archivo XML"** del footer.

---

## ✒️ Autora

**Alba Ruiz de la Vega** — Estudiante de DAW, CEI Sevilla
