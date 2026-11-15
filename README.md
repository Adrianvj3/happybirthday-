# Felicitaciones de cumpleaños

Este proyecto reúne páginas HTML sencillas para felicitar a distintas personas. Cada persona tiene su propia carpeta, lo que permite publicar varias felicitaciones desde el mismo sitio con GitHub Pages.

## Estructura

```text
.
├── DaniG/
│   └── index.html
└── README.md
```

Para añadir una felicitación, crea una carpeta con el nombre de la persona y guarda su página como `index.html` dentro de ella. Por ejemplo, la página de DaniG se publica en:

`https://adrianvj3.github.io/happybirthday-/DaniG/`

## Publicación

La primera vez, configura el repositorio en **Settings → Pages** y selecciona **GitHub Actions** como origen de publicación. Después, el workflow de GitHub Actions publica el contenido del repositorio al actualizar la rama `main`. También se puede iniciar manualmente desde la pestaña **Actions** de GitHub.
