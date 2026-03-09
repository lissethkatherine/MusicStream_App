# MusicStream 🎵

Maquetación de una tienda de música y reproductor web hecho con HTML y CSS. Es solo la estructura visual de la página, sin funcionalidad real.

## Páginas

- **index.html** — Tienda principal con banner destacado, grilla de álbumes y canciones más vendidas
- **album-detail.html** — Detalle de álbum con tracklist, info del artista y botón de compra
- **player.html** — Reproductor completo con barra de progreso, controles y cola de reproducción
- **cart.html** — Carrito de compras con control de cantidades y resumen del pedido
- **checkout.html** — Formulario de pago con tarjeta y dirección de facturación
- **success.html** — Confirmación de compra con resumen del pedido

## Estructura

```
MUSICSTREAM_APP/
├── assets/
│   ├── icons/
│   ├── img/
│   └── mp3/
├── css/
│   ├── views/
│   │   ├── album.css
│   │   ├── checkout.css
│   │   ├── player.css
│   │   └── store.css
│   ├── components.css
│   ├── layout.css
│   └── main.css
├── album-detail.html
├── cart.html
├── checkout.html
├── index.html
├── player.html
└── success.html
```

## Flujo de navegación

```
index → album-detail → cart → checkout → success
             ↑
          player
```

## Cómo correrlo

Es un sitio estático, basta con abrir cualquier `.html` en el navegador. Para evitar problemas con rutas, se recomienda usar un servidor local:

```
python -m http.server 8080
```

Luego entrar a `http://localhost:8080`.

## Tecnologías
- HTML5 / CSS3 sin frameworks