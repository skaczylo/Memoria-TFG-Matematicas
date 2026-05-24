# Memoria TFG — Matemáticas: El transformador

Este repositorio contiene la memoria del Trabajo de Fin de Grado en Matemáticas, cuyo objetivo es construir una comprensión rigurosa y completa del  transformador: la arquitectura que revolucionó la inteligencia artificial moderna.

## Sobre el trabajo

El TFG parte de los fundamentos de las redes neuronales y avanza progresivamente hasta explicar con detalle la arquitectura del transformador y sus aplicaciones en el procesamiento del lenguaje natural (NLP).

### Contenido por capítulos

1. **Introducción** — Recorrido histórico desde el Test de Turing y el perceptrón hasta la publicación de *Attention Is All You Need* (2017), que introdujo el transformador y dio origen a modelos como GPT, BERT o Gemini.

2. **Redes Neuronales** — Formalización matemática de las redes neuronales: vectores de activación, matrices de pesos, funciones de activación, función de pérdida y las funciones Softmax y LayerNorm que son piezas clave del transformador.

3. **El Transformador** — Análisis detallado de la arquitectura: el mecanismo de autoatención (*self-attention*), las matrices de consulta/clave/valor (Q, K, V), la atención múltiple (*multi-head attention*) y la arquitectura completa con conexiones residuales y normalización de capa.

4. **Lenguaje Natural** — Cómo los transformadores procesan texto: tokenización (algoritmo BPE), *embeddings* y las tres variantes arquitectónicas — codificador (BERT), decodificador (GPT) y codificador-decodificador — incluyendo la atención enmascarada y la atención cruzada (*cross-attention*).

5. **Implementación** — Construcción desde cero en Python y PyTorch de un traductor inglés-español basado en la arquitectura codificador-decodificador, entrenado con el corpus OPUS100 de un millón de pares de frases.

## Recursos

- El código fuente del traductor implementado está disponible en [github.com/skaczylo/Transformer-Translator](https://github.com/skaczylo/Transformer-Translator).
- La memoria está escrita en LaTeX con la plantilla TeXiS.
