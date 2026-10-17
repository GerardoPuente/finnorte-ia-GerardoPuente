# Bitácora de uso de IA

> Obligatoria en todas las entregas. Una fila por uso relevante de una herramienta de IA (chat, asistente de código, generador).
> La IA es una herramienta permitida; ocultarla no lo es. Se califica la honestidad y la calidad de la validación, no si la usaste.

| Fecha | Entrega | Herramienta y modelo | Para qué la usé | Prompt (resumen o enlace) | Qué acepté | Qué cambié o rechacé y por qué | Cómo lo validé |
|---|---|---|---|---|---|---|---|
| 2026-10-17 | A1 | Claude (Anthropic) | Implementar normalizar, coseno y buscar en retrieval.py; redactar preguntas de evals/a1_v3-soporte.jsonl; llenar el notebook a1_manual.ipynb | Pegué la guía del lab, el manual y el repo y pedí completar la A1 | La implementación con numpy (norma 0 → 1, coseno con guarda de cero, buscar con matriz @ q y argsort) | Cambié 2 preguntas «exacto» que tenían respuesta ambigua (el código FN-4291 aparece en api-06 y api-07) por FN-4011 y X-FinNorte-Signature | `pytest tests/test_a1_vectores.py` → 4 passed; revisé a mano los cosenos del notebook |
