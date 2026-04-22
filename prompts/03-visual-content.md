# Prompt 3 — Descripciones visuales (prompts para generadores de imágenes)

## Rol
Actúa como **Instagram Visual Creator**. Traduces estrategia en descripciones visuales detalladas, listas para usarse como prompt en un generador de imágenes (Midjourney, DALL·E, etc.).

## Contexto
- `outputs/content-calendar.md` del paso 2 (pégalo o referéncialo).
- INSTAGRAM_DESCRIPTION (para respetar el tono visual de marca).

## Tarea
Para **cada día** del calendario (lunes a viernes), escribe una descripción visual que incluya:

1. **Sujeto principal** y acción/escena.
2. **Paleta de colores** (2-4 colores explícitos).
3. **Iluminación y mood** (cálida, dramática, minimalista…).
4. **Estilo visual** (fotografía realista, ilustración, 3D, flat, analógico).
5. **Composición / encuadre** (primer plano, cenital, regla de tercios…).
6. **Detalles clave** que refuercen el mensaje del post.
7. **Formato destino** (1:1 feed, 9:16 reel, 4:5 carrusel).

Ejemplos de referencia de estilo de descripción:
- "Imagen realista de un living moderno con ventanal a la ciudad, paleta neutra con un sofá rojo de acento, luz natural cálida, mood acogedor."
- "Escena minimalista: escritorio de madera clara con laptop, cuaderno y taza de café, fondo blanco, sensación de foco y productividad."
- "Playa tropical al atardecer, palmeras, cielo en tonos cálidos, vacía, mood de calma."

## Formato de salida
```markdown
# Visual content — semana de {CURRENT_DATE}

## Lunes
**Prompt visual:** (texto listo para pegar en un generador)
**Formato:** 1:1 / 9:16 / 4:5
**Notas de marca:** ...

## Martes
...
```

Guarda en `outputs/visual-content.md`.
