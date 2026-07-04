# Michael Rodrigo

**Ingeniería de Datos · Inteligencia Artificial · Desarrollo de Software** — Bilbao, España

Soy desarrollador de software y construyo sistemas de datos e IA de extremo a extremo: ingesta y orquestación de datos, fine-tuning de LLMs y despliegue en local. Vengo del desarrollo full-stack, lo que me da soltura en todas las capas de un producto, y soy bilingüe español-inglés.

Actualmente curso la especialización **Data Engineering e Inteligencia Artificial** (IFCD0077, 960 h): Apache Spark, Kafka, Deep Learning, NLP, MLOps y Cloud. Los proyectos de abajo están construidos de extremo a extremo siguiendo buenas prácticas: testing, CI, Docker y documentación.

## Proyectos destacados

| Proyecto | Qué hace | Stack |
|----------|----------|-------|
| Motor de LoRAs | Fábrica local de fine-tuning y despliegue de LLMs: 18 formatos de datos → LoRA → GGUF → servidor OpenAI-compatible en GPU, con agente ReAct y RAG. 511 tests, CI, Docker. Caso de estudio medido: su VLM afinado supera en +8,7 pts de F1 al pipeline clásico de EXIST 2025. *(Repo privado, publicación próxima)* | PyTorch · PEFT/TRL · llama.cpp · FastAPI · ChromaDB |
| [EXIST 2025](https://github.com/fmr693/EXIST-2025) | Detección multimodal de sexismo en memes (shared task CLEF 2025): OCR propio, XLM-RoBERTa + ResNet50 con ensembles, y fine-tuning VLM con LoRA. Evaluación con holdout estricto | PyTorch · Transformers · EasyOCR |
| [Pipeline Medallón AEMET](https://github.com/fmr693/Pipeline-medallon-bronze-silver-gold-AETMET) | Pipeline de datos meteorológicos en tiempo real con arquitectura medallón (bronze/silver/gold) | Kafka · MinIO (S3) · MongoDB · DuckDB · Streamlit · Docker |
| [Crypto Data Pipeline](https://github.com/fmr693/crypto-data-pipeline) | ELT del mercado cripto cada 5 minutos con el modern data stack y tests de calidad en el DAG | Airflow · dbt · PostgreSQL · Metabase · Docker |
| [IoT Streaming Pipeline](https://github.com/fmr693/iot-streaming-pipeline) | Ingesta IoT end-to-end: sensor simulado → broker → procesamiento en streaming → data lake | MQTT · Kafka · Spark Structured Streaming · MinIO/Parquet |
| [LLM Abliteration Toolkit](https://github.com/fmr693/llm-abliteration-toolkit) | Interpretabilidad mecanicista: localizar y neutralizar la dirección de rechazo de un LLM sin reentrenarlo (Arditi et al. 2024). Diff-Means, whitened SVD, COSMIC, steering vectors | PyTorch · Transformers |

## Stack técnico

**Ingeniería de datos** — Python · SQL · Apache Kafka · Apache Spark (PySpark) · Apache Airflow · dbt · PostgreSQL · MongoDB · DuckDB · MinIO/S3 · Docker

**IA / ML** — PyTorch · Hugging Face (Transformers, PEFT/TRL) · LLMs · Fine-tuning LoRA · RAG · Agentes (ReAct) · LangChain · llama.cpp/GGUF · TensorFlow/Keras

**Desarrollo web** — JavaScript/TypeScript · React · Angular · Node.js · Laravel

**BI y visualización** — Power BI · Tableau · Streamlit · Metabase

**Metodología** — Git · CI (GitHub Actions) · Testing · Docker · Desarrollo asistido por IA

## Contacto

[LinkedIn](https://www.linkedin.com/in/michael-rodrigo-1874a51a1) · [fmr693@gmail.com](mailto:fmr693@gmail.com)
