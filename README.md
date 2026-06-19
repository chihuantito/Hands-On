# Hands-On AI & Machine Learning Explorations

Este repositorio contiene una colección de proyectos prácticos y experimentos avanzados en el ámbito de la Inteligencia Artificial, cubriendo desde los fundamentos de procesamiento de lenguaje natural hasta la arquitectura de agentes autónomos complejos.

## 🚀 Contenido del Repositorio

### 1. Machine Learning & NLP (Modelos de Lenguaje)
Enfoque en la implementación y comparación de técnicas clásicas y modernas de procesamiento de texto.
*   **Tokens y Embeddings:** Sistema de recomendación de canciones basado en **Word2Vec**. Entrenamiento de representaciones vectoriales para identificar similitudes en playlists musicales.
*   **Clasificación de Texto:** Evaluación comparativa de sentimientos utilizando **RoBERTa**, **FLAN-T5** y **GPT** sobre el dataset de Rotten Tomatoes.
*   **Técnicas:** Desde regresión logística con embeddings hasta *zero-shot classification*.

### 2. Prompt Engineering & Evaluación de LLMs
Experimentación detallada con técnicas de prompting para mejorar las capacidades de razonamiento de los modelos.
*   **Active Prompting:** Implementación de estrategias de razonamiento (Chain of Thought) aplicadas a datasets matemáticos como **GSM8K**.
*   **Datasets de Razonamiento:** Análisis y pruebas con **MultiArith** para evaluar la precisión lógica de modelos de lenguaje.
*   **Inferencia:** Pipelines de evaluación para medir la precisión y el rendimiento de las predicciones frente a la verdad de campo (*ground truth*).

### 3. Agentes Inteligentes (Framework LangChain)
Desarrollo de una arquitectura de agentes "desde cero" utilizando **LangChain** y **LangGraph**.
*   **Deep Agents:** Implementación de agentes de investigación capaces de gestionar su propio estado, planes de trabajo y sistemas de archivos virtuales.
*   **Capacidades de los Agentes:**
    *   **Gestión de Tareas:** Sistema de TODOs integrado para flujos de trabajo complejos.
    *   **Virtual File System:** Persistencia de contexto mediante operaciones de lectura/escritura en memoria.
    *   **Delegación:** Capacidad de crear sub-agentes especializados para tareas paralelas.
    *   **Investigación Autónoma:** Integración con herramientas de búsqueda (Tavily) y loops de reflexión estratégica.

## 🛠️ Tecnologías Principales

*   **Lenguaje:** Python
*   **IA/ML:** LangChain, Hugging Face (Transformers), Word2Vec, OpenAI/Google Models.
*   **Agent & Orquestación:** LangGraph, Custom State Management.
*   **Análisis de Datos:** JSON-based datasets, Pandas.

## 📁 Estructura del Proyecto

```text
├── LangChain/             # Arquitectura de Agentes y Gestión de Estado
│   ├── utils/             # Prompts de sistema y lógica de herramientas
│   └── ...
├── Prompting/             # Experimentos de CoT, Active Prompting y Datasets
│   ├── dataset/           # MultiArith y recursos de entrenamiento
│   └── output/            # Resultados de inferencia y benchmarking
└── ... (ML Projects)      # Clasificación de texto y recomendación
```

---

*Este repositorio es una bitácora de aprendizaje y experimentación técnica en el ecosistema de la IA moderna.*
