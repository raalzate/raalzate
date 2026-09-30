<div align="center">

# Raúl Alzate

### Arquitecto de Soluciones · IA Generativa · Ingeniería de Agentes

**Diseño sistemas donde la IA trabaja de verdad: agentes gobernados, arquitecturas en la nube que escalan y herramientas que convierten conocimiento de negocio en software.**

[![AWS Certified](https://img.shields.io/badge/AWS-Certified_Solutions_Architect-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)](#)
[![GenAI](https://img.shields.io/badge/IA_Generativa-Agentes_·_RAG_·_MCP-6E40C9?style=for-the-badge)](#)
[![DDD](https://img.shields.io/badge/DDD-Event_Storming_·_Microservicios-0A7E8C?style=for-the-badge)](#)
[![Maestría](https://img.shields.io/badge/Maestría-Aplicaciones_Inteligentes_·_Univalle-C8102E?style=for-the-badge)](#)

</div>

---

## En una frase

> **Una regla sin un comando que la haga fallar es una sugerencia.**
> Construyo la infraestructura que hace que los agentes de IA cumplan las reglas de tu equipo — y la arquitectura que hace que tus sistemas aguanten el crecimiento.

Más de una década pasando de Java/Android y microservicios a **IA generativa en producción**: RAG empresarial sobre AWS, agentes con herramientas (MCP), inferencia local y ahora **harness engineering** — el oficio de gobernar agentes de código.

---

## Qué puedo hacer por tu equipo

| | Servicio | Qué te llevas |
|---|---|---|
| 🛡️ | **Gobernanza de agentes de código** (Claude Code, Codex, Hermes) | Hooks, gates y frenos probados que evitan que el agente rompa lo que no debe. Tu equipo adopta IA sin perder calidad. |
| 🧠 | **Soluciones de IA generativa en AWS** | RAG empresarial, Bedrock, Knowledge Bases, multi-agente, guardrails, PII y control de costo de tokens — con IaC y listo para auditoría. |
| 🏗️ | **Arquitectura y modernización** | De monolito a microservicios con análisis estático, métricas de acoplamiento/cohesión y ADRs. Decisiones medidas, no intuiciones. |
| 🧩 | **Descubrimiento de dominio con IA** | Event Storming y DDD asistidos por IA: de la transcripción de un taller a un modelo de dominio, diagramas C4/BPMN y especificaciones. |
| 🔒 | **IA local y privada** | Apps de escritorio con inferencia on-device (WebGPU, LLMs locales). Tus datos no salen de tu máquina. |
| 🎓 | **Formación y mentoría** | Katas, guías y talleres de IA en AWS, prompt engineering y certificación de Claude. |

---

## Proyectos destacados

### 🛡️ Ingeniería de agentes

- **[agent-harness](https://github.com/raalzate/agent-harness)** — Arnés portable para agentes de código: hooks del ciclo del agente, gate declarativo, self-test que prueba que cada freno *muerde*, subagentes revisores y un ciclo que convierte cada incidente en un mecanismo. Agnóstico de lenguaje, cero dependencias, Windows/macOS/Linux. **[→ sitio](https://raalzate.github.io/agent-harness/)**
- **[hermes-harness](https://github.com/raalzate/hermes-harness)** — El mismo método para **Hermes Agent** (Nous Research): frenos en herramientas, memoria, skills y cron, porque un agente que aprende y corre desatendido necesita reglas que se cumplan solas.

### 🧩 Arquitectura y dominio con IA

- **[processflow-architect](https://github.com/raalzate/processflow-architect)** — Estudio de **Event Storming** de escritorio con agente ReAct **100 % local** (LiteRT-LM + WebGPU). DDD · BPMN · C4 · UML, ADRs y roadmaps versionados, puente MCP con Claude Code. **[→ sitio](https://raalzate.github.io/processflow-architect/)**
- **[static-inference](https://github.com/raalzate/static-inference)** — Análisis estático de Java y .NET que agrupa componentes y **propone microservicios con nombres de negocio**. CLI y servidor MCP. [▶ demo](https://www.youtube.com/watch?v=m8U0r368jR8)
- **[ia-ddd-studio](https://github.com/raalzate/ia-ddd-studio)** — De la grabación de un taller a un modelo de dominio DDD: Whisper + LangGraph, validación del grafo, agente conversacional y simulación multi-agente de talleres.
- **[ia-arch-view](https://github.com/raalzate/ia-arch-view)** — Visualiza y moderniza apps Java con IA: métricas CBO/LCOM, detección de patrones y propuestas de corte a microservicios. [▶ demo](https://youtu.be/ndbPA8qsZJE)

### ☁️ IA generativa en AWS

- **[aws-rag-enterprise](https://github.com/raalzate/aws-rag-enterprise)** — Asistente RAG para contact center sobre el historial de casos de Salesforce: AppFlow → S3 → Bedrock Knowledge Base → OpenSearch Serverless. Respuestas con citas en < 10 s.
- **[ia-aws](https://github.com/raalzate/ia-aws)** — **20 casos de uso de IA/ML** en AWS con CloudFormation: RAG, routing y fallback de modelos, multi-agente, human-in-the-loop, guardrails, PII y monitoreo de costo.

### 🎓 IA aplicada a la educación

- **[emma-desktop](https://github.com/raalzate/emma-desktop)** — Tutora de inglés conversacional para profesionales de TI, local-first (Electron + Next.js). Trabajo integrador de la Maestría en Univalle. **[→ sitio](https://raalzate.github.io/emma-desktop/)**
- **[ia-coach-agent](https://github.com/raalzate/ia-coach-agent)** · **[ia-english-listening-lab](https://github.com/raalzate/ia-english-listening-lab)** — Tutor con LLMs locales y currículo MCER; laboratorio de *listening* con Whisper palabra por palabra.
- **[ia-claude](https://github.com/raalzate/ia-claude)** — Guía de preparación para la certificación de Claude: dominios, katas ejecutables y banco de preguntas.

---

## Stack

**IA:** LLMs · RAG · Agentes (ReAct, multi-agente) · MCP · LangGraph · Whisper · inferencia local (WebGPU, llama.cpp) · Claude · Gemini · Bedrock
**Cloud:** AWS (Bedrock, Lambda, Step Functions, OpenSearch, SageMaker, CloudFormation) · Serverless · IaC
**Arquitectura:** DDD · Event Storming · Clean/Hexagonal · Microservicios · CQRS · C4 · ADRs
**Lenguajes:** TypeScript · Python · Java · C# · JavaScript
**Apps:** Electron · Next.js · Streamlit · FastAPI

---

<div align="center">

**¿Tu equipo quiere adoptar agentes de IA sin perder el control, o llevar IA generativa a producción en AWS?**
Hablemos: abre un issue en cualquiera de mis repos o escríbeme.

<sub>Los proyectos anteriores a 2025 están archivados: siguen disponibles, pero lo que muestro es lo que construyo hoy.</sub>

</div>
