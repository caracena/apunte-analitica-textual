# Analítica Textual

Este apunte acompaña el curso **Analítica Textual** y está pensado como una guía aplicada para pasar desde los fundamentos del procesamiento de texto hasta el diseño de soluciones con modelos modernos y agentes de IA.

La propuesta sigue una progresión semanal:

| Semana | Tema central | Resultado esperado |
| --- | --- | --- |
| 1 | Introducción, panorama actual y limpieza con regex | Preparar texto real para análisis |
| 2 | Ingeniería de características, TF-IDF, VSM y similitud | Representar y comparar documentos |
| 3 | Clustering | Descubrir grupos y temas sin etiquetas |
| 4 | Clasificación | Entrenar modelos supervisados para categorizar textos |
| 5 | Word Embeddings | Capturar relaciones semánticas densas |
| 6 | Transformers, fine-tuning y LLMs | Entender el salto a modelos pre-entrenados |
| 7 | Agentes de IA | Integrar modelos, herramientas y memoria |
| 8 | Casos de uso | Traducir técnicas a contextos de negocio |

## Cómo usar este libro

Cada capítulo combina:

- explicación conceptual breve;
- ejemplos en Python;
- interpretación de resultados;
- ejercicios para profundizar.

Los ejemplos fueron diseñados para ser autoexplicativos y reutilizables en notebooks, laboratorios o tareas. Cuando una técnica requiere librerías más pesadas o un entorno especial, se indica explícitamente.

## Requisitos sugeridos

Para seguir los ejemplos base del curso, se recomienda trabajar con:

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

## Resultados de aprendizaje

Al finalizar el curso deberías poder:

1. limpiar colecciones textuales con criterios reproducibles;
2. representar documentos con bolsas de palabras, TF-IDF y espacios vectoriales;
3. medir similitud y agrupar documentos;
4. entrenar clasificadores supervisados;
5. interpretar embeddings y modelos pre-entrenados;
6. evaluar cuándo usar LLMs y cuándo una solución clásica es suficiente;
7. diseñar flujos con agentes de IA y herramientas externas;
8. conectar decisiones técnicas con métricas y restricciones del negocio.

## Recomendación pedagógica

Conviene leer cada capítulo en orden, ejecutar los fragmentos de código y luego modificar los corpus de ejemplo. En analítica textual, aprender significa comparar resultados, inspeccionar errores y refinar decisiones de modelado.
