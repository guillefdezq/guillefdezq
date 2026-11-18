# Hi, I'm Guillermo 👋

**Computer Engineering Graduate | Software Development · Backend · Testing & V&V · Systems**

I'm a Computer Engineering graduate from the **Universidad Nacional de Educación a Distancia (UNED)** (2026), based in Madrid, Spain.

My academic projects have given me hands-on experience in software design, backend development, full-stack integration, automated testing, compiler construction, and computer systems. I'm particularly interested in understanding how software works, building maintainable solutions, and solving technical problems systematically.

I'm **open to junior opportunities across Computer Engineering**, including — but not limited to — software development, backend engineering, software testing and verification, systems integration, and cybersecurity.

## 🛠️ Technical Skills

### Programming languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

*Also familiar with assembly programming through compiler coursework.*

### Web development and APIs

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![DRF](https://img.shields.io/badge/Django_REST_Framework-A30000?style=for-the-badge) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) ![REST API](https://img.shields.io/badge/REST_APIs-0A66C2?style=for-the-badge) ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### Data, infrastructure and development tools

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Testing, networking and security tools

![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white) ![Nmap](https://img.shields.io/badge/Nmap-214478?style=for-the-badge)

These technologies reflect academic projects and independent practice; they are not claims of professional expertise in every tool listed.

## 💻 Featured Work

### 🎓 Online Learning Platform with a Hybrid Recommendation System — Bachelor's Thesis

**UNED · 2026 · Individual project · Grade: 9/10**

[**Explore the source code and documentation**](https://github.com/guillefdezq/PFG-UNED-2026-LSI-DACOR)

I independently designed and implemented an online learning platform combining **course management**, **learning activity tracking**, and **personalised course recommendations**. The application includes user roles, course content, enrolments, submissions, quizzes, ratings, progress statistics, and administrative functionality.

The project focuses on integrating a **hybrid recommendation engine** into a working full-stack application, rather than developing a recommender in isolation.

**Architecture and implementation:**

- **Backend and authentication:** Python, Django, Django REST Framework, REST APIs, and JWT-based authentication.
- **Frontend:** React, Vite, React Router, Axios, and Recharts for interactive interfaces and visualisations.
- **Persistence and file storage:** PostgreSQL and S3-compatible object storage using MinIO.
- **Hybrid recommender:** Python and scikit-learn, combining user activity, content affinity, course popularity, and interaction signals to generate personalised recommendations.
- **Service orchestration:** Docker Compose for frontend, backend, database, object storage, and recommendation-related processes, with environment configuration, persistent volumes, and health checks.
- **Testing and validation:** automated backend and recommender tests with Python/Django testing tools and Pytest, frontend testing with Vitest, simulated user interactions, validation evidence, and basic load-testing scripts.

The repository includes reproducible local setup instructions, sample-data generation, test commands, and ways to inspect recommendation results. **Simulated interactions support functional testing and demonstrations; they should not be confused with a real-world evaluation of recommendation quality.**

**Tech:** `Python` · `Django` · `Django REST Framework` · `React` · `Vite` · `PostgreSQL` · `MinIO` · `scikit-learn` · `Docker Compose` · `Pytest` · `Vitest`

### 🧩 Compiler for the ENS2001 Architecture — Language Processors II

**UNED · Academic coursework (2023–2024) · Practical assignment grade: 10/10**

[**Compiler repository**](https://github.com/guillefdezq/ArquitecturaPLII2023-2024)

A compiler implemented in **Java** for an educational source language (`.ces`), generating assembly code for the **ENS2001 architecture** (`.ens`). The project explores the main stages of compiler construction and the transition from source code to lower-level instructions.

- **Lexical analysis:** token recognition and error handling using **JFlex**.
- **Syntax analysis:** grammar definition and parser generation using **Java CUP**.
- **Semantic analysis:** handling of types, declarations, identifiers, and scopes.
- **Intermediate representation:** quadruples, temporary values, labels, and procedure-related structures.
- **Code generation:** translating intermediate operations into ENS2001 assembly, involving registers, memory, and procedure calls.
- **Testing:** sample input programs and generated assembly, including factorial and Fibonacci examples.

The implementation uses supporting compiler libraries provided for the university course; it is an **academic compiler**, not a production-ready compiler built entirely from scratch.

**Tech:** `Java` · `JFlex` · `Java CUP` · `Apache Ant` · `ENS2001 Assembly` · `Git`

### 🔐 Cybersecurity & Networking — Controlled Virtual Lab

**Independent learning · Isolated, non-production environment**

I have practised introductory ethical-hacking and network-analysis techniques using a **deliberately vulnerable virtual machine**, obtained through contacts with **FDIst**, an ethical-hacking group associated with the Faculty of Computer Science at the Complutense University of Madrid (UCM).

My practical exploration has included:

- **Service discovery and reconnaissance** using Nmap.
- **Traffic capture and protocol analysis** using Wireshark.
- **Investigation of vulnerabilities** in an authorised, controlled laboratory environment.
- Applying academic foundations in **computer networks, security, and cryptography** to hands-on experimentation.

This is a **learning activity**, not professional penetration-testing experience or a claim of having performed an external security audit.

**Tools and topics:** `Nmap` · `Wireshark` · `Virtual Machines` · `Network Analysis` · `Cybersecurity Fundamentals`

## 🎓 Education

**Bachelor's Degree in Computer Engineering** — Universidad Nacional de Educación a Distancia (UNED), Spain · **2021—2026**

Relevant areas include software engineering, algorithms and data structures, operating systems, computer architecture, databases, networks, concurrency, and compilers.

## 🔍 Areas of Interest

Software engineering · Backend development · Software testing and verification (V&V) · Computer systems · Systems integration · Cybersecurity · Other Computer Engineering disciplines

## 🌍 Languages

- **Spanish:** Native
- **English:** C1 (CEFR) — Aptis ESOL General, British Council (2026)
- **Chinese:** Knowledge approximately corresponding to the former HSK 3, roughly equivalent to CEFR A2 *(not certified)*
- **French:** Basic knowledge from secondary education, roughly equivalent to CEFR A2 *(not certified)*
- **German:** Beginner; currently learning, roughly equivalent to CEFR A1 *(not certified)*

## 📫 Connect

[**LinkedIn**](https://www.linkedin.com/in/guillermo-fern%C3%A1ndez-quesada-5899b323a/)
