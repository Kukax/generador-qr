# Generador de Códigos QR para Imprimir

Generador de códigos QR en un solo archivo HTML. Pega un link, personaliza el QR y descárgalo en alta resolución o imprímelo.

Demo: https://kukax.github.io/generador-qr/

## Características

- Generación instantánea de QR desde cualquier link o texto.
- Título personalizable sobre el QR (con color elegible).
- Opciones de borde: sin borde, sólido, redondeado o doble, con grosor y color.
- Tamaños de exportación hasta 2048 px (apto para impresión, póster o lona).
- Descarga PNG final con título, borde, QR y link integrados.
- Modo lote: pega varios links (uno por línea, opcionalmente `Título | https://...`) y arma una hoja para imprimir.
- Hoja de impresión con vista para papel y botones de descarga individual por QR.
- 100 % lado del cliente, sin backend ni dependencias de build.

## Uso

1. Abre `index.html` en el navegador (doble clic, no requiere servidor).
2. Pega el link y escribe un título opcional.
3. Ajusta tamaño, corrección de errores, colores y borde.
4. Descarga el PNG o usa el botón de imprimir.

Para la hoja con varios QR, usa la pestaña "Varios / Hoja" con un link por línea.

## Impresión

- Usa 1024 px o 2048 px para papel y cartelería.
- Nivel de corrección H recomendado para impresos que pueden ensuciarse o doblarse.
- Tamaño mínimo sugerido en papel: 3 x 3 cm, luego verifica el escaneo.

## Tecnología

- HTML + CSS + JavaScript vanilla en un solo archivo.
- Librería QR: `qrcodejs` vía CDN (cdnjs).

## Publicar en GitHub Pages

El repo ya está configurado para GitHub Pages (rama `main`, ruta `/`).

Para actualizar el sitio:

```bash
git add index.html
git commit -m "cambio"
git push
```

## Estructura

```text
index.html   # aplicación completa
.nojekyll    # evita el procesamiento Jekyll en GitHub Pages
README.md    # este archivo
```
