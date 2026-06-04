# Legal Tech RAG Search Engine (Lovable + Supabase Prototype)

A high-velocity legal technology prototype designed to optimize information retrieval for dense legal documents and Malaysian statute queries. This platform transitions traditional database lookups into an intelligent, AI-driven search experience by leveraging grounded data pipelines.

---

Prototype Link: https://id-preview--1e6c3967-7e14-4ff6-9999-54a1b9f5a0d1.lovable.app/auth

## 🛠️ Tech Stack & Architecture

This prototype balances rapid client-side prototyping with a robust cloud database to manage real-time application states:

* **Frontend Engine:** React / TypeScript orchestrated via Lovable for seamless user interface updates.
* **Backend Database:** Supabase (PostgreSQL) handling data storage and user session states.
* **AI Layer:** Grounded Retrieval-Augmented Generation (RAG) concepts designed to look up context accurately.

---

## 💡 System Focus

* **Contextual Search:** The core engine is built to query legal data rows efficiently from the connected backend storage.
* **Hallucination Prevention:** The interface is engineered with strict logical boundaries, forcing the AI to align with specified data blocks rather than guessing information out of bounds.
* **Clean Data Flow:** Focuses on a smooth server-to-client pipeline where user questions are securely processed and matched against stored reference materials.
