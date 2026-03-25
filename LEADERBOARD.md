## 🏆 Leaderboard

### Subtask 1 — Term Detection

Identify technical term boundaries in EN-TR sentence pairs.

| System | Type | P | R | F1 |
|--------|------|----:|----:|----:|
| GPT-5.2 | baseline | 0.82 | **0.92** | **0.87** |
| Claude Sonnet 4.5 | baseline | 0.71 | 0.81 | 0.75 |
| Gemini 3 Flash | baseline | 0.56 | 0.80 | 0.66 |
| DeepSeek v3.2 | baseline | 0.51 | 0.70 | 0.59 |
| Co-Text · Mistral Large | participant | 0.45 | 0.71 | 0.55 |
| Co-Text · Mistral Large + Para | participant | 0.44 | 0.70 | 0.54 |
| Koç-CoT · Llama 4 Scout | participant | 0.42 | 0.50 | 0.46 |
| Co-Text · Llama 4 Scout | participant | 0.42 | 0.49 | 0.46 |
| Llama 4 Scout | baseline | 0.42 | 0.51 | 0.46 |
| KU-RAG · Llama 4 Scout | participant | 0.41 | 0.50 | 0.45 |
| Co-Text · Llama 4 Scout + Para | participant | 0.42 | 0.44 | 0.43 |
| **Human Expert** | human | — | — | 0.83 |

### Subtask 2 — Term Correction with Expert Input

Fix term translations using expert hints. Evaluated by Exact Match (EM).

| System | Type | EM |
|--------|------|----:|
| GPT-5.2 | baseline | **0.40** |
| Claude Sonnet 4.5 | baseline | **0.40** |
| DeepSeek v3.2 | baseline | 0.38 |
| Co-Text · Mistral Large | participant | 0.34 |
| Co-Text · Mistral Large + Para | participant | 0.34 |
| Koç-CoT · Llama 4 Scout | participant | 0.33 |
| Co-Text · Llama 4 Scout | participant | 0.30 |
| Gemini 3 Flash | baseline | 0.30 |
| KU-RAG · Llama 4 Scout | participant | 0.27 |
| Llama 4 Scout | baseline | 0.24 |
| Co-Text · Llama 4 Scout + Para | participant | 0.24 |
| **Human Expert** | human | **0.60** |

### Subtask 3 — End-to-End Post-Edit

Full translation post-editing with offline glossary access.

| System | Type | chrF | BLEU |
|--------|------|-----:|-----:|
| New Mind AI · Qwen3-4B | participant | 85.79 | **70.27** |
| Co-Text · Llama 4 Scout + Para | participant | **85.64** | 69.42 |
| GPT-5.2 | baseline | 83.97 | 64.82 |
| Co-Text · Llama 4 Scout | participant | 82.37 | 62.53 |
| Llama 4 Scout | baseline | 81.70 | 62.59 |
| Claude Sonnet 4.5 | baseline | 80.43 | 57.93 |
| Koç-CoT · Llama 4 Scout | participant | 79.77 | 58.27 |
| DeepSeek v3.2 | baseline | 78.83 | 55.18 |
| Co-Text · Mistral Large + Para | participant | 77.68 | 50.39 |
| Co-Text · Mistral Large | participant | 76.67 | 49.33 |
| Gemini 3 Flash | baseline | 74.59 | 52.82 |
| KU-RAG · Llama 4 Scout | participant | 66.78 | 36.38 |
