# dermanova-v3

[Edit in StackBlitz next generation editor ⚡️](https://stackblitz.com/~/github.com/crisduranh13/dermanova-v3)

## SEO de la demo y dominio final

El dominio final confirmado es `https://clinicadermanova.com.mx`. La portada está en `index.html`. La URL base temporal de la demo es `https://dermanova-ver3.netlify.app/` y aparece solo en los tres metadatos sociales `og:url`, `og:image` y `twitter:image` de ese archivo. La demo tiene `noindex, nofollow` en `index.html` y en la página de plantilla `page2.html`.

Antes de publicar en el dominio final:

1. Sustituir las tres referencias a la URL temporal en `index.html` por `https://clinicadermanova.com.mx`. Añadir `<link rel="canonical" href="https://clinicadermanova.com.mx/">`.
2. Quitar `noindex, nofollow` de la portada solo cuando el dominio final esté listo. Mantener `page2.html` fuera de indexación o retirarla de la publicación si ya no se necesita.
3. Crear `sitemap.xml` con la URL canónica real de la portada y `robots.txt` que permita su rastreo y apunte a ese sitemap. No incluir URLs de tratamientos que no existen.
4. Resolver los seis enlaces de publicaciones que todavía apuntan a `www.clinicadermanova.com.mx`: alojar los PDF en una ubicación confirmada o reemplazar sus enlaces por fuentes verificadas.
5. Comprobar en el dominio final que portada, metadatos, imagen social, sitemap y enlaces responden correctamente antes de solicitar indexación.
