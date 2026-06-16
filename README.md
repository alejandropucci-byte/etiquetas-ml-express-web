# Etiquetas ML Express Web

Version web estatica para usar desde celular y publicar en GitHub Pages.

## Que hace

- Modo 1: prepara 1 etiqueta en A4 horizontal con la etiqueta al lado izquierdo.
- Modo 2: junta 2 envios en una hoja A4 horizontal, con producto y cantidad debajo de cada etiqueta.

Los PDFs se procesan en el navegador. No se suben a un servidor propio.

## Publicar en GitHub Pages

1. Crear un repositorio nuevo en GitHub, por ejemplo `etiquetas-ml-express-web`.
2. Subir estos archivos al repositorio:
   - `index.html`
   - `README.md`
3. En GitHub, entrar a `Settings`.
4. Ir a `Pages`.
5. En `Build and deployment`, elegir:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Guardar.

GitHub va a entregar una URL parecida a:

```txt
https://TU_USUARIO.github.io/etiquetas-ml-express-web/
```

## Dependencias externas

La pagina carga estas librerias desde CDN:

- `pdf-lib`
- `pdfjs-dist`

Por eso necesita internet para funcionar publicada en GitHub Pages.
