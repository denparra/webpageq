# Queirolo Autos Web

Este repositorio incluye una estructura básica de archivos para iniciar el rediseño del sitio de Queirolo Autos. Se basa en las recomendaciones del archivo `Guia.pdf` y contempla las páginas esenciales:

- Inicio
- Seminuevos (inventario)
- Financiamiento
- Consignación
- Nosotros
- Contacto
- Blog
- Tienda

El contenido del sitio se ubica en la carpeta `site/`. Para mantener un orden básico se usan subdirectorios para las páginas y los recursos estáticos:

```
site/
  index.html
  pages/              # páginas individuales
  blog/               # sección de blog
  tienda/             # sección de tienda online
  assets/
    css/
    js/
    img/
```

### Ejecutar localmente

Puedes visualizar el sitio de forma local utilizando el servidor simple de Python:

```bash
cd site
python3 -m http.server 8000
```

Luego abre `http://localhost:8000` en tu navegador.

Esto es solo una plantilla básica para iniciar el proyecto.
