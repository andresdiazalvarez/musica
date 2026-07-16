# Mi Musica

App web sencilla para escuchar musica local desde el navegador.

## Como usarla

1. Abre la app en el navegador.
2. Pulsa **Abrir carpeta de musica**.
3. Elige la carpeta donde tienes tus canciones.
4. Selecciona una cancion de la lista para reproducirla.

La app no sube tus canciones a internet. Solo pide permiso al navegador para leer la carpeta que tu elijas.

Tambien acepta comandos de voz en navegadores compatibles:

- "abrir" o "abrir carpeta"
- "siguiente"
- "pausa"
- "reproducir"

El navegador puede pedir permiso para usar el microfono y para leer la carpeta. Es una proteccion propia del navegador y no se puede desactivar desde una web publicada en GitHub Pages.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube estos archivos a la raiz del repositorio:
   - `index.html`
   - `README.md`
   - `.nojekyll`
   - `.gitignore`
3. En GitHub, entra en **Settings > Pages**.
4. En **Build and deployment**, selecciona:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/** root
5. Guarda los cambios.

GitHub te dara una URL parecida a:

```text
https://tu-usuario.github.io/tu-repositorio/
```

## Nota importante

El boton moderno de abrir carpeta funciona mejor en Chrome o Edge. En otros navegadores la app usa el selector compatible de carpeta/archivos cuando esta disponible.
