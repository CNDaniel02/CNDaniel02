# Daniel (Dongmin) Wu

**AI Application Engineer · Full-Stack Builder · Data Systems**

Los Angeles, California  
M.S. in Mathematical Data Science at the University of Southern California  
B.S. in Statistics and Mathematics, Minor in Computer Science, from UC Davis

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dongmin_Wu-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dongmin-wu-7811452a2)
[![Email](https://img.shields.io/badge/Email-dongminw%40usc.edu-EA4335?logo=gmail&logoColor=white)](mailto:dongminw@usc.edu)

I build AI products that connect models, data, infrastructure, and real user workflows. My recent work includes large-scale visual retrieval, local-first speech intelligence, authenticated full-stack platforms, RAG and graph-based search, and resumable data pipelines operating across tens of millions of records.

My strongest areas are **AI application engineering, backend and full-stack product development, retrieval systems, data infrastructure, and technical product execution**.

---

## Selected Engineering Work

### [ArtAuction Image Search](https://github.com/CNDaniel02/artauction_image_search)
**Large-scale visual retrieval for imperfect real-world artwork images**

- Designed an end-to-end retrieval system for a corpus of more than **41 million auction images**.
- Built manifest generation, metadata catalogs, image preprocessing, multi-model embeddings, sharded FAISS indexes, candidate fusion, re-ranking, and FastAPI serving.
- Developed query handling for screenshots, crops, borders, compression, rotation, reflections, and other real-world distortions.
- In a 100,000-image pilot, the SSCD retrieval path reached **98.20% Top-1** and **99.82% Top-5** accuracy across 4,500 transformed queries.
- The public repository demonstrates the reproducible architecture while excluding private images, manifests, embeddings, indexes, credentials, and infrastructure details.

`Python` `FastAPI` `FAISS` `SSCD` `DINOv2` `SQLite` `Parquet` `Computer Vision`

### Local Scribe
**Local-first real-time transcription, translation, and meeting intelligence**  
Current system is private; the earlier transcription foundation is available in [Transcriber](https://github.com/CNDaniel02/Transcriber).

- Built browser-to-local-machine audio streaming over WebSocket with real-time partial and final subtitles.
- Added `faster-whisper` ASR, asynchronous speaker-change and overlap detection, persistent project-level speaker profiles, timestamps, SQLite storage, and VTT export.
- Implemented local Chinese-English translation with glossary protection and revision tracking.
- Added local LLM-based staged summaries with resource-aware fallback behavior.
- Designed secure mobile access through private HTTPS/WSS connectivity while keeping inference and stored data on the user's own computer.

`Python` `FastAPI` `WebSocket` `faster-whisper` `SQLite` `llama.cpp` `PWA` `Local AI`

### [USC Course Group Finder](https://github.com/CNDaniel02/SESE-USC-Course-Web)
**Authenticated campus course discovery and community infrastructure**

- Built a full-stack Next.js application for USC students to search courses and access course-specific information.
- Implemented Google authentication with `@usc.edu` enforcement, role-aware administration, Prisma/MySQL data access, search, filters, and pagination.
- Extended the product direction toward a school-scoped group directory with administrative workflows, auditable access controls, and enterprise messaging integration.
- Worked across product requirements, database design, authentication, security boundaries, backend APIs, frontend flows, testing, and deployment planning.

`Next.js` `TypeScript` `React` `NextAuth` `Prisma` `MySQL` `Tailwind CSS`

### Knowledge Retrieval and Graph Search

- [RagHop](https://github.com/CNDaniel02/RagHop): multi-hop RAG with semantic chunking, FAISS retrieval, multiple knowledge bases, conversational context, and optional web augmentation.
- [Neo4j NL2Cypher](https://github.com/CNDaniel02/neo4j-nl2cypher-llm): full-stack natural-language query layer that generates Cypher, executes it against Neo4j, and summarizes structured results for non-technical users.

`RAG` `Embeddings` `FAISS` `LangChain` `Neo4j` `Flask` `Vue.js`

### Large-Scale Data Infrastructure
**Private infrastructure project supporting the image retrieval system**

- Designed a resumable **100+ TB** Aliyun OSS-to-local backup and validation pipeline.
- Managed more than **41 million object records** through inventory normalization, manifests, batch state machines, retries, checksums, extraction, and per-disk indexes.
- Coordinated cloud workers, segmented archives, parallel downloads, SSD staging, multi-HDD extraction, failure recovery, and cleanup controls.
- Treated observability, resumability, provenance, and safe restart behavior as core system requirements rather than afterthoughts.

`Python` `Aliyun OSS` `aria2` `SQLite` `Parquet` `Windows` `Linux` `Data Pipelines`

### Additional Product Builds

- **PikThrift:** Saleor/GraphQL e-commerce deployment with React storefront work, Docker, AWS, and Stripe integration.
- **Internal company intelligence:** AI-assisted search and structured company discovery using RAG, automation, and data workflows.
- **Analytics projects:** PostgreSQL ETL, Looker Studio dashboards, regression, ANOVA, forecasting, and business-facing analysis.

---

## Engineering Approach

I prefer projects where AI is one component of a complete system rather than an isolated demo. I focus on:

- translating ambiguous product requirements into concrete architecture and workflows;
- separating offline data preparation from reliable online serving;
- measuring retrieval or model quality with reproducible evaluations;
- building resumable pipelines for long-running and failure-prone workloads;
- keeping private data, credentials, model artifacts, and deployment details out of public repositories;
- documenting limitations clearly and avoiding claims beyond what the system can verify.

---

## Technical Stack

**AI and retrieval**  
Python, RAG, embeddings, semantic search, FAISS, LangChain, LlamaIndex, Neo4j, Whisper/faster-whisper, local LLM inference, computer vision retrieval

**Backend and full stack**  
FastAPI, Flask, Node.js, Next.js, React, Vue.js, REST APIs, WebSocket, NextAuth, Prisma, SQLAlchemy

**Data and infrastructure**  
PostgreSQL, MySQL, SQLite, SQL, Parquet, object storage, Docker, AWS, Aliyun, nginx, Git, Windows and Linux automation

**Analytics**  
R, pandas, NumPy, scikit-learn, regression, time series, ANOVA, experimental analysis, Looker Studio, Excel

---

## Current Direction

I am continuing to work on:

- local-first and privacy-conscious AI systems;
- multimodal retrieval and large-scale indexing;
- production-oriented RAG and agent workflows;
- full-stack AI products with measurable user value;
- reliable backend, data, and automation infrastructure.

I am open to **software engineering, AI application engineering, backend, full-stack, data engineering, and technical product opportunities**, with Los Angeles and California as preferred locations.
