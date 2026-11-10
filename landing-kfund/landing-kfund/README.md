# Landing Lean Finance × K Fund

Página estática para las startups participadas de K Fund. Diseño: Figma «One pager Lean Finance × K Fund».

## Estructura

```
index.html              la página completa (HTML + CSS + JS)
assets/                 imágenes exportadas de Figma
  hero.jpg              fondo del hero (el mismo en PC y móvil)
  foto.jpg              foto de «Lo que te ofrecemos» (la misma en PC y móvil)
  logo-lf-blanco.png    logo Lean Finance blanco (secciones oscuras)
  logo-lf-color.png     logo Lean Finance color  (sección clara)
  logo-kfund-blanco.png logo K Fund blanco       (secciones oscuras)
  logo-kfund-oscuro.png logo K Fund oscuro       (sección clara)
  favicon.png           icono de la pestaña (opcional)
fonts/
  CarmenSans-Bold.woff2 tipografía de los titulares
```

Los nombres de archivo tienen que ser exactamente estos (minúsculas, sin espacios).

## Cambiar los enlaces de los botones

Al final de `index.html`, en el `<script>`:

```js
var CTA_CONTACTO    = "mailto:javier@leanfinance.es?subject=Vengo%20de%20K%20Fund";
var CTA_DIAGNOSTICO = "mailto:...";
```

## Publicar

GitHub → Settings → Pages → Branch `main`, carpeta `/ (root)` → Save.
