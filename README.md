# Hi, I'm Pruthvi Raj Panduga 👋

### Java Full Stack Developer | Spring Boot | Backend Engineering | Problem Solver

I build scalable backend systems, enterprise web applications, and AI-powered solutions using Java, Spring Boot, MySQL, Docker, and modern software architecture.

**Currently exploring:** System Design, Microservices, Kafka, Distributed Systems, Vector Databases & LLM Applications

---

## 📋 Quick Links

| Platform | Link |
| --- | --- |
| **LinkedIn** | [Connect with me](https://linkedin.com/in/your-linkedin) |
| **LeetCode** | [150+ DSA Problems](https://leetcode.com/u/pruthvi22_6/) |
| **GitHub** | [Explore my repositories](https://github.com/Pruthvi226) |
| **Email** | [Get in touch](mailto:yourmail@gmail.com) |

---

## 🏆 For Recruiters & Interviewers

**Start Here:** Review [SmartClinic](https://github.com/Pruthvi226/SmartClinic_Management_System) (8,500+ LOC, production-ready hospital management system)

### What You'll See:
- **Enterprise Architecture**: Layered MVC (Controllers → Services → DAOs → Entities)
- **Real Business Logic**: Smart slot allocation, billing automation, prescription workflows
- **Production-Ready Code**: Transaction management, role-based security, Docker deployment
- **Database Design**: 12+ tables with relationships, stored procedures, audit logging
- **Testing**: JUnit 5 + Mockito covering business-critical rules

### Code Highlights:
- 📁 **DAO Layer:** `src/main/java/com/smartclinic/dao/` - Hibernate repository patterns
- 📁 **Service Layer:** `src/main/java/com/smartclinic/service/` - Transactional workflows
- 🔧 **Complex Algorithm:** `SlotAllocator.java` - Priority-based appointment scheduling
- 🏗️ **Architecture:** `src/main/java/com/smartclinic/config/` - Spring configuration
- 🗄️ **DB Design:** `src/main/resources/schema.sql` - Relational modeling
- 🐳 **DevOps:** `Dockerfile` + `docker-compose.yml` - Production deployment

---

## 🚀 Tech Stack

### Languages & Frameworks

| Category | Technologies |
| --- | --- |
| **Backend** | Java 17/21, Spring Boot, Spring MVC, Spring Security, Hibernate ORM |
| **Frontend** | JSP, Thymeleaf, React, HTML5, CSS3, Bootstrap, JavaScript |
| **Database** | MySQL 8.0+, PostgreSQL, Redis, H2 (testing), FAISS (vector DB) |
| **DevOps & Tools** | Docker, Docker Compose, Maven, Git, Render, Railway |
| **APIs & Integration** | REST, JWT, Jackson, Swagger, OpenAI, Gemini API |
| **Testing** | JUnit 5, Mockito, Spring Test, AssertJ, Testcontainers |

### Skills Breakdown

**Backend Specialization:**
- Spring MVC, Spring Boot, Spring Security, Spring Transaction Management
- Hibernate ORM, JPA, Database relationships & indexing
- REST API design, JWT authentication, role-based access control (RBAC)
- MySQL schema design, transaction boundaries, SQL optimization

**Advanced Features:**
- AI/ML: Semantic search, vector embeddings, complaint classification
- Real-time: Queue management, notification systems, event scheduling
- Payment: Invoice generation, tax calculation, discount/refund workflows
- Search: Duplicate detection (Haversine formula), predictive scoring, Criteria API queries

---

## 🏥 Featured Projects

### 1️⃣ SmartClinic - Hospital Management System
**[Repository](https://github.com/Pruthvi226/SmartClinic_Management_System) • [Live Demo](https://smartclinicmanagementsystem-production.up.railway.app)**

![SmartClinic Dashboard](https://raw.githubusercontent.com/Pruthvi226/SmartClinic_Management_System/main/screenshots/admin-dashboard.png)

#### What It Does
Full-stack hospital operations platform handling appointments, consultations, pharmacy, inventory, billing, and multi-role workflows. Not just CRUD—includes smart business logic for slot allocation, billing automation, and prescription dispensing.

#### Key Features
- ✅ **Smart Appointment Scheduling**: Priority-based slot allocation respecting doctor availability
- ✅ **Role-Based Workflows**: Admin, Doctor, Receptionist, Pharmacist dashboards
- ✅ **Complete Billing Pipeline**: Auto-generated invoices, tax calculation, payment tracking
- ✅ **Pharmacy Management**: Inventory tracking, low-stock alerts, expiry monitoring
- ✅ **Audit Trail**: Comprehensive logging for compliance and troubleshooting
- ✅ **REST APIs**: JSON endpoints for patients, doctors, appointments, prescriptions

#### Technical Highlights
| Aspect | Detail |
| --- | --- |
| **LOC** | 8,500+ |
| **Database Tables** | 12 |
| **API Endpoints** | 25+ |
| **Test Coverage** | 75%+ |
| **Architecture** | Layered MVC with Spring Security & Hibernate |
| **Deployment** | Docker Compose, Tomcat 9, Railway |

#### Tech Stack
Java 17 • Spring MVC 5.3 • Hibernate 5.6 • MySQL 8.0 • JSP/JSTL • Spring Security • Docker • Maven

---

### 2️⃣ CivicFix+ - Smart Civic Issue Resolution Platform
**[Repository](https://github.com/Pruthvi226/CivicFix)**

![CivicFix Command Center](https://raw.githubusercontent.com/Pruthvi226/CivicFix/main/screenshots/official-command-center.png)

#### What It Does
Role-based municipal complaint management where citizens report civic issues, officials assign workers, field teams resolve problems, and the public tracks progress transparently. Includes AI complaint classification and duplicate detection.

#### Key Features
- ✅ **AI Complaint Classification**: NLP-based category and severity inference
- ✅ **Duplicate Detection**: Haversine formula to find nearby complaints within 100m
- ✅ **Civic Rewards**: Karma points for reporting, verified by officials
- ✅ **Predictive Maintenance**: ML-based maintenance advisories for risky zones
- ✅ **Transparent Dashboard**: Public analytics and ward health leaderboards
- ✅ **Secure Reporting**: Anonymous whistleblower mode with AES encryption
- ✅ **Multi-Role Workflows**: Citizen, Worker, Official, Admin dashboards

#### Technical Highlights
| Aspect | Detail |
| --- | --- |
| **Smart Features** | Complaint classification, duplicate radar, predictive scoring |
| **Database** | MySQL 8.0 with Haversine spatial queries |
| **Geolocation** | Leaflet.js maps for worker task assignment |
| **File Handling** | Multipart uploads with path traversal protection |
| **Audit Trail** | Karma transaction ledger + servlet performance filters |

#### Tech Stack
Java 21 • Spring MVC 5.3 • Hibernate 5.6 • MySQL 8.0 • JSP • Chart.js • Leaflet.js • Docker

---

### 3️⃣ AgriConnect - Agricultural Marketplace Platform
**[Repository](https://github.com/Pruthvi226/Agriconnect)**

![AgriConnect Marketplace](https://raw.githubusercontent.com/Pruthvi226/Agriconnect/main/screenshots/marketplace.png)

#### What It Does
Production marketplace connecting farmers and buyers with smart matching, MSP compliance, FPO management, and agricultural advisories. Real business logic for bidding workflows, order fulfillment, and farmer scoring.

#### Key Features
- ✅ **Smart Marketplace**: Crop listings with MSP compliance verification
- ✅ **Bidding System**: Buyer placement, farmer acceptance/rejection, counter-offers
- ✅ **Farmer Scoring**: Performance-based reputation using Haversine distance & delivery history
- ✅ **Matchmaking**: Intelligent buyer-farmer recommendations based on proximity & crop overlap
- ✅ **FPO Management**: Farmer Producer Organization groups for collective bargaining
- ✅ **Advisory System**: Crop/weather/disease/pest advisories with bulk notifications
- ✅ **Financial Tracking**: Wallet transactions, commission tracking, earned revenue

#### Technical Highlights
| Aspect | Detail |
| --- | --- |
| **Complex Algorithms** | Matchmaking scoring, farmer performance ranking |
| **API Security** | JWT authentication for REST endpoints |
| **Database** | 18+ tables with complex relationships & indexes |
| **Geospatial** | Haversine distance for nearby-buyer suggestions |
| **Scheduling** | Async advisory notifications, score recomputation jobs |

#### Tech Stack
Java 17 • Spring Framework 6.1 • Spring Security 6.2 • Hibernate ORM 6.4 • MySQL 8.3 • JSP • Docker

---

## 📊 Other Notable Projects

| Project | What It Is | Stack | Link |
| --- | --- | --- | --- |
| **EventSphere** | College event management with QR attendance & certificates | Java • Spring Boot • Thymeleaf • MySQL | [Repo](https://github.com/Pruthvi226) |
| **Smart Expense Manager** | Personal finance app with budgeting & insights | Java • Spring Boot • MySQL • Swagger • Docker | [Repo](https://github.com/Pruthvi226/Smart_Expense_Manager) |
| **AI Research Assistant** | PDF analysis with semantic search & vector embeddings | Python • Flask • React • FAISS • Transformers | [Repo](https://github.com/Pruthvi226/AI_Research_Assistant) |

---

## 🧠 Problem Solving & Algorithms

**150+ DSA Problems Solved on LeetCode**

### Strong Areas
- ✅ Arrays & Strings (sliding window, two-pointer techniques)
- ✅ Binary Search & Sorting
- ✅ Linked Lists & Trees (traversal, reconstruction)
- ✅ Graphs (BFS, DFS, shortest path, topological sort)
- ✅ Dynamic Programming (knapsack, subsequences, path counting)
- ✅ Greedy Algorithms
- ✅ Backtracking (permutations, combinations, N-Queens)
- ✅ Hash Maps & Heaps

### Applied Algorithms in Projects
- **Slot Allocation Algorithm**: Respecting doctor availability, leave dates, and patient priority (SmartClinic)
- **Haversine Distance Formula**: Duplicate detection & farmer-buyer geospatial matching (CivicFix, AgriConnect)
- **NLP Classification**: Keyword-based complaint categorization (CivicFix)
- **Scoring & Ranking**: Farmer performance and matchmaking recommendation engines (AgriConnect)

🔗 [View LeetCode Profile](https://leetcode.com/u/pruthvi22_6/)

---

## 💡 Architecture & Design Principles

### Layered MVC Architecture
```
Browser / REST Client
    ↓
Spring MVC DispatcherServlet
    ↓
Controllers (Request handling & routing)
    ↓
Service Layer (Business logic & transactions)
    ↓
DAO Layer (Hibernate data access)
    ↓
MySQL Database
```

### Design Patterns Used
- **DAO Pattern**: `GenericDaoImpl` base classes with entity-specific implementations
- **Service Layer Pattern**: Transactional business logic isolated from controllers
- **Repository Pattern**: Reusable query methods for complex searches
- **Strategy Pattern**: Slot allocation algorithms with priority variants
- **Observer Pattern**: Notification systems for events (orders, advisories)
- **Decorator Pattern**: Optional prescription draft saving before finalization

### Security Features
- ✅ Spring Security with role-based access control (ADMIN, DOCTOR, USER, EXPERT)
- ✅ BCrypt password hashing (never plaintext)
- ✅ CSRF protection on all state-changing operations
- ✅ JWT authentication for stateless REST APIs
- ✅ Session-based authentication for web applications
- ✅ Path traversal protection for file uploads
- ✅ SQL injection prevention through parameterized queries & Hibernate

---

## 🐳 DevOps & Deployment

### Containerization
- Multi-stage Docker builds (Maven compile → Tomcat runtime)
- Docker Compose for local full-stack development (app + MySQL + Adminer)
- Health checks and readiness probes
- Automatic schema bootstrap from SQL files

### Deployment Targets
- **Railway**: Production hosting for SmartClinic
- **Render**: Deployment-ready blueprints
- **Docker Hub**: Publishable container images
- **Local**: Maven Jetty/Cargo for development

### Key DevOps Files
| File | Purpose |
| --- | --- |
| `Dockerfile` | Multi-stage Maven build + Tomcat 9 runtime |
| `docker-compose.yml` | Full stack: app, MySQL, Adminer, health checks |
| `render.yaml` | Render platform deployment config |
| `.env.example` | Environment variable template |
| `schema.sql` | Database initialization with seed data |

---

## 📈 Project Metrics

| Project | LOC | Tables | APIs | Tests | Status |
| --- | --- | --- | --- | --- |
| SmartClinic | 8,500+ | 12 | 25+ | 50+ | ✅ Active |
| CivicFix+ | 6,200+ | 8 | 20+ | 30+ | ✅ Complete |
| AgriConnect | 7,800+ | 18 | 35+ | 60+ | ✅ Complete |
| **Total** | **22,500+** | **38** | **80+** | **140+** | ✅ Production-Ready |

---

## 🎯 Current Learning & Exploration

- 📚 **System Design**: Database sharding, caching strategies, load balancing
- 📚 **Microservices**: Spring Cloud, service discovery, API gateway patterns
- 📚 **Message Queues**: Kafka for event-driven architectures
- 📚 **Distributed Systems**: Consensus algorithms, distributed tracing
- 📚 **Vector Databases**: FAISS, Pinecone, LLM embeddings
- 📚 **AI/LLM**: RAG systems, prompt engineering, fine-tuning

---

## 🤝 Connect & Collaborate

I'm always interested in:
- Backend engineering challenges
- Open-source contributions
- System design discussions
- AI/ML integration projects

<p align="center">

<a href="https://github.com/Pruthvi226">
<img src="https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github">
</a>

<a href="https://linkedin.com/in/your-linkedin">
<img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin">
</a>

<a href="mailto:yourmail@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail">
</a>

</p>

---

## 🎓 Key Takeaways

This portfolio demonstrates:

✅ **Enterprise Architecture** - Layered MVC with clear separation of concerns  
✅ **Real Business Logic** - Not toy CRUD apps; slot allocation, billing, marketplace matching  
✅ **Production-Ready** - Docker deployment, security, audit logging, transactions  
✅ **Database Expertise** - Complex schemas, relationships, indexing, query optimization  
✅ **Problem Solving** - Algorithm implementation, duplicate detection, scoring systems  
✅ **Testing & Quality** - JUnit 5, Mockito, meaningful test coverage  
✅ **DevOps Awareness** - Docker, Docker Compose, CI/CD ready  
✅ **Full-Stack Skills** - Backend + frontend, REST + MVC paradigms  

---

### 💬 "Building software that solves real-world problems through scalable engineering and clean architecture" 🚀
