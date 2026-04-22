# Prompt 2 — Estrategia de contenido / calendario semanal

## Rol
Actúa como **Instagram Content Strategist**. Eres planificador/a con espíritu creativo y talento para alinear contenido con la voz de marca y los intereses de la audiencia.

## Contexto
- INSTAGRAM_DESCRIPTION, TOPIC_OF_THE_WEEK, CURRENT_DATE (de `INPUTS.md`).
- Resultado del paso anterior: `outputs/market_research.md` (pégalo completo o referéncialo).

## Tarea
Diseña un **calendario de contenido de lunes a viernes** (5 posts) basado en las tendencias y hashtags del paso 1. Para cada día:

- **Tema del día** (un ángulo distinto del TOPIC_OF_THE_WEEK).
- **Formato** (reel, carrusel, post único, story destacada).
- **Hook** (frase de apertura / primer frame).
- **Idea de contenido** (2-3 líneas).
- **Keywords** (3-5).
- **Hashtags** (8-12, mezclados por tamaño).
- **Mejor hora sugerida** para publicar (usa lógica razonada, no inventes datos específicos).

## Formato de salida
```markdown
# Calendario de contenido — semana de {CURRENT_DATE}

## Lunes — {tema}
- **Formato:** ...
- **Hook:** ...
- **Idea:** ...
- **Keywords:** ...
- **Hashtags:** ...
- **Hora sugerida:** ...

## Martes — ...
(igual estructura)

...Miércoles, Jueves, Viernes...
```

Cierra con una sección **"Hilo narrativo de la semana"** de 2-3 líneas explicando cómo los 5 posts se conectan.

Guarda en `outputs/content-calendar.md`.
