# LearnMate – Agentic AI for Personalized Course Pathways

'''
this repo contains all the necessary certificates, Agent Code file and Project PPT PDF
'''


LearnMate is an agentic AI learning coach that builds personalized and adaptive course pathways for students based on their interests, current skill level, and learning preferences.
It uses IBM Watsonx.ai Granite LLMs + a vectorized knowledge base to ground recommendations in curated learning modules and guidance principles.

🚀 Features
Conversational intake to understand student goals and preferences.

Vector index retrieval from a 200+ chunk knowledge base.

Adaptive learning pathway generation (5–7 steps initially).

Dynamic feedback loop to adjust difficulty and pace.

Explainable recommendations citing retrieved modules.

Works across multiple domains:

Frontend / Backend Development

Data Science / AI / ML

Cybersecurity

UI/UX Design

Cloud / DevOps

Blockchain, AR/VR, and more


🧠 Architecture
Watsonx.ai Granite Model

Chat/Reasoning: ibm/granite-3-8b-instruct (or smaller for efficiency)

Embeddings: ibm/slate-125m-english-rtrvr (or similar)

Vector Index (Knowledge Base)

200+ curated chunks containing:

Module descriptions

Career guidance

Learning principles

Mini-project ideas

Stored in Watsonx.ai Vector Index for retrieval-augmented generation.

Retrieval-Augmented Generation (RAG) Flow

User query → Profile extraction → Vector search → LLM with system prompt + retrieved context → Pathway output.
