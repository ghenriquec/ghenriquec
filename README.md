# Guilherme Henrique

**Senior Software Engineer | Java & Spring Boot | Backend Systems, Correctness & Architecture**

Based in Belo Horizonte, Brazil · [LinkedIn](https://www.linkedin.com/in/guihenriquecoelho/) · [Dev.to](https://dev.to/ghenriquec) · [Email](mailto:guilhermehenriquecoelhos.dev@gmail.com)

I work on business-critical software, with an emphasis on **backend engineering, business rules, and systems that remain understandable and reliable as they evolve**. I have worked in software development since 2019, including financial-services and public-sector applications.

Currently a **Senior Software Engineer at PRODEMGE**, I focus primarily on Java and enterprise systems. My interests include consistency, distributed-system failure modes, pragmatic architecture, and AI-assisted software quality.

## Engineering evidence

I prefer executable examples and explicit trade-offs over long lists of technologies.

| Work | What you can inspect |
| --- | --- |
| **[Ledger Core — Java 21](https://github.com/ghenriquec/faang-engineer-path/tree/main/labs/ledger-core)** | In-memory transfer atomicity, idempotency, lock ordering, oversubscription tests and failure handling. [Architecture](https://github.com/ghenriquec/faang-engineer-path/blob/main/labs/ledger-core/ARCHITECTURE.md) · [Tests](https://github.com/ghenriquec/faang-engineer-path/blob/main/labs/ledger-core/src/test/java/dev/ghenriquec/ledger/LedgerTest.java) |
| **[PostgreSQL Ledger — JDBC / SQL](https://github.com/ghenriquec/faang-engineer-path/tree/main/labs/postgres-ledger)** | Relational transactions, durable idempotency keys, canonical row locks and concurrent integration tests with PostgreSQL. [Architecture](https://github.com/ghenriquec/faang-engineer-path/blob/main/labs/postgres-ledger/ARCHITECTURE.md) · [Integration tests](https://github.com/ghenriquec/faang-engineer-path/blob/main/labs/postgres-ledger/src/test/java/dev/ghenriquec/ledger/sql/PostgresLedgerTest.java) · [CI](https://github.com/ghenriquec/faang-engineer-path/actions/workflows/postgres-ledger.yml) |
| **[Universal Domain Rules Discovery](https://github.com/ghenriquec/universal-domain-rules-discover-skill)** | A portable agent protocol with JSON Schemas, behavioral validator tests, evidence traceability, and CI. |
| **[People Registration](https://github.com/ghenriquec/cadastro-pessoas)** | Java 17, Spring Boot, PostgreSQL, REST controllers, JUnit/Mockito tests, and a React interface. |
| **[QA Sentinel](https://github.com/ghenriquec/qa-sentinel-skill)** | A read-only QA auditing protocol: rule discovery, risk-based findings, evidence, and structured reports. |

These two labs deliberately separate **single-JVM safety** from **database transaction guarantees**. Both are educational exercises, not deployed financial services. Their ADRs explain observed deadlocks, recovery semantics and durability limits.

## Technical focus

- **JVM and backend:** Java, Spring Boot, APIs, persistence, domain modeling, and enterprise integrations.
- **Correctness and reliability:** concurrency, idempotency, automated tests, validation, and failure analysis.
- **Architecture:** system boundaries, trade-offs, evolutionary design, and distributed-systems fundamentals.
- **Delivery:** SQL / DB2, Docker, GitHub Actions; full-stack work with Angular and TypeScript.

## Engineering principles

**Design for clarity. Verify behavior. Document the trade-offs.**

I aim to make important business invariants visible in code and tests. When studying advanced patterns, I document what is implemented, what is measured, and what still needs evidence.

## Contact

[LinkedIn](https://www.linkedin.com/in/guihenriquecoelho/) · [Writing](https://dev.to/ghenriquec) · [Email](mailto:guilhermehenriquecoelhos.dev@gmail.com)
