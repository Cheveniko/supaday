# Supabase detrás de 300K tickets

Slides de mi charla en **Supaday Quito · Supabase × SpaceXAI** (septiembre 2026).

**Nicolás Baquero** — [baquero.engineering](https://baquero.engineering) · [@Cheveniko](https://x.com/Cheveniko)

## De qué va

Cómo construí y sostengo la plataforma de venta de tickets de
[Wiwa Quito](https://www.visitawiwa.com), el primer parque refugio de animales
silvestres del Ecuador, que recibe más de 200 mil visitantes al año.

Desde febrero de 2025 la plataforma lleva **93 mil transacciones procesadas** y
**336 mil tickets generados**.

La charla cubre tres cosas:

- **Producto y negocio** — cómo apareció la oportunidad y qué problemas del parque resolvimos.
- **Por qué Supabase** — DB, Auth y Storage como palanca para un equipo pequeño.
- **Los downsides y algunos tips** — lo que cuesta, y cómo trabajar más cómodo.

## Correr los slides

Necesitas [Node.js](https://nodejs.org).

```bash
npm install
npm start
```

Se abre en <http://localhost:8000>.

## Atajos

| Tecla | |
|-------|---|
| `→` / `espacio` | Avanzar |
| `←` | Retroceder |
| `F` | Pantalla completa |
| `O` | Ver todas las slides |
| `S` | Vista de presentador (notas) |
| `B` | Pantalla en negro |
| `T` | Alternar modo claro / oscuro |

Para exportar a PDF: <http://localhost:8000/?print-pdf> y desde ahí imprimir a PDF
con márgenes en *None* y los gráficos de fondo activados.

## Estructura

```
index.html        Todas las slides
css/theme.css     Tema, basado en la línea gráfica de baquero.engineering
assets/           Imágenes y logos
```

Hecho con [reveal.js](https://revealjs.com) 6. Tipografías Space Grotesk y Space Mono.
