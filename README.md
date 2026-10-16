# Para Perros — sitio web provisorio

Sitio de una sola página (HTML + CSS, sin dependencias). Las fotos están en `assets/`.

## Cómo publicarlo en GitHub Pages

1. Creá una cuenta en https://github.com (si todavía no tenés).
2. Tocá **New repository**, ponele un nombre (por ejemplo `paraperros`), dejalo en **Public** y creá el repositorio.
3. Tocá **uploading an existing file** y arrastrá **todo el contenido** de esta carpeta: `index.html`, `.nojekyll` y la carpeta `assets` (tiene que quedar `assets/` con las fotos adentro). Confirmá con **Commit changes**.
4. Entrá a **Settings → Pages**. En **Source** elegí **Deploy from a branch**, rama **main** y carpeta **/ (root)**. Guardá.
5. En uno o dos minutos GitHub te muestra la dirección: `https://TU-USUARIO.github.io/paraperros/`.

## Usar tu dominio (paraperros.com.ar)

En **Settings → Pages → Custom domain** escribí tu dominio y, en el panel donde tenés registrado el dominio, agregá los registros DNS que GitHub te indica (cuatro registros A y un CNAME para `www`). La documentación oficial paso a paso está en https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site

## Editar textos o fotos

- Textos: abrí `index.html` en GitHub (ícono del lápiz) y cambiá el texto.
- Fotos: subí la nueva imagen a `assets/` con el mismo nombre para reemplazarla.
