# 🤖 TP 1 – La familia de las IAs

### Inteligencia Artificial | 6.º 3.ª

**Integrantes:** Mateo Morea, Nicolás Barrales y Santiago Orlando  
**Profesor:** Luis Pandiani

---

## 📌 Descripción del trabajo

En este trabajo investigamos y comparamos seis modelos de inteligencia artificial, analizando sus desarrolladores, su cantidad de parámetros y sus diferencias de acceso.

Utilizamos **NotebookLM** para elaborar una infografía a partir de fuentes oficiales y luego verificamos algunos de los datos para comprobar su exactitud.

## 🖼️ Infografía

La siguiente infografía presenta una comparación visual de los seis modelos investigados.

![Infografía: La familia de las IAs](infografia.png)

## 🧠 Modelos investigados

| Modelo | Empresa | Parámetros | Acceso |
|---|---|---|---|
| GPT-4 (ChatGPT) | OpenAI | No publicados | Cerrado |
| Claude 3.7 Sonnet | Anthropic | No publicados | Cerrado |
| Gemini 2.5 Pro | Google DeepMind | No publicados | Cerrado |
| Qwen3-235B-A22B | Alibaba / Qwen | 235B totales, 22B activos | Abierto |
| Llama 3.1 8B Instruct | Meta | 8B | Abierto |
| Gemma 3 27B IT | Google DeepMind | 27B | Abierto |

**Nota:** Las versiones indicadas corresponden a los modelos seleccionados para este trabajo. ChatGPT es un producto que puede utilizar distintos modelos.

## 📏 Escala de parámetros

Para comparar los tamaños utilizamos la siguiente escala:

**0.1B · 0.5B · 1B · 7B · 70B · 235B · 1T**

- **B:** mil millones de parámetros.
- **1T:** un billón de parámetros (1.000B).
- **Parámetro:** valor que el modelo aprende durante el entrenamiento.
- **Modelo abierto:** permite acceder a sus pesos para descargarlos y utilizarlos según su licencia.
- **Modelo cerrado:** no ofrece sus pesos públicamente.

Una mayor cantidad de parámetros no garantiza mejores resultados.

## 🔎 Modo detective – Verificación de datos

Seleccionamos tres afirmaciones generadas por la IA y las comparamos con documentación oficial.

| Dato | Lo que dijo la IA | Fuente oficial | ¿Bien? |
|---|---|---|---|
| GPT-4 | Sus parámetros no están publicados. | OpenAI no revela el número de parámetros en su informe técnico. | ✅ Sí |
| Qwen3 | Tiene 235B de parámetros totales y 22B activos. | Qwen confirma ambas cantidades. | ✅ Sí |
| Llama 3.1 | La versión Instruct analizada tiene 8B de parámetros. | Meta confirma el tamaño de Llama 3.1 8B Instruct. | ✅ Sí |

### Conclusión de la verificación

Los tres datos seleccionados resultaron correctos al compararlos con sus fuentes oficiales.

Aprendimos que no debemos confiar automáticamente en toda la información generada por una inteligencia artificial, ya que puede cometer errores o presentar datos sin verificar.

## 📚 Fuentes oficiales utilizadas

Para desarrollar el trabajo cargamos 11 fuentes en NotebookLM:

1. [Claude 3.7 Sonnet and Claude Code – Anthropic](https://www.anthropic.com/news/claude-3-7-sonnet)
2. [GPT-4 – OpenAI](https://openai.com/index/gpt-4-research/)
3. [Gemma 3 – Google DeepMind](https://deepmind.google/models/gemma/gemma-3/)
4. [Introducing Llama 3.1 – Meta AI](https://ai.meta.com/blog/meta-llama-3-1/)
5. [Qwen3-235B-A22B – Hugging Face](https://huggingface.co/Qwen/Qwen3-235B-A22B)
6. [Qwen3: Think Deeper, Act Faster – Qwen](https://qwenlm.github.io/blog/qwen3/)
7. [Gemma 3 27B IT – Hugging Face](https://huggingface.co/google/gemma-3-27b-it)
8. [GPT-4 Technical Report – OpenAI (PDF)](https://cdn.openai.com/papers/gpt-4.pdf)
9. [Gemini 2.5 Pro Model Card – Google DeepMind (PDF)](https://storage.googleapis.com/deepmind-media/Model-Cards/Gemini-2-5-Pro-Model-Card.pdf)
10. [Claude 3.7 Sonnet System Card – Anthropic (PDF)](https://www-cdn.anthropic.com/9ff93dfa8f445c932415d335c88852ef47f1201e/claude-3-7-sonnet-system-card.pdf)
11. [Llama 3.1 8B Instruct – Hugging Face](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct)

## 🛠️ Herramientas utilizadas

- **NotebookLM:** investigación, análisis de fuentes y generación de la infografía.
- **GitHub:** almacenamiento y presentación del trabajo.
- **Documentación oficial:** verificación de datos.

## ✅ Conclusión general

Este trabajo nos permitió conocer las diferencias entre modelos abiertos y cerrados, comprender el significado de los parámetros y analizar cómo se comparan distintas inteligencias artificiales.

También aprendimos la importancia de consultar documentación oficial y verificar la información generada por herramientas de IA.

---

**Trabajo Práctico N.º 1 – La familia de las IAs**  
**6.º 3.ª – Profesor Luis Pandiani**