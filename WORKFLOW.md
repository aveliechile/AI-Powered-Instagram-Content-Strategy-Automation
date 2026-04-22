# Flujo de Contenido Instagram — Versión Markdown

Versión sin código, sin Python y sin CrewAI del proyecto original.
Pensada para usarse desde el celular con Claude Code: solo leer prompts y pegarlos en el chat.

## Cómo se usa

1. Abre `INPUTS.md` y completa los 3 datos (descripción de la cuenta, tema de la semana, fecha).
2. Abre los prompts uno por uno, en orden, y pégaselos a Claude Code. Cada prompt recibe como entrada el resultado del paso anterior.
3. Guarda la salida de cada paso en `outputs/` (los nombres sugeridos ya existen en este repo como ejemplo: `market_research.md`, `visual-content.md`, `final-content-strategy.md`).

## Orden del flujo

| # | Prompt | Entrada | Salida sugerida |
|---|---|---|---|
| 1 | `prompts/01-market-research.md` | `INPUTS.md` | `outputs/market_research.md` |
| 2 | `prompts/02-content-strategy.md` | paso 1 | `outputs/content-calendar.md` |
| 3 | `prompts/03-visual-content.md` | paso 2 | `outputs/visual-content.md` |
| 4 | `prompts/04-copywriting.md` | pasos 2 y 1 | `outputs/copywriting.md` |
| 5 | `prompts/05-final-report.md` | pasos 1-4 | `outputs/final-content-strategy.md` |

## Equivalencia con el proyecto original

- `market_researcher` (agents.yaml) → `prompts/01-market-research.md`
- `content_strategist` → `prompts/02-content-strategy.md` y `prompts/05-final-report.md`
- `visual_creator` → `prompts/03-visual-content.md`
- `copywriter` → `prompts/04-copywriting.md`
- `main.py` (inputs) → `INPUTS.md`
- `crew.py` (orquestación) → este archivo `WORKFLOW.md`

## Atajo: correr todo de una vez

Si prefieres no copiar/pegar 5 veces, abre `prompts/00-run-all.md`: es un único prompt que le pide a Claude ejecutar todo el flujo encadenado y entregar los 5 artefactos finales.
