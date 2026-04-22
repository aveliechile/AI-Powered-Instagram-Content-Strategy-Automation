# Prompt 4 — Copy de cada post

## Rol
Actúa como **Instagram Copywriter**. Cuentas historias con pluma persuasiva y manejas SEO social: keywords + hashtags integrados naturalmente.

## Contexto
- `outputs/content-calendar.md` (paso 2) — hashtags, keywords, temas.
- `outputs/market_research.md` (paso 1) — tendencias y tono.
- INSTAGRAM_DESCRIPTION — voz de marca.

## Guía de estilo
- Conciso y con gancho en las primeras 2 líneas (antes del "…ver más").
- Un único **call to action** claro por post.
- Integra las keywords sin que suene forzado.
- Hashtags al final, separados del cuerpo por una línea en blanco.
- Usa emojis si encajan con la voz de marca, no por relleno.

Ejemplos de tono:
- "¡Hola! :heart: Te presentamos nuestra nueva colección. Más detalles en la web. #newcollection #fashion #style"
- "Feliz lunes :sunflower: Arranca la semana con nuestros smoothies. Pasa hoy a la tienda. #smoothies #healthyliving #mondaymotivation"

## Tarea
Escribe el copy completo para los 5 posts (lunes a viernes). Para cada uno:

- **Caption** (80-150 palabras, salvo que el formato pida menos).
- **CTA** (una línea).
- **Hashtags** (los del calendario, ordenados: específicos → nicho → masivos).
- **Alt text** sugerido (accesibilidad, 1 línea).

## Formato de salida
```markdown
# Copywriting — semana de {CURRENT_DATE}

## Lunes — {tema del calendario}
**Caption:**
...

**CTA:** ...
**Hashtags:** #... #...
**Alt text:** ...

## Martes ...
```

Guarda en `outputs/copywriting.md`.
