# Ahmad Islam — Senior AI Engineer

**London, United Kingdom** · [mailto.ahmadai@gmail.com](mailto:mailto.ahmadai@gmail.com) · [+44 7539 106075](tel:+447539106075) · [linkedin.com/in/nlpengineer](https://linkedin.com/in/nlpengineer)

---

Senior AI Engineer with 5+ years designing and deploying production-grade AI systems across healthcare, legal, and insurance domains. Specialises in LLM-powered applications, multi-agent systems, and scalable cloud-native architectures — with a strong focus on reliability, automation, and real-world business impact. Experienced in taking AI products end-to-end: from problem framing and architecture through deployment, monitoring, and continuous improvement.

---

## Skills

| Area | Technologies |
|---|---|
| **AI Systems** | LLM Applications · Conversational AI · Multi-Agent Systems · RAG · Embeddings · MCP · Prompt Engineering · Voice & Telephony AI |
| **LLM Frameworks** | LangChain · LangGraph · Haystack · Dialogflow CX/ES · Vertex AI |
| **Programming** | Python · TypeScript · JavaScript · FastAPI · Node.js · React |
| **Cloud & DevOps** | AWS · GCP · Docker · Kubernetes · Terraform · CI/CD · Monitoring & Logging |
| **Data & Vector DBs** | PostgreSQL · BigQuery · Qdrant · Elasticsearch · OpenSearch |
| **Integrations** | Twilio · WebRTC · n8n · REST APIs |

---

## Experience

### AI Software Engineer — ThriveLink
*St. Louis, US · Remote · Contract · Apr 2025 – Present*

- Architected and deployed **Roger**, a multi-agent multilingual AI voice system built on LangGraph and an MCP question engine, guiding users through complex public benefit applications across multiple U.S. states — processing hundreds of applications per day with a **~30% increase in completion rates**
- Designed **Build-A-Bot**, a reusable AI platform that captures client requirements and automatically provisions Twilio voice bots — reducing setup time from days to minutes
- Engineered a state-specific PDF mapping pipeline that converts conversational session data into completed program applications and automatically faxes them to respective organisations, eliminating manual form-filling by care teams

`LangGraph` `MCP` `Python` `FastAPI` `Twilio` `WebRTC` `AWS` `PostgreSQL` `Voice AI`

---

### Conversational AI Engineer — PanteraGPT
*Fort Lauderdale, US · Remote · Contract · Mar 2024 – Jun 2025*

- Built **Consortium Legal**, a SaaS Legal AI platform for lawyers — automated scraping of Mexican Supreme Court cases, a Haystack-based RAG knowledge pipeline over non-uniform legal data, and a WhatsApp-connected assistant achieving **~85% case resolution accuracy**
- Self-hosted and maintained Rocket.Chat on AWS EC2 for an omnichannel lead-generation platform across 8 departments, with automated backups and monitoring
- Developed custom Rocket.Chat apps (WhatsApp template messaging, FlowXO bot integration), **automating 80% of lead capture** and increasing qualified leads by ~40%

`Haystack` `Python` `RAG` `WhatsApp APIs` `Rocket.Chat` `AWS EC2` `OpenSearch` `AWS Bedrock`

---

### Senior Backend Engineer — Coachendo AB
*Malmö, Sweden · Remote · Full-time · Aug 2022 – Feb 2024*

- Built the **Coachendo Chatbot Trainer**, a CLI tool that converts coaching scripts into Dialogflow CX training data — enabling rapid creation and continuous training of **50+ coaching bots** across multiple programs
- Developed an end-to-end **Coachendo Analytics** platform ingesting Dialogflow CX logs via Cloud Dataflow into BigQuery, with Looker Studio dashboards for session engagement and program effectiveness
- Built fine-tuning and batch inference pipelines for personality and emotion models on Vertex AI, powering personalised coaching insights

`Dialogflow CX` `Python` `Google Cloud Dataflow` `BigQuery` `Vertex AI` `Looker Studio`

---

### Associate AI Engineer — OpenAIMP
*Austin, US · Remote · Full-time · Jun 2021 – May 2022*

- Built end-to-end automation pipelines for text analytics, OCR, and document parsing, **reducing insurance contract processing time by 90%**
- Co-developed **Analyzer**, an MLOps platform for plug-and-play experimentation across datasets, models, and algorithms
- Developed ML-backed annotation tooling for standard datasets (TACRED, CoNLL, Pascal VOC), enabling fine-tuning of task-specific language models

`Python` `NLP` `OCR` `Machine Learning` `MLOps` `Deep Learning`

---

## Projects

| Project | Type | Stack | |
|---|---|---|---|
| [**Knobi**](./knobi/README.md) | RAG · Multi-tenant SaaS · LLM Agent | LangChain · Qdrant · FastAPI · Next.js · OpenAI | [→](./knobi/README.md) |
| [**PanteraGPT RAG**](./panteragpt-rag/README.md) | Legal RAG · Hybrid Search · Spanish NLP · Domain-Specialised Indexing | Haystack · OpenSearch · BM25 + KNN · Sentence Transformers · GPT-4o · FastAPI | [→](./panteragpt-rag/README.md) |
| [**Contabox**](./contabox/README.md) | Tax Automation AI · Prompt Engineering · Structured Outputs · Compliance | GPT-4 · LangChain · Pydantic · FastAPI · MongoDB · SAT API | [→](./contabox/README.md) |
| [**ThriveLink Bot Analytics**](./thrivelink-bot-analytics/README.md) | Data Pipeline · ETL · Conversation Analytics | Apache Beam · Dataflow · BigQuery · Dialogflow CX | [→](./thrivelink-bot-analytics/README.md) |
| [**Zovax**](./zovax/README.md) | RAG · WhatsApp AI · Multi-tenant SaaS | LangChain · Qdrant · FastAPI · React · WhatsApp API | [→](./zovax/README.md) |
| [**RelateHub**](./relatehub/README.md) | Conversational AI · Personality AI · Cross-platform | OpenAI · Dialogflow CX · React Native · Parse Server | [→](./relatehub/README.md) |
| [**Coachendo Chatbot Loader**](./coachendo-chatbot-loader/README.md) | Infrastructure Automation · Dialogflow CX · Internal Tool | Node.js · Dialogflow CX API · Google Sheets · Google Drive | [→](./coachendo-chatbot-loader/README.md) |
| [**Coachendo Chatbot Trainer**](./coachendo-chatbot-trainer/README.md) | ML Microservice · Embeddings · Clustering · Text Generation | Python · FastAPI · Sentence Transformers · KMeans · DialoGPT · OpenAI | [→](./coachendo-chatbot-trainer/README.md) |
| [**Coachendo Events**](./coachendo-events/README.md) | Event-Driven Microservices · Notification Engine · Serverless | Node.js · GCP Cloud Functions · Pub/Sub · Firebase FCM · MongoDB | [→](./coachendo-events/README.md) |
| [**Rocket.Chat × FlowXO**](./rocketchat-pantera-flowxo/README.md) | Livechat Integration · Bot Middleware · Rocket.Chat App | TypeScript · Rocket.Chat Apps SDK · FlowXO Webhook API | [→](./rocketchat-pantera-flowxo/README.md) |
| [**Rocket.Chat × WhatsApp**](./rocketchat-pantera-whatsapp/README.md) | WhatsApp Template Messaging · Livechat Integration · Rocket.Chat App | TypeScript · Rocket.Chat Apps SDK · Meta WhatsApp Cloud API | [→](./rocketchat-pantera-whatsapp/README.md) |
| [**Rocket.Chat Forward**](./rocketchat-pantera-forward/README.md) | Livechat Routing · Agent Availability · Rocket.Chat App | TypeScript · Rocket.Chat Apps SDK · Rocket.Chat REST API | [→](./rocketchat-pantera-forward/README.md) |
| **Xiomara** | Workflow Automation · AI Reporting | n8n · Gemini · Python | — |

---

## Education

**BSc (Hons) Software Engineering** — Sargodha University, Pakistan · CGPA 3.54/4.0 · **Gold Medalist**
Artificial Intelligence · Machine Learning · NLP · Data Structures · Big Data · Cloud Computing · Statistical Learning

**HSSC Pre-Engineering** — Aga Khan University Examination Board · 78% · **AKU EB Scholarship Holder**
Physics · Mathematics · Computer Science

---

## Certifications

**IELTS Academic** — British Council · Band 7.0 *(Listening 8.0 · Speaking 6.5 · Reading 6.5 · Writing 6.0)*
