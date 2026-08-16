# bolli.ar

Sitio personal estático de Diego Bollini.

No usa frameworks, dependencias, gestor de paquetes ni proceso de compilación:
el contenido vive en `index.html` y los estilos en `css/main.css`.

## Desarrollo local

Desde la raíz del repositorio:

```sh
python3 -m http.server 8000
```

Abrir <http://localhost:8000>.

## Estructura

```text
.
├── css/
│   └── main.css
├── images/
│   ├── avataaar.svg
│   └── back.webp
└── index.html
```

## Publicación

Se puede publicar directamente en cualquier hosting estático. El directorio a
publicar es la raíz del repositorio y no hay comando de build.
