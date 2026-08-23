# Publicar en GitHub Pages

1. Crea un repositorio en GitHub y sube este proyecto a la rama `main`.
2. En el repositorio, abre **Settings → Pages** y selecciona **GitHub Actions** como fuente.
3. Cada push a `main` ejecutará `.github/workflows/deploy-pages.yml` y publicará la demo.

La URL será:

`https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/demo/share`

Desde esa página puedes copiar o descargar el QR. El QR apuntará automáticamente a `/demo` en la URL pública correcta. El build genera también `404.html` para que las rutas funcionen al abrirse directamente en GitHub Pages.
