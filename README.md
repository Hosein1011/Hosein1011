# Hossein Karimi

Computer Engineering undergraduate at **Sharif University of Technology** (Tehran, Iran).  
Focused on systems programming, information retrieval, and full-stack web applications.

[GitHub](https://github.com/Hosein1011) &bull; [LinkedIn](https://linkedin.com) &bull; `your.email@sharif.edu`

---

### Systems & Architecture

- **STK Motors ([Mahyarelect/stkmotor](https://github.com/Mahyarelect/stkmotor))**: Co-lead architect on a commercial B2B electromechanical catalog indexing 863 technical variants across 30 product families. Built with Next.js 16 (App Router), React 19, Prisma ORM 6, PostgreSQL 16, and Playwright E2E automation. (43 core commits).
- **BabyGit ([Hosein1011/BabyGit](https://github.com/Hosein1011/BabyGit))**: Git version control system implemented from scratch in pure C99 using direct POSIX filesystem APIs (`sys/stat`, `dirent`, `unistd`). Implements the staging index, parent-linked commit DAG, branch references (`HEAD`), status inspection, and history rollbacks.
- **Melora / sptfy ([Hosein1011/sptfy](https://github.com/Hosein1011/sptfy))**: Decoupled cloud audio streaming platform pairing a Next.js 15 SSR frontend with a stateless Django REST Framework API and PostgreSQL 17. Features role-based access control (RBAC), database-level subscription quota enforcement, and Docker Compose orchestration.
- **Gwent ([Hosein1011/Gwent](https://github.com/Hosein1011/Gwent))**: Standalone desktop implementation of The Witcher's card game built in Java 21 and JavaFX 19. Features FXML UI layouts, video background integration (`javafx-media`), complete rules engine across 5 factions and special card abilities, deck building, and profile persistence.

---

### Search & Vector Retrieval

- **MIR3 ([Hosein1011/MIR3](https://github.com/Hosein1011/MIR3))**: Hybrid multimodal product search engine combining sparse lexical signals (BM25) with dense neural embeddings using PyTorch and FAISS CPU. Employs Reciprocal Rank Fusion (RRF) and cross-encoder neural reranking. Packaged with `uv`.
- **Goodreads IR ([Hosein1011/MIR](https://github.com/Hosein1011/MIR))**: Information retrieval engine with custom positional inverted indexes, Okapi BM25 scoring, TF-IDF vector space modeling, MinHash Locality-Sensitive Hashing (LSH) for duplicate detection, and a Streamlit UI.
- **Music Advisor ([Hosein1011/Music-Advisor](https://github.com/Hosein1011/Music-Advisor))**: Java 21 recommendation service integrating Meta LLaMA 3.2 90B query synthesis with PostgreSQL's `pgvector` extension for 22-dimensional acoustic vector similarity search via JDBC.
- **DeFi Security Lab ([Hosein1011/BC-HW03](https://github.com/Hosein1011/BC-HW03))**: Smart contract security audit suite in Solidity and Hardhat analyzing Vault reentrancy exploits and NFT marketplace Denial of Service vulnerabilities with pull-payment fixes.

---

### Academic & Technical Leadership

- **Teaching Assistant & Student Project Manager** &mdash; *Advanced Programming (AP), Sharif University of Technology (Fall 2025)*  
  Managed technical scoping, architectural constraints, and deliverables for three enterprise platforms (Event Management, CRM, Co-working Space) across 150+ students.
- **Teaching Assistant & Product Scope Designer** &mdash; *Fundamentals of Programming (FOP), Sharif University of Technology (Spring 2026)*  
  Authored product specifications, UX interaction flows, and grading test suites for the university educational portal clone (**EDU**).

---

### Tech Stack

- **Languages:** C (C99), C++, Java (21 LTS), Python, TypeScript, JavaScript, SQL, Solidity, Verilog HDL, Bash
- **Web & Backend:** Next.js 16/15, React 19/18, Django REST Framework, Prisma ORM 6, Express.js, Flask
- **Databases & IR:** PostgreSQL (`pgvector`), SQLite, FAISS, BM25, TF-IDF, LSH MinHash, RRF
- **DevOps & Testing:** Docker, Docker Compose, Playwright (E2E), Jest, Vitest, JUnit 4/5, JaCoCo, PIT Mutation Testing
