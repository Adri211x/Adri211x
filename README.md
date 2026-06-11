# Hola, soy Adri 👋

Desarrollo herramientas de IA aplicadas a problemas concretos: agentes con herramientas, asistentes RAG, APIs locales, procesamiento de documentos, observabilidad y automatizacion. Me gusta construir proyectos que se puedan probar de punta a punta: interfaz, backend, logs, tests y una documentacion que explique bien como levantarlo.

[![GitHub](https://img.shields.io/badge/GitHub-Adri211x-181717?style=flat-square&logo=github)](https://github.com/Adri211x)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![OpenAI Compatible](https://img.shields.io/badge/OpenAI--compatible-111111?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-2563EB?style=flat-square)

## Proyectos en GitHub 🚀

### 🧠 [LLM Agent Workbench](https://github.com/Adri211x/llm-agent-workbench)

Workbench local para trabajar con LLMs mediante una API con agente, tool calling, subida de PDFs, monitor de logs en tiempo real y pruebas automatizadas.

**Que resuelve**

Permite conversar con un agente local conectado a herramientas reales: calculadora segura, lectura/escritura de archivos, listado de directorios, lectura de PDFs, busqueda web y fecha/hora configurable. Esta pensado como entorno de pruebas para agentes LLM con proveedores OpenAI-compatible como Groq, Ollama, OpenAI, LM Studio o vLLM.

**Puntos fuertes**

- ⚡ API principal con `FastAPI` y documentacion en `/docs`.
- 🛠️ Agente con bucle de tool calling de hasta 10 iteraciones por peticion.
- 📄 Subida y lectura de PDFs desde la interfaz web.
- 📡 Monitor de logs separado en tiempo real con WebSocket, filtros, busqueda y limpieza.
- 🔌 Cliente LLM unificado usando el SDK de OpenAI contra endpoints compatibles.
- 🧪 Suite de tests amplia, verificacion completa y cobertura minima configurada.

**Stack:** `Python` | `FastAPI` | `Uvicorn` | `OpenAI SDK` | `pypdf` | `pytest` | `pytest-cov` | `WebSocket` | `JavaScript` | `HTML` | `CSS`

```text
src/backend/     API FastAPI, agente, herramientas, tests y scripts
src/frontend/    UI del chat
src/log_ui/      Monitor de logs
src/metrics/     Dashboard de metricas
workspace/       Archivos del agente y PDFs subidos
```

---

### 🌴 [CancunIA](https://github.com/Adri211x/CancunIA)

Asistente turistico con IA generativa y RAG especializado en Cancun, Riviera Maya, Isla Mujeres, Tulum, Chichen Itza, Cozumel, cenotes, transporte, gastronomia, rutas e itinerarios.

**Que resuelve**

Convierte un corpus Markdown en una fuente de verdad consultable por un chatbot. El sistema no usa fine-tuning: ingesta documentos, limpia contenido, extrae metadatos, genera chunks semanticos y responde usando retrieval sobre una base vectorial.

**Puntos fuertes**

- ⚡ Backend `FastAPI` con endpoints de salud, configuracion, estado LLM, ingesta, retrieval, chat y borrado de vector store.
- 🔎 RAG con `ChromaDB`, embeddings y chunks enriquecidos con URL, dominio, categoria, ubicacion, seccion, fiabilidad y prioridad.
- 💬 Frontend de chatbot con `Streamlit`.
- 🤖 Soporte para Groq + Llama y proveedores OpenAI-compatible como Ollama, LM Studio o vLLM.
- 🧰 Scripts de setup, descarga de embeddings, ingesta, evaluacion y limpieza.
- 🧪 Monitor de logs local y tests para API, chatbot, chunker, cleaner, loader, retriever, vector store, config y clientes LLM.

**Stack:** `Python` | `FastAPI` | `Streamlit` | `ChromaDB` | `SentenceTransformers` | `Groq` | `Llama` | `Ollama` | `pytest` | `PowerShell` | `Dockerfile`

```text
app/        API, chatbot, configuracion, LLM y RAG
frontend/   Chatbot Streamlit
corpus/     Fuente Markdown del asistente
scripts/    Ingesta, evaluacion y utilidades
tests/      Cobertura funcional del sistema
```

## Lo que estoy construyendo 🧩

- 🤖 Agentes LLM con herramientas reales y control de ejecucion.
- 🔎 Sistemas RAG basados en fuentes controladas.
- ⚙️ APIs locales faciles de probar y documentar.
- 🖥️ Interfaces ligeras para interactuar con IA sin complicar el flujo.
- 📊 Observabilidad para entender que hace el agente, que herramientas usa y donde falla.
- 🧪 Tests y scripts de verificacion para que los prototipos sean reproducibles.

## Tecnologias que uso 🛠️

`Python` | `FastAPI` | `Streamlit` | `OpenAI SDK` | `Groq` | `Ollama` | `ChromaDB` | `SentenceTransformers` | `pypdf` | `pytest` | `pytest-cov` | `JavaScript` | `HTML` | `CSS` | `PowerShell` | `Docker`

## Perfil tecnico ✨

Me interesa la IA practica: no solo llamar a un modelo, sino rodearlo de contexto, herramientas, logs, evaluacion y una interfaz usable. En mis proyectos suelo cuidar tres cosas:

- Que el sistema tenga una arquitectura clara.
- Que se pueda levantar localmente sin friccion.
- Que el comportamiento sea observable y testeable.

## Contacto 📌

- Perfil: [github.com/Adri211x](https://github.com/Adri211x)
- Proyecto principal de agentes: [llm-agent-workbench](https://github.com/Adri211x/llm-agent-workbench)
- Proyecto RAG turistico: [CancunIA](https://github.com/Adri211x/CancunIA)
- Email: [adrianramolopez7@gmail.com](mailto:adrianramolopez7@gmail.com)
- LinkedIn: [Adrian Ramo Lopez](https://www.linkedin.com/in/adri%C3%A1n-ramo-l%C3%B3pez-297a18261/)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Adri211x&layout=compact&theme=transparent)
