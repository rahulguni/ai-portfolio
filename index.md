# Portfolio: AI & Machine Learning
**Rahul Guni** | Software Engineer & Infrastructure Architect

---

## Professional Bio
I am a Software Engineer and Infrastructure Architect specializing in building scalable, full-stack enterprise applications. Currently pursuing a Master of Science in Computer Info Systems with a specialization in AI, I am passionate about bridging the gap between raw data science and production-ready software infrastructure. My technical stack includes Java (Spring Boot), Python, TypeScript, Docker, and AWS (ECS Fargate, S3, CloudFront).

## Value Proposition and Audience
**Personal Value Proposition:** 
I offer the unique ability to not only understand complex Machine Learning and Artificial Intelligence models but also to architect the underlying distributed systems and frontend interfaces required to deploy them at an enterprise scale. 

**Target Audience:** 
The specific audience for this portfolio includes engineering managers, technical recruiters, and peer developers seeking versatile architects capable of managing end-to-end AI product lifecycles.

---

## Artifacts

### Artifact 1: Domain-Specific Educational AI Chatbot

<img width="1062" height="762" alt="Screenshot 2026-10-25 at 9 55 32 PM" src="https://github.com/user-attachments/assets/2208965b-9116-4dbb-a655-1a47794a30e5" />
<img width="1074" height="767" alt="Screenshot 2026-10-25 at 9 55 54 PM" src="https://github.com/user-attachments/assets/c89982c0-0777-4e4e-832a-6d462b83f0ff" />
<img width="1057" height="754" alt="Screenshot 2026-10-25 at 9 56 27 PM" src="https://github.com/user-attachments/assets/a7852881-4a6e-4d4f-b684-d7b11ba7c16e" />


**Introduction**
This artifact is a specialized educational chatbot developed as part of an applied Artificial Intelligence lab focusing on prompt engineering and LLM constraints.

**Artifact Description**
* **Objective:** To design a tightly constrained, persona-driven AI assistant capable of guiding users through educational workflows without hallucinating or breaking character.
* **Process:** Created individually. I engineered strict system instructions to define behavior and tone, established clear operational boundaries, and uploaded domain-specific knowledge files to ground responses using Retrieval-Augmented Generation (RAG).
* **Tools and Technologies Used:** Mizou AI Platform, Custom Prompt Engineering, System Rule Configuration, RAG Knowledge Files.

**Artifact-Specific Value Proposition**
* **Unique Value:** This artifact showcases my ability to bridge the gap between raw language models and deployment-ready software through structured prompt architecture.
* **Relevance:** It aligns with my personal value proposition by proving I can architect, constrain, and deploy user-facing AI tools safely for enterprise environments.

**Customization for Audience**
* **Adaptations Made:** I highlighted the system constraints and guardrails over the raw conversational output. 
* **Relevance:** This customization speaks directly to engineering managers who prioritize safety, alignment, and predictability when integrating generative AI into production.

**Reflection**
* **Significance:** I chose this artifact because it translates academic concepts into a tangible product, demonstrating a hands-on capability to control LLMs.
* **Lessons Learned:** I learned that strict boundary setting and context grounding are just as important, if not more so, than the base model selection when building reliable AI products.

**Feedback and Revisions**
* **Feedback:** Initial peer review suggested the bot was too willing to give away direct answers rather than guiding the user.
* **Revisions:** I revised the system instructions and boundary rules to force a Socratic teaching method, strictly preventing the output of final answers.

**References**
* Mizou Platform Documentation.
* "Prompt Engineering Guidelines" (OpenAI).

---

### Artifact 2: Distributed Portfolio Image Processing & Search Pipeline
<img width="682" height="728" alt="Screenshot 2026-11-01 at 7 44 34 PM" src="https://github.com/user-attachments/assets/c79e7751-0076-49b5-89a2-e626ac1d08ac" />


**Introduction**
This artifact details a high-throughput Machine Learning pipeline designed for image ingestion, deep learning embedding generation, and rapid data delivery. It was developed to evaluate ML vs. Deep Learning methodologies for semantic image search.

**Artifact Description**
* **Objective:** To architect a highly scalable, asynchronous data pipeline capable of rapidly processing portfolio assets and serving vector data to frontend applications.
* **Process:** Created individually as an architectural exercise. I designed a backend infrastructure utilizing Redis as a message broker to orchestrate isolated worker nodes (image processing, link processing, embedding generation, documenting). These asynchronous workers store finalized assets and vectors into AWS S3 buckets for the frontend read layer.
* **Tools and Technologies Used:** Redis, AWS S3, Asynchronous Worker Architecture, Python, Deep Learning Embedding Models.

**Artifact-Specific Value Proposition**
* **Unique Value:** This artifact showcases my deep backend engineering skills, specifically in orchestrating distributed data pipelines and managing the fast movement of data.
* **Relevance:** It demonstrates to technical recruiters that I can handle the heavy, underlying infrastructure required for AI integration, perfectly complementing my user-facing skills.

**Customization for Audience**
* **Adaptations Made:** I abstracted proprietary company data into a clean, generic Mermaid.js architectural flowchart.
* **Relevance:** This adaptation ensures the artifact is safe for public viewing while keeping the target audience focused on the structural logic and architectural patterns.

**Reflection**
* **Significance:** I selected this artifact because it demonstrates a fundamentally different skill set than my prompt-engineering artifact, proving my versatility as a full-stack infrastructure architect.
* **Lessons Learned:** I deepened my understanding of using Redis queues to decouple ML processing tasks, preventing backend bottlenecks during embedding generation.

**Feedback and Revisions**
* **Feedback:** Received feedback that the initial pipeline description was difficult to visualize without understanding the data flow.
* **Revisions:** Integrated a comprehensive architectural flowchart mapping the Redis broker and asynchronous worker nodes to clarify the system design for external stakeholders.

**References**
* AWS S3 Architecture Documentation.
* Redis Pub/Sub and Message Broker Documentation.
