# Hospital Emergency - AI Assistant
 Intelligent RAG-Based Virtual Assistant for Hospital Information Management
The Hospital Emergency SOP AI Assistant is an AI-driven solution designed to automate hospital information delivery and improve operational efficiency.  
Built on a Retrieval-Augmented Generation (RAG) framework using Google Gemini, Pinecone Vector Database, and n8n Automation, the system provides accurate, context-aware answers to queries about hospital emergency procedures and standard operating protocols.
 System Overview
This solution integrates hospital Standard Operating Procedures (SOPs) into a secure, searchable AI knowledge base.  
When a patient, visitor, or staff member asks a question, the system retrieves the most relevant SOP data from Pinecone, processes it through Google Gemini, and delivers a precise and compliant response in real time.
Core Capabilities:-   Dynamic SOP retrieval through vector search (Pinecone)
- AI-powered contextual response generation (Google Gemini)
- End-to-end workflow automation (n8n)
- Continuous conversation memory and contextual understanding-
# Architecture Components
| Layer | Technology | Function |
| Workflow Engine | n8n Automation | Orchestrates all data flow and AI interactions |
| LLM Engine | Google Gemini Chat Model | Generates human-like, SOP-aligned responses |
| Vector Database | Pinecone | Stores and retrieves document embeddings |
| Embedding Model | Google Embeddings API | Converts SOP documents into searchable vectors |
| Memory Module | n8n Simple Memory Node | Enables multi-turn, context-aware conversations |
# Key Features and Benefits
- 24/7 Virtual Hospital Assistant – Always available to respond to emergency and procedural inquiries.  
- Policy-Compliant Answers – Ensures that all responses are based strictly on hospital-approved SOPs.  
- Operational Efficiency – Reduces workload on reception and support staff by automating repetitive queries.  
- Enhanced Patient Experience – Provides clear information to patients before visiting the hospital.  
- Scalable Knowledge Base – Easy to update when SOPs or policies change.  
- Data Privacy and Security – Operates within a controlled and compliant hospital environment.
# Practical Use Cases
- Pre-admission guidance for patients and attendants  
- Real-time emergency SOP access for on-duty staff  
- Automated query handling for hospital websites or kiosks  
- Digital onboarding and training for new healthcare staff  
- 24/7 support for public inquiries through WhatsApp or web chat integration
# Workflow Summary
1. SOP File Upload – Documents are uploaded and segmented for embedding  
2. Vectorization – Text segments are converted to embeddings using Google Embeddings API  
3. Storage – Embeddings are stored in Pinecone Vector Store for semantic retrieval  
4. Query Processing – Incoming user queries are matched against stored vectors  
5. Response Generation – Relevant SOP content is used by Google Gemini to generate accurate responses  
6. Memory Retention – The Simple Memory Node enables context continuity for natural conversation
# Strategic Advantages
- Zero downtime – Cloud-hosted and always active  
- Minimal human intervention – Automated document loading and embedding  
- Cost-efficient – Low operational cost using open and scalable components  
- Multi-department scalability – Can be extended beyond Emergency SOPs to other hospital departments  
# Repository Contents
- Hospital_Emergency_SOP.json – Complete n8n workflow for the RAG model  
- README.md – Project documentation and architecture overview  
## Project Access
Deployment Type: Private n8n Cloud Instance  
Version: v1.0 (October 2025)
# About the Developer
Developed by:  Ashraf  
Project Name: Hospital Emergency SOP AI Assistant  
Organization: SMT Digital Automation  
Tools: n8n, Google Gemini, Pinecone, Google Embeddings  
Contact: imashraf787@gmail.com
# License
© 2025 SMT Digital Automation. All rights reserved.  
This project is intended for institutional use and demonstration purposes within healthcare and automation environments.  
Hospital SOPs used in this project are for non-commercial, illustrative use only.
# Workflow Visualization

Below is a visual representation of the n8n workflow used in this project:

<img width="1366" height="619" alt="Hospital Emergency SOP" src="https://github.com/user-attachments/assets/b83ee188-b94b-4a05-9e96-45f3b74a5e22" />
