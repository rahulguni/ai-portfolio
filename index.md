# Portfolio: AI & Machine Learning
**Rahul Guni** | Software Engineer & Infrastructure Architect

## About Me
I am a Software Engineer and Infrastructure Architect specializing in building scalable, full-stack enterprise applications. Currently pursuing a Master of Science with a specialization in AI and Machine Learning, I am passionate about bridging the gap between raw data science and production-ready software infrastructure. 

## Skills
* **Languages & Frameworks:** Java (Spring Boot), Python (PyTorch, scikit-learn, pandas), TypeScript, Angular.
* **Infrastructure & Cloud:** AWS (ECS Fargate, S3, CloudFront), Docker, PostgreSQL.
* **AI/ML Competencies:** Prompt Engineering, Retrieval-Augmented Generation (RAG), Embedding Pipelines, Natural Language Processing.

---

## Artifact 1: Educational AI Chatbot Configuration

<img width="1062" height="762" alt="Screenshot 2026-10-25 at 9 55 32 PM" src="https://github.com/user-attachments/assets/2208965b-9116-4dbb-a655-1a47794a30e5" />
<img width="1074" height="767" alt="Screenshot 2026-10-25 at 9 55 54 PM" src="https://github.com/user-attachments/assets/c89982c0-0777-4e4e-832a-6d462b83f0ff" />
<img width="1057" height="754" alt="Screenshot 2026-10-25 at 9 56 27 PM" src="https://github.com/user-attachments/assets/a7852881-4a6e-4d4f-b684-d7b11ba7c16e" />


* **Title:** Domain-Specific Educational AI Chatbot
* **Objective:** To design a tightly constrained, persona-driven AI assistant capable of guiding users through educational workflows without hallucinating or breaking character.
* **Process:** I engineered strict system instructions to define the bot’s behavior and tone. I then established clear boundary rules to ensure the chatbot provided structured guidance rather than direct answers, and uploaded domain-specific knowledge files to ground the responses using Retrieval-Augmented Generation (RAG). 
* **Tools:** Mizou AI Platform, Custom Prompt Engineering, System Rule Configuration, RAG Knowledge Files.
* **Value Proposition:** This artifact demonstrates my ability to bridge the gap between raw language models and deployment-ready software. It shows I can architect, constrain, and deploy user-facing AI tools safely for enterprise or educational environments.

---

## Artifact 2: ML vs. Deep Learning - Portfolio Image Search Pipeline

<img width="682" height="728" alt="Screenshot 2026-11-01 at 7 44 34 PM" src="https://github.com/user-attachments/assets/c79e7751-0076-49b5-89a2-e626ac1d08ac" />


* **Title:** Distributed Portfolio Image Processing & Search Pipeline
* **Objective:** To architect a highly scalable, asynchronous data pipeline capable of rapidly processing portfolio assets, generating deep learning embeddings, and serving data to frontend applications.
* **Process:** I helped design a backend infrastructure heavily focused on Redis to orchestrate the fast movement of data. I implemented isolated worker nodes handling specific pipeline stages: image processing, link processing, embedding generation, and documenting. These workers operate asynchronously, pulling from Redis and ultimately storing the finalized assets and vector data into AWS S3 buckets, which serve as the highly available read layer for the frontend team. 
* **Tools:** Redis, AWS S3, Asynchronous Worker Architecture, Deep Learning Embedding Models, Distributed Data Pipelines.
* **Value Proposition:** This artifact showcases my backend engineering and infrastructure architecture skills. It proves I can design distributed, high-throughput systems that efficiently bridge the gap between heavy machine learning processing tasks and frontend data delivery.
