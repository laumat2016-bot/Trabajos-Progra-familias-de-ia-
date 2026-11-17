# Trabajos-Programaci-n
# TP 1: La familia de las IAs

**Alumno:** Lautaro Iván Coronel Bravo  
**Escuela:** EEST N°1 "Julio Argentino Roca" – Miramar (6° Año, Informática)

## Modelos analizados
- **Cerrados (en la nube):** ChatGPT / GPT-4o (OpenAI), Claude 3.5 Sonnet (Anthropic), Gemini (Google DeepMind).
- **Abiertos (pesos descargables):** Llama 3.1 (Meta), DeepSeek-V3 (DeepSeek), Gemma 2 (Google).

## Registro del proceso con IA
- **Herramienta utilizada:** NotebookLM (cargando como fuentes las publicaciones oficiales de OpenAI, Anthropic, Google DeepMind, Meta, Hugging Face y Wikipedia).
- **Prompt utilizado:** Solicitud de infografía comparativa detallando creador, cantidad de parámetros (aclarando confidencialidad en modelos cerrados), tipo de acceso y escala visual `0.1B · 0.5B · 1B · 7B · 70B · 235B · 1T`.
- **Verificación (Modo Detective — qué datos estaban mal y se detectaron):**
  1. **Omisión en Gemma 2:** La infografía listó únicamente los tamaños de `9B` y `27B`, omitiendo la versión oficial de `2B` parámetros.
  2. **Error de orden en la escala visual:** Al graficar la recta numérica, la IA ubicó `37B activos` de DeepSeek-V3 más cerca de `1T` que `671B totales` (invirtiendo el orden de magnitud), y ubicó `8B` de Llama 3.1 a la izquierda de `7B`.
