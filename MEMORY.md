# Atlantic Studio — Memory

## Identidad

- **Nombre:** Atlantic Studio
- **Nombre anterior:** Atlantic Web (renombrado 21/04/2026)
- **Servicio:** Páginas web para pymes y negocios locales
- **Zona:** Santa Clara del Mar, Buenos Aires
- **WhatsApp:** 5492236247791

## Hosting

- **Org GitHub:** `atlantic-studio`
- **Repo:** `atlantic-studio.github.io`
- **URL:** atlantic-studio.github.io
- **Carpeta local:** `EMPRENDEDORES/atlantic-studio-deploy/`

## Archivos

- `index.html` — página principal completa
- `Nueva carpeta/logo nuevo.jpg` — logo Atlantic Studio (A con ola, paleta azul/cyan/lavanda/rosa)

## Diseño

### Paleta de colores
- **Navy** `#0d1b3e` — fondo oscuro, tipografía
- **Electric** `#2563eb` — azul eléctrico principal
- **Cyan** `#06b6d4` — acentos y tags
- **Lavender** `#c4b5fd` — degradado suave
- **Rose** `#f0abfc` — toque cálido final del degradado
- **Foam** `#f0f9ff` — fondos de secciones claras

### Estructura de la página
1. Nav fija — texto "ATLANTIC STUDIO" + botón "Hablemos" (WhatsApp)
2. Hero — logo grande como banner + headline + 2 botones
3. El problema — 4 cards (invisible en Google, solo WA no alcanza, competencia, primera impresión)
4. Servicios — 6 cards (diseño web, actualizaciones, hosting gratis, WA, soporte, catálogo)
5. Demos — 4 links a trabajos reales
6. Precios — 3 columnas (Presencia $150 / Profesional $280 / Completo $450 USD)
7. Contacto — botón WhatsApp + datos zona/entrega/hosting
8. Footer

## Demos vinculados

| Proyecto | URL |
|----------|-----|
| Pizzería El Romano | dontiburcio.github.io |
| Cuties Girls | mareachic.github.io |
| Baron Barbería | baronbarberia.github.io |
| The Nice Shot | theniceshot.github.io |

## Flujo para actualizar

```bash
cd "atlantic-studio-deploy"
# editar index.html
git add .
git commit -m "descripcion del cambio"
git push
# live en 1-2 min
```

## Precios actuales

| Plan | Precio | Incluye |
|------|--------|---------|
| Presencia | $150 USD | 1 sección, logo, WA, hosting |
| Profesional | $280 USD | Multi-sección, catálogo, pedidos WA, 1 mes soporte |
| Completo | $450 USD | Todo + dominio propio, animaciones, 3 meses soporte |

## Pendiente
- [ ] Conseguir logo en PNG con fondo transparente (para nav)
- [ ] Definir precios finales en ARS o USD
- [ ] Agregar más demos a medida que entren clientes
